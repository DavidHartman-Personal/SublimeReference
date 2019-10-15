# Sublime Macros
Macro files are JSON files with the extension .sublime-macro. Sublime Text ships with a few macros providing core functionality, such as line and word deletion.

## Commands
[Sublime Macros Commands]:Documentation for commands used in macros can be found in the Unofficial documentation site.

## Record/Save Macro
To start recording a macro, press Ctrl+q and subsequently execute the desired steps one by one. When you’re done, press Ctrl+q again to stop the macro recorder. Your new macro won’t be saved to a file, but kept in the macro buffer instead. Now you will be able to run the recorded macro by pressing Ctrl+Shift+q, or save it to a file by selecting Tools | Save macro…

## Key Binding for Macros
Macro files can be bound to key combinations by passing the macro file path to the run_macro_file command like so:
`{"keys": ["super+alt+l"], "command": "run_macro_file", "args": {"file": "res://Packages/User/Example.sublime-macro"}}`

## References/Resources
[Sublime Macros Unofficial Documentation - Macros]: Documentation on Sublime Macros

[Sublime Macros Unofficial Documentation - Macros]: http://docs.sublimetext.info/en/latest/extensibility/macros.html
[Sublime Macros Commands]: http://docs.sublimetext.info/en/latest/reference/commands.html
