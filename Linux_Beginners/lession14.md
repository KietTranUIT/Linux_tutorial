# Lession 14

<h3> Filtering Input </h3>

The grep command is a text filter that will search input and return lines which contain a match to a given pattern.

<span> Syntax: <br> <code> grep [options] pattern [file] </code> </span>

<h3> Regular Expressions </h3>

Regular expressions have two common forms: basic and extended. Most commands that use regular expressions can interpret basic regular expressions. However, extended regular expressions are not available for all commands and a command option is typically required for them to work correctly.

The following table summarizes basic regular expression characters:

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/86aa90e0-10c1-42cc-a262-9f6100823354">

The following table summarizes the extended regular expressions, which must be used with either the egrep command or the    -E option with the grep command:

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/bfd7773b-2261-4a3d-bdd3-3bb659bd8456">

<h3> Basic Pattern </h3>

<h3> Anchor characters </h3>

Anchor characters are one of the ways regular expressions can be used to narrow down search results. 

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/a43841d0-5d59-45db-a66d-10b201b5f735">

<h3> Match a Single Character With . </h3>

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/b9409fbe-9c0d-4cf7-863c-b93c1c360cb1">

<h3> Match a Single Character With [] </h3>

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/e870f4f9-0976-4184-a8f6-8fc27022e4df">

<h3> Match a Repeated Character Or Patterns With * </h3>

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/957cc5de-9426-4db3-a022-ad2fd58af543">

<h3> Standard Input </h3>

If a file name is not given, the grep command will read from standard input, which normally comes from the keyboard with input provided by the user who runs the command. This provides an interactive experience with grep where the user types in the input and grep filters as it goes. Feel free to try it out, just press Ctrl-D when you're ready to return to the prompt.