# Strong typing code snippets for Visual Studio

Here code snippets can be found for:

* A strong type wrapping a `string` [short-cut: __strongstr__]
* A strong type wrapping a value type [short-cut: __strongval__]
* A comparable strong type wrapping a `string` [short-cut: __cmpstrongstr__]
* A comparable strong type wrapping a value type [short-cut: __cmpstrongval__]

The "comparable" types differ from the non-comparable types in that they implement
`IComparable<>` and `IComparable` as well as `IEquatable<>`.

## Installation

In Visual Studio go to __Tools -> Code Snippets Manager__, select __CSharp__ from the list of languages
in the drop-down at the top and select a location from the pane below.
Now click __Import...__ and navigate to the *.snippet files and click __Open__.
You should now be able to access the code snippets in a C# file via the short-cuts named above.
