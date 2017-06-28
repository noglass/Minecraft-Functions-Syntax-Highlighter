# Minecraft-Functions-Syntax-Highlighter
GTKSourceView Language File For .mcfunction File Syntax Highlighting

	Known problems:

		Curly braces embedded within curly braces are not
	*	respected with their natural opening and closing.
		Example:
			summon minecraft:ocelot ~ ~ ~ {Attributes:[{Base:1.0,Name:"generic.movementSpeed"},{Base:8.0,Name:"generic.followRange"}],CustomName:"Lightning McKitty",CustomNameVisible:1}
