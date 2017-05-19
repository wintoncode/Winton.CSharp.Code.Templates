# Strong typing code snippets for Visual Studio Code

Here code snippets can be found for:

* A strong type wrapping a `string` [short-cut: __strongstr__]
* A strong type wrapping a value type [short-cut: __strongval__]
* A comparable strong type wrapping a `string` [short-cut: __cmpstrongstr__]
* A comparable strong type wrapping a value type [short-cut: __cmpstrongval__]

The "comparable" types differ from the non-comparable types in that they implement
`IComparable<>` and `IComparable` as well as `IEquatable<>`.

By default the name for the type generated will be the name of the file.
Unfortunately, there is currently no means of removing the extension so you'll need to remove the `.cs` manually.
Once [this vscode issue](https://github.com/Microsoft/vscode/issues/6920) has been resolved and released,
this behaviour will be corrected.

## Installation

In Visual Studio Code go to __File -> Preferences -> User Snippets__ and select __C#__ from the list of languages.
This will open `csharp.json` for editing.
Next paste the contents of `strong_types.json` into that file and save it.
You should now be able to access the code snippets in a C# file via the short-cuts named above.
