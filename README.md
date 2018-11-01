# Pop Culture cmd
A repository filled with python-based command environments inspired by pop-culture. Send a pull request my way to add your own!

## New Shells Guide
### Files
The shell files you make should follow the `cmd.Cmd` python module's specification. You can make a case in your pull request as to why your different method might be better, and if it's a good enough argument, I might switch over to that. The main problem is just that I can't seem to find any other good packages for quickly and easily making python-based command environments.
### File Paths
The file path should be structured as follows: `(root)/universe/specification/(file)` where `(root)` is the root folder of the repository and `(file)` is the file you are adding to the repository. `universe` is the universe where the shell fits in, like "portal" or "star_wars". `specification` is any kind of distinguishing specification about your file. For instance, if you made an empire-themed shell inspired by Star Wars, the path would most likely be `(root)/star_wars/empire/(file)`.
### File Names
The file naming convention is relatively simple. It would be similar to the following: `universeabbr_specification_author.py`, where `universeabbr` is the name of the universe, abbreviated if appropriate and possible, `specification` is the same as above, and `author` is the username of the person that authored the shell.
### Functionality
I'm pretty serious about this stuff being good. If it doesn't quite fit with the theme or something like that, I may dismiss you. Now, there are some guidelines that I have that make for good theming:
 - Give a good startup sequence. Have a logo, or a message, some kind of delayed printout sequence that suggests files are being loaded into the non-existent system.
 - Add some interactive atmosphere. For Examle: if a user "logs in" with an account relevant to the universe, send a customized welcoming message.
 - Some of the shell should actually be functional in some way. It should actually be able to do *something*, even if it's not that much.
 - Document your commands. The `Cmd.cmd` module has built in support for help menus and docstrings. Make your shell easy to use by simply adding a sentence or two to each command function describing what it does.
   - If you want, you can add a page to the wiki once your shell is added for online documentation.
