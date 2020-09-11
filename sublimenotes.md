Tools > Command Pallete, type install package controler
install SublimeLinter
install TrailingSpaces
main > preferences > keybindings:

[
	{ "keys": ["ctrl+shift+b"], "command": "insert_snippet", "args": {"contents": "require 'pry'; binding.pry"}},
	{ "keys": ["ctrl+shift+t"], "command": "delete_trailing_spaces" }
]

