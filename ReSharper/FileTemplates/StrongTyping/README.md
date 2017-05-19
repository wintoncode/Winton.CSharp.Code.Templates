# Strong typing file templates for ReSharper

Here file templates can be found for:

* A strong type wrapping a `string`
* A strong type wrapping a value type
* A comparable strong type wrapping a `string`
* A comparable strong type wrapping a value type

The "comparable" types differ from the non-comparable types in that they implement
`IComparable<>` and `IComparable` as well as `IEquatable<>`.

## Installation

The `strong_types.DotSettings` template file needs to be imported into ReSharper.
This can be done from the ReSharper Templates Explorer found in Visual Studio via
__ReSharper -> Tools -> Templates Explorer__.
Navigate to the __File Templates__ tab in the explorer, click on the "Import..." icon and select the
`strong_types.DotSettings` file.
The templates will appear in the "Winton" category.