---
-api-id: P:Windows.ApplicationModel.Package.Dependencies
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Collections.IVectorView<Windows.ApplicationModel.Package> Dependencies { get; }
-->

# Windows.ApplicationModel.Package.Dependencies

## -description
Gets the packages on which the current package depends.

## -property-value
The packages on which the current package depends.

## -remarks
> [!IMPORTANT]
> Although Package is supported in desktop apps, this member is supported only in Windows Store app. To access a package's dependencies from a desktop app, use [GetPackageInfo](http://msdn.microsoft.com/library/28f45b3b-a61f-44d3-b606-6966ad5866fa).

## -examples

## -see-also
[App package information sample](http://code.msdn.microsoft.com/windowsapps/Package-sample-46e239fa), [App package information sample (Windows 10)](http://go.microsoft.com/fwlink/p/?LinkId=620581)