"NO2" v1.0 - Notepad++ for Oberon-2 development

This package is my personal assembly based on Notepad++ (free text editor) for
working with XDS Oberon-2.

Feature highlights:
- the assembly is portable, i.e. all the setings are stored in the
  installation folder, nothing is stored in the system registry or the
  "Application Data" folder, so you can run it from a flash drive;
- Function List shows the list of procedures in the current file sorted
  alphabetically. Double-click an entry to jump to the source position;
- Explorer displays the list of files, a folder tree and provides the standard
  Windows Explorer's context menu, including TortoiseCVS/SVN/GIT commands (for
  those who have it installed) for version management;
- NppExec allows one to execute console commands, preconfigured to highlight
  XC error messages (double click on the message opens the file/position of
  the error);
- QuickText plugin allows you to expand abbreviations to make full language
  constructs in a few keystrokes, e.g. type "p" and press Ctrl+Enter to
  replace "p" with a full PROCEDURE template with caret placed at the place to
  enter name the name for the new procedure. Press Ctrl+Enter again to move
  caret to the next predefined position in the template;
- Oberon2Lexer plugin provides support for syntax highlighting;
- Obide plugin supports:
  * code tooltips (e.g. parameter list for a procedure, value for a constant,
    type name for a variable = Ctrl+Alt+Space);
  * code navigation (jump to identifier declaration and back = Ctrl+9, Ctrl+0);
  * autocompletion - a popup list of fields and type-bound procedures
    respecting ancestry and visibility rules = Ctrl+Space
    (see plugins/doc/Obide.txt and "Plugins - Obide" in the main menu for the
    shortcuts);
- other plugins can, of course, be installed at will.


Component versions:
- Explorer v1.8.2;
- Function List v2.1;
- Notepad++ v5.6.8 Unicode;
- NppExec v0.3.2;
- Oberon2Lexer v0.3;
- Obide v2.2.1;
- Plugin Manager 0.9.3.1;
- QuickText v0.2.1;
- Scintilla v2.0.1.


Links:
NO2:
   GitHub project page: http://github.com/AlexIljin/NO2
Notepad++:
   Official page: http://notepad-plus.sourceforge.net/
   SourceForge project: https://sourceforge.net/projects/notepad-plus/
Notepad++ Plugins:
   SourceForge project: https://sourceforge.net/projects/npp-plugins/
Oberon Revival:
   Official page: http://oberonrevival.sourceforge.net/
   SourceForge project: http://sourceforge.net/projects/oberonrevival/
   Mailing list: oberonrevival-xds-usage@lists.sourceforge.net
Author:
   Alexander Iljin <AlexIljin@users.SourceForge.net>
