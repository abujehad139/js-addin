This is a Add-In for Visual Studio for extended javascript support.
Here the link on [Visual Studio Gallery](http://visualstudiogallery.msdn.microsoft.com/288a2b0f-1357-47b4-8215-1134c36bdf30) site.
Please visit [discussion group](https://groups.google.com/forum/#!forum/js-addin) if you want to ask something or you have a great idea how to improve this addin.

<table cellpadding='0' border='0' cellspacing='0'>
<tr>
<td>
<br>
</td>
<td width='89%' align='right'>

</td>
</tr>
</table>

## Summary ##
> When you are editing a extremely large javascript files it's very useful to have some set of tools to improve the performance of development process and avoid possible bugs.
> To solve this problems I've created this add-in for Visual Studio.

> Supported versions of Visual Studio: 2008, 2010, 2012.

> Current version is 3.6. [Version History](VersionHistory.md)
> [Read more about 3.6 version](Version_3_6.md).

![http://js-addin.googlecode.com/svn/site/vs2010_errors_tasklist.png](http://js-addin.googlecode.com/svn/site/vs2010_errors_tasklist.png)

## Features ##
  * ![http://js-addin.googlecode.com/svn/site/hot.gif](http://js-addin.googlecode.com/svn/site/hot.gif) Support of VS2010 and VS2012 color themes. [Read more](VisualStudioThemesSupport.md).
  * ![http://js-addin.googlecode.com/svn/site/hot.gif](http://js-addin.googlecode.com/svn/site/hot.gif) Errors notification popup bar.
  * Tree of functions. This panel is used to quick navigation - on double click on the function name Visual Studio set a input focus to that function.
  * Comments are loaded and show on mouse over on function in tree. [Screenshot](http://code.google.com/p/js-addin/wiki/ListOfFunctions#Loading_comments)
  * Great support of Javascript syntax.
  * Runtime source support. Its very useful in debug mode. [Screenshot](http://code.google.com/p/js-addin/wiki/ListOfFunctions#Runtime_source_support)
  * Support of `<script></script>` blocks in non-js files (**`*`.html**, **`*`.aspx**, etc) [Screenshot](http://code.google.com/p/js-addin/wiki/ListOfFunctions#Inline_scripts_support)
  * Ignoring asp.net-specific tags (<%= %>) from source code to maintain valid javascript.
  * Marks. You can set mark to any function. This marks are saved when restarted Visual Studio and allows to remember some points in the large scripts. [Screenshot](http://code.google.com/p/js-addin/wiki/ListOfFunctions#Marks).
  * Find feature (supports hotkey). You can find your function by capital letters in its name - if you use camel naming. [Screenshot](http://code.google.com/p/js-addin/wiki/ListOfFunctions#Find_feature).
  * Show line numbers for functions in tree (optional).
  * Automatic track active function while working in text editor (optional).
  * Option for automatically Expand\Collapse all nodes in tree.
  * Show parameters in function chain. Usable for when anonymous function is attached by jQuery. [Screenshot](http://code.google.com/p/js-addin/wiki/ListOfFunctions#Show_parameters_in_function_chain)
  * Show javascript errors in your file.
  * Show //TODO: comments in tasklist section.
  * Option for hide anonymous functions.

## Planned improvements ##
> [Planned Improvements List](PlannedImprovements.md)