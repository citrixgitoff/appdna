#Analyze applications

using AppDNA = Citrix.SDK.AppDNA;
AppDNA.Server appdna;
//Connect appdna

	public void Analyze(string reportConfigIdentifier, IEnumerable<AppDNA.Application> applications)
	{
		var reportConfig = appdna.ReportConfiguration.Get(reportConfigIdentifier);
		var analysis = reportConfig.Analyze( applications ); analysis.WaitForCompletion();
	
		switch (analysis.ProcessingState.State)
		{
			case AppDNA.RunningState.Canceled:
				Console.WriteLine("The analysis was canceled");
				break;
			case AppDNA.RunningState.Completed:
				Console.WriteLine("The analysis completed successfully");
				break;
			case AppDNA.RunningState.Failed:
				Console.WriteLine("The analysis failed with error: " + analysis.ProcessingState.Result:;
				break;


public void Analyze(IEnumerable<AppDNA.Application> applications)









##Monitoring progress

Use the Analysis object returned from a call to Analyze to monitor the progress and success of the analysis. Analysis.ProcessingState implements INotifyPropertyChanged so that, for example, a GUI application can update controls with details of the analysis as it proceeds.

The return from WaitForCompletion does not provide any indication of the success or otherwise of the analysis. To get an indication, check the Analysis.ProcessingState.State property. The WaitForCompletion method waits until the analysis is no longer running, while still allowing event handlers to be raised on the current thread's SynchronizationContext.

To wait for completion without running the current thread's SyncronizationContext, run a loop waiting for Analysis.IsFinished to return true, typically with a Thread.Sleep(…) call inside the loop.