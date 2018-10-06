# AwesomeSwiftSnippets
Collection of awesome Swift Snippets compiled with Swift 4

# What is need
Code completion and Fix‐It can both help you **speed up your development of Swift code**. 
Code snippets in the library go even further: They are snippets of code you can just drag into your own code. You can use a snippet as‐is, but many have tokens — highlighted areas that you can customize with your own variable names or other customizations.

When you drag snippets with tokens into your code, they almost always generate errors because you haven’t replaced the tokens yet. This is normal.
In addition to the built‐in library, you can create your own snippets according to your project needs and distribute along team members.

# Import
Xcode's all built-in code snippets exist at path in ~/Library/Developer/Xcode/UserData/CodeSnippets/ 
So you can just download this codesnippet folder and copy all it's files to same path and you done !

Don't forget to restart Xcode after copying this file, so changes can be get reflected.

Note:If you don't found the folder, create it. It is get created by Xcode when user adds his first custom snippet.

# Usage
I named all snippets using scheme *snippet...* . So when you start typing word snippet in Xcode editor all relevant snippet code will appear to choose from.


![Snippet Use](https://raw.githubusercontent.com/sagarmore62/AwesomeSwiftSnippets/master/assets/snippetUse.gif)


Or you can click on Snippet Library button to get all list of snippets in Xcode.
Note: In Xcode 10 Snippet Library button position changed to top toolbar as shown in below graphics. In Xcode 9 it was at bottom-right position at Utilities Panel.

![Snippet Use](https://raw.githubusercontent.com/sagarmore62/AwesomeSwiftSnippets/master/assets/snippetalert.gif)


# Create own custom snippet
In Xcode 10 you can go to Editor->Create Code Snippet. And you will get window for creating custom snippet.
For older Xcode versions, you can write custom snippet in editor area and drag it to Utilites panel's snippet library area.


![Snippet Use](https://raw.githubusercontent.com/sagarmore62/AwesomeSwiftSnippets/master/assets/createsnippet.gif)

If you want to add placeholder in snippet simply put it between <# and #> and it will be transformed in both editor and final snippet.

# Note
This code is written in swift 4.1 language with XCode 10.



