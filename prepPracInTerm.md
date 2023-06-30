# Practice in Terminal

<https://ryanstutorials.net/linuxtutorial/>  

## The Command Line  

I didn't know that the first thing typed is a called a command and the rest after that are called arguments.  I didn't know bash stood for Bourne agaun shell.  I found it strange that the ways I open a terminal weren't listed in the opening a terminal section. (clicking on the app icon or opening from vscode)  Also I found it interesting that my prompt doesn't end in bash like it says it should in the article.  

## Basic Navigation  

I didn't know square brackets made items optional.  I didn't know -l provided a long listing, or that /etc listed directories contents.  I'm not sure how that's different than ls by itself. I didn't know cd ~ and cd by itself did the same thing.  

## More About Files  

I had forgotten that file extension names were ignored in linux.  I wasn't aware spaces could be used in file names.  I didn't know that a \ was called an escape character.  I also forgot that -a can be used to reveal all files. (including hidden ones)  

## Manual Pages  

Manual Pages are pretty much manuals for commands on your system.
'man (command to look up)' invokes the manual pages. To exit the manual pages press 'q' for quit.  
'man -k (search term)' does a keyword search. Use 'n' for next item found.  

## File Manipulation

Use mkdir [ options] (Directory)  
 -p tells mkdir to make parent directories as needed  
 -v makes mkdir tell us what it is doing  
'rmdir [ options] (Directory)' for removing  
  -supports v and p  
  -add -f for nonempty directories 'rm -r backups'  
Use touch to make a blank file 'touch [ options] (filename)'  
Use 'cp [ options] < source> < destination>' to copy a file or directory.  
Use 'mv [ options] < source> < destination>' to move a file or directory.  
  -Also Can be used for renaming (ex:'mv foo foo3')  

## Cheat Sheet

<https://ryanstutorials.net/linuxtutorial/cheatsheet.php>

I'll keep this handy, should be useful.  It phrases things and categorizes them (such as the wildcard section) in ways I'm not used to, although I've used some of the characters before.

- [Go to TOC](README.md)
