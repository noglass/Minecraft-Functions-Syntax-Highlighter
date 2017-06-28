# Minecraft-Functions-Syntax-Highlighter
GTKSourceView Language File For .mcfunction File Syntax Highlighting

	Usage:
	
		Simply place the `mcfunc.lang` file directly into your
		`/usr/share/gtksourceview-3.0/language-specs/` directory.
		
		When you open a file with the `.mcfunction` extension it
		will automatically conform to the syntax highlighting
		defined in the language file.
		
		You can also create a new file and select "Minecraft
		Functions" from the language drop down box.
	
	Preview Sample Images:
	
		http://i.imgur.com/5cRzftA.png - Error highlighting
		http://i.imgur.com/aXBaBDC.png - Curly brace issue
		http://i.imgur.com/EuAWlV8.png - Default keywords
		http://i.imgur.com/Lf3cB7E.png - Pretty Colors
	
	Known problems:

		Curly braces embedded within curly braces are not
	*	respected with their natural opening and closing.
		Example:
			summon minecraft:ocelot ~ ~ ~ {Attributes:[{Base:1.0,Name:"generic.movementSpeed"},{Base:8.0,Name:"generic.followRange"}],CustomName:"Lightning McKitty",CustomNameVisible:1}
