# xkb Symbols Reference

**Warning: If you have a configuration file wih a syntax error in your symbols folder, your system will refuse to boot.**

On the other hand, `systemctl restart keyboard-setup.service` didn't work on my vm.

This a cheatsheatsheet for editing xkb files. The symbols listed here are those that I need and use.
I made it as a little help for me to port [Dvorak by Nizo](https://github.com/theNizo/DvorakByNizo-German) to Linux.
if you want to list more characters, feel free to send me a list and I'll add them.
Just in case, no guarantee that it's correct, but if something should be changed, let me know.

Please Note that this text is formatted to support markdown view. Viewing this as a raw file might be confusing.

| Character | Name | Dead Key Name |
|-|-|-|
| ^ | circumflex | dead_circumflex |
| ° | degree | dead_degree |
| ! | exclam | |
| " | quotedbl | |
| § | section | |
| $ | dollar | |
| % | percent | |
| & | ampersand | |
| / | slash | |
| ( | parenleft | |
| ) | parenright | |
| = | equal | |
| ² | twosuperior | |
| ³ | threesuperior | |
| { | braceleft | |
| } | braceright | |
| \[ | bracketleft | |
| \] | bracketright | |
| ? | question | |
| \ | backslash | |
| ´ | acute | dead_acute |
| \` | grave | dead_grave |
| \+ | plus | |
| \* | asterisk | |
| ~ | asciitilde | |
| # | numbersign | |
| ' | apostrophe | |
| > | greater | |
| < | less | |
| \| | bar | |
| ¦ | brokenbar | |
| , | comma | |
| ; | semicolon | |
| . | period | |
| : | colon | |
| \- | minus | |
| _ | underscore | |
| @ | at | |
| € | EuroSign | |
| µ | mu | |

~~When you use include, you don't actually override the keys, but the symbols. If a symbol is not overridden, it will shine through (e.g you only replace normal and shift, but not AltGr/Right Alt). To get rid of those, override them with "NoSymbol"~~

When you have to assign a character on Level 5, but nothing on the Alt Groups, fill them with "NoSymbol". If (in this case) there is a character in the Alt Group in the layout yours is based on, it will "shine through". It will still be on your layout. (Haven't figured out how to override them yet.)

## Special Keys (name is self explanatory)

* Up
* Down
* Left
* Right
* BackSpace
* Delete
* Return
* Undo
* Redo
* Tab
* Menu (assumed)
* Escape
* Home
* End

## NumBlock ("keypad_keys")

| Character | Name |
|-|-|
| 1 | KP_1 |
| 2 | KP_2 |
| 3 | KP_3 |
| 4 | KP_4 |
| 5 | KP_5 |
| 6 | KP_6 |
| 7 | KP_7 |
| 8 | KP_8 |
| 9 | KP_9 |
| 0 | KP_0 |

## German characters

| Character | Name |
|-|-|
| ü | udiaeresis |
| ä | adiaeresis |
| ö | odiaeresis |
| Ü | Udiaeresis |
| Ä | Adiaeresis |
| Ö | Odiaeresis |
| ß | ssharp |
