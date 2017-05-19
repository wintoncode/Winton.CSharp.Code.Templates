# Strong typing live templates for ReSharper

Here live templates can be found for:

* A strong type wrapping a `string` [short-cut: __strongstr__]
* A strong type wrapping a value type [short-cut: __strongval__]
* A comparable strong type wrapping a `string` [short-cut: __cmpstrongstr__]
* A comparable strong type wrapping a value type [short-cut: __cmpstrongval__]

The "comparable" types differ from the non-comparable types in that they implement
`IComparable<>` and `IComparable` as well as `IEquatable<>`.

## Installation

The `strong_types.DotSettings` template file needs to imported into ReSharper.
This can be done from the ReSharper Templates Explorer found in Visual Studio via
__ReSharper -> Tools -> Templates Explorer__.
Navigate to the __Live Templates__ tab in the explorer, click on the "Import..." icon and select the
`strong_types.DotSettings` file.
The templates will appear in the "Winton" category.
You should now be able to access the code snippets in a C# file via the short-cuts named above.