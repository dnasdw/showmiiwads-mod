**showmiiwads-mod** is a mod of the original **ShowMiiWads by Leathl**. Goal is to provide some tools for sneek/uneek.

This mod is based on ShowMiiWads v1.5.

Changes :

- Remove needs of common-key.bin (use libmiisharp instead)

- Major change in extract nand function :
  * Execute nand extraction function on a separate thread;
  * Add ability to choose extract directory;
  * Add progress information (progress bar);
  * Better exception handling (extraction will continue even if a file couldn't be extracted)
  * Fix problem with location of keys.bin. This file must be on the same folder than Bootmii dump file !
- Add a form to build a nand "from scratch" :
  * Choose a system menu version, and required stuff will be download (nus) and install to the chosen folder. System Menu 4.2 and 4.3 (E/U/J) are available.
  * You can use you wii serial number to generate a setting.txt file. If not used, a default setting.txt will be generate.
- Add new "view" : **ShowMiiWiiGames**. Purpose is to provide some tools to decrypt wii game for sneek.
  * Add view (list view)
  * Add method to list games on a folder (recursively) with WIT : set Option-> Set Wii Game Backup Path
  * Support all kind of wii game format : .ISO, .WBFS, .CISO, etc. (all format supported by WIT ;))
  * Drag/Drop support for file/folder;
  * Context menu to add file/folder, convert and remove game;
  * Progress bar and ETA available;

More info/question here : http://www.wiiu-info.fr/