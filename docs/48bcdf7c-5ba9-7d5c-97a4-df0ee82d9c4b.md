# XenUpgradeSolutionPlatform Class
 

Xen Upgrade Solution platform with OS, additional parameters, applications


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">Citrix.SDK.AppDNA.Solutions.Xen.Common.XenSolutionPlatform</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade.XenUpgradeSolutionPlatform<br />
**Namespace:**&nbsp;<a href="2805b95f-a335-5d98-deaf-c0312b394eda">Citrix.SDK.AppDNA.Solutions.XenUpgrade</a><br />**Assembly:**&nbsp;Citrix.SDK.AppDNA.Solutions.XenUpgrade (in Citrix.SDK.AppDNA.Solutions.XenUpgrade.dll) Version: 7.11.0.0 (7.11.0.0)

## Syntax

**C#**
```csharp
public class XenUpgradeSolutionPlatform : XenSolutionPlatform
```

**VB**
```vbnet
Public Class XenUpgradeSolutionPlatform
	Inherits XenSolutionPlatform
```

The XenUpgradeSolutionPlatform type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="ee135b27-2580-4bd6-c995-890c482e70c2">AlternateImages</a></td><td>
Gets the alternate images.
 (Inherited from <a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">XenSolutionPlatform</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="cadda774-f231-f7cc-c5c8-7d9e408c3f67">AlternateWin10Image</a></td><td>
Gets the alternate win10 image.
 (Overrides <a href="56095ed1-7829-fc71-a9be-b2e1cfeed58a">XenSolutionPlatform.AlternateWin10Image</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="85b5f124-8aef-6f48-9e47-e991d62f675f">AlternateWin7Image</a></td><td>
Gets the alternate win7 image.
 (Overrides <a href="92c0e447-40d6-fce0-c75f-f9bff2d18811">XenSolutionPlatform.AlternateWin7Image</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="1067f3fe-187e-42fd-7af7-17c1537dd679">AlternateWin8Image</a></td><td>
Gets the alternate win8 image.
 (Overrides <a href="f52282d2-feed-a761-d18f-70017fad2b05">XenSolutionPlatform.AlternateWin8Image</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="cb3c7143-76d2-7738-06d5-6ced708aede8">Applications</a></td><td>
Gets the applications.
 (Overrides <a href="2912e683-60b1-3dc2-8453-dc3c8d593c10">XenSolutionPlatform.Applications</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="be8e7a78-fd7c-ffd2-6ea4-610065568bde">AppV</a></td><td>
Gets a value indicating whether App-V is used.
 (Overrides <a href="f4044176-9f6f-068f-44ee-f2288923c4ac">XenSolutionPlatform.AppV</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d53d6fc5-5f98-0803-16f4-b6ec7cfe2bc0">Description</a></td><td>
Gets the description.
 (Overrides <a href="62f0689f-72ed-e4d5-53fb-572a9760c4ff">XenSolutionPlatform.Description</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="53c7683f-9438-b25b-71ff-e944b3ac25c9">DesktopHostedOperatingSystems</a></td><td>
Gets the used desktop hosted operating systems.
 (Overrides <a href="b6905200-4545-5b9d-6d66-5accccfc421a">XenSolutionPlatform.DesktopHostedOperatingSystems</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="7f25ff6c-fae8-40af-0b8b-ae1d7e793e8a">Error</a></td><td>
Gets a reason why platform is invalid.
 (Overrides <a href="5d1b696c-539d-9484-a2a5-fb391c6bbce7">XenSolutionPlatform.Error</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="b42f3ec8-84f4-d746-870d-a9e6ad1db510">Identifier</a></td><td>
Gets the identifier.
 (Overrides <a href="a61bcf91-5a3d-7270-7512-3f8f9870781d">XenSolutionPlatform.Identifier</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="19bfd931-32f5-b13e-1593-45cade6c5c20">Image</a></td><td>
Gets the image.
 (Overrides <a href="e55d2176-b8d8-7478-b08a-31c7daf7b696">XenSolutionPlatform.Image</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="e53eddee-bea6-22c7-cf31-5c212da10a79">IsTarget</a></td><td>
Gets a value indicating whether this instance is target platform.
 (Overrides <a href="ca38c7d6-b869-54be-7555-72a65b58a602">XenSolutionPlatform.IsTarget</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="4b2b41a2-0408-4ffc-8d39-2d06b089eaf6">IsValid</a></td><td>
Gets a value indicating whether this instance is valid.
 (Overrides <a href="108dc96e-1817-797a-e326-18605bd93cd2">XenSolutionPlatform.IsValid</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="f5aafcca-a45f-38d8-9abd-b6e1fabb163b">Name</a></td><td>
Gets the name.
 (Overrides <a href="cce38a45-73a6-4321-7bc5-7a2535240936">XenSolutionPlatform.Name</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="f59b6b69-f396-0e4f-5ad3-394edda87407">UseDesktopHostedModel</a></td><td>
Gets a value indicating whether to use desktop hosted model for deployment.
 (Overrides <a href="a4c816c1-38b4-f960-4f81-d33adf506cbb">XenSolutionPlatform.UseDesktopHostedModel</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="8648e0b6-a8a9-bafc-70a8-0d45106cce61">X64</a></td><td>
Gets a value indicating whether this <a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">XenSolutionPlatform</a> is 64-bit.
 (Overrides <a href="18d5a6e1-4da9-30c7-de8f-6582736b4c83">XenSolutionPlatform.X64</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="b770efc9-1bc7-12d0-cd04-4bf74fcc8170">Xen</a></td><td>
Gets a value indicating whether this <a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">XenSolutionPlatform</a> uses XenApp or XenDesktop.
 (Overrides <a href="8313efbd-aceb-53af-98b8-441d91df58ca">XenSolutionPlatform.Xen</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="aff33a38-2243-fbdd-5993-55adf027b1cc">XenVersion</a></td><td>
Gets the xen version for platform.
 (Overrides <a href="5b3c3788-7a1e-2251-ebcd-e1917f4fc612">XenSolutionPlatform.XenVersion</a>.)</td></tr></table>&nbsp;
<a href="#xenupgradesolutionplatform-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="4d5150fc-b4ac-cae4-8303-4921f82a5aed">CreatePlatform</a></td><td>
Creates the platform.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="c633bb26-c868-732e-c795-1f8c0ff7f7c8">Equals(Object)</a></td><td>
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="b35a5ae7-8982-0431-0689-69295ce8c598">Equals(XenSolutionPlatform)</a></td><td>
Indicates whether the current object is equal to another object of the same type.
 (Overrides <a href="217aedc3-69d7-b722-f5c9-6e78ab76bae2">XenSolutionPlatform.Equals(XenSolutionPlatform)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="fb1ef4e5-3ab8-d8eb-5c0d-eaf13aaeae70">Equals(XenUpgradeSolutionPlatform)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="dbb75692-f72c-5c7d-f716-0c85c6b60909">GetDefaultTargetPlatform</a></td><td>
Gets the default target platform.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="f505a21c-8552-1f37-6539-87e0e711d293">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="f2db3525-3f59-0e87-e573-8881fa2b0c60">OnPropertyChanged</a></td><td>
Called when property changed.
 (Inherited from <a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">XenSolutionPlatform</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="36c917b9-07ff-579c-b532-2f1b40908658">ToString</a></td><td>
Returns a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> that represents this instance.
 (Overrides <a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#xenupgradesolutionplatform-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="6ed34a79-8c7a-234f-6056-4cf4acfa2a4f">Deleted</a></td><td>
Raised when the solution is deleted.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="0c663d0d-3cdb-f99d-7e86-c52c24e103a9">PropertyChanged</a></td><td>
Occurs when a property value changes.
 (Inherited from <a href="0e04915f-6b1a-0016-6a11-cd519e55dcbe">XenSolutionPlatform</a>.)</td></tr></table>&nbsp;
<a href="#xenupgradesolutionplatform-class">Back to Top</a>

## See Also


#### Reference
<a href="2805b95f-a335-5d98-deaf-c0312b394eda">Citrix.SDK.AppDNA.Solutions.XenUpgrade Namespace</a><br />