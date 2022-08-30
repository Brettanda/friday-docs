---
title: Config
description: The general configuration commands for Friday
---
# Config

The general configuration commands for Friday

## Botchannel

The channel where bot commands live.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!botchannel <channel>
	!botchannel clear 
	```

=== "Examples"
	```md
	!botchannel #botspam
	```

### Clear

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"

	```md
	!botchannel clear 
	```

## Disable

Disable a command

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!disable|disablecmd <command>
	!disable|disablecmd list 
	```

=== "Aliases"
	```md
	disablecmd
	```

=== "Examples"
	```md
	!disable ping
	!disablecmd ping last
	!disable "blacklist add" ping
	```

### List

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Lists all disabled commands.

=== "Usage"

	```md
	!disable list 
	```

## Enable

Enables the selected command(s).

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!enable <command>
	```

## Prefix

Sets the prefix for Fridays commands

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!prefix <new_prefix>
	```

=== "Examples"
	```md
	!prefix ?
	!prefix f!
	```

## Restrict

Restricts the selected command to the bot channel. Ignored with manage server permission.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!restrict <command>
	!restrict list 
	```

### List

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Lists the restricted commands.

=== "Usage"

	```md
	!restrict list 
	```

## Serverlanguage

Change the default language that I will speak in a server. Doesn't affect application commands

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!serverlanguage|serverlang|guildlang|guildlanguage 
	```

=== "Aliases"
	```md
	serverlang,guildlang,guildlanguage
	```

## Unrestrict

Unrestricts the selected command.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!unrestrict <command>
	```

## Updates

Recieve updates on new features and changes for Friday

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!updates <channel>
	```

## Userlanguage

Change the language that I will speak to you as a user. This doesn't affect application commands

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!userlanguage|userlang 
	```

=== "Aliases"
	```md
	userlang
	```
