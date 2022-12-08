Resharper version 2022.3
Visual Studio Community 2022 version 17.4.2

To reproduce the issue, follow these steps:
1. Turn the ReSharper option "Automatically run cleanup when saving a file" on
2. Open the .cs file and press "ctrl + s" to save the file
3. ReSharper will now get stuck into a loop, and constantly save the file without stopping