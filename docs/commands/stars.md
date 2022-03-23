---
title: Stars
description: A starboard to upvote posts obviously.\nThere are two ways to make use of this feature, the first is via reactions, react to a message with ⭐ and the bot will automatically add (or remove) it to the starboard.\nThe second way is via Developer Mode. Enable it under Settings > Appearance > Developer Mode and then you get access to Copy ID and using the star/unstar commands.
---
# Stars

A starboard to upvote posts obviously.

There are two ways to make use of this feature, the first is
via reactions, react to a message with ⭐ and
the bot will automatically add (or remove) it to the starboard.

The second way is via Developer Mode. Enable it under Settings >
Appearance > Developer Mode and then you get access to Copy ID
and using the star/unstar commands.

## Star

Stars a message via message ID.

To star a message you should right click on the on a message and then
click "Copy ID". You must have Developer Mode enabled to get that
functionality.

It is recommended that you react to a message with ⭐ instead.

You can only star a message once.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!star <message>
	!star clean <stars>
	!star limit <stars>
	!star lock 
	!star migrate 
	!star random 
	!star show <message>
	!star stats <member>
	!star unlock 
	```

### Clean

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Cleans the starboard

This removes messages in the starboard that only have less
than or equal to the number of specified stars. This defaults to 1.

Note that this only checks the last 100 messages in the starboard.

This command requires the Manage Server permission.

=== "Usage"

	```md
	!star clean <stars>
	```

### Limit

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Sets the minimum number of stars required to show up.

When this limit is set, messages must have this number
or more to show up in the starboard channel.

You cannot have a negative number and the maximum
star limit you can set is 100.

Note that messages that previously did not meet the
limit but now do will still not show up in the starboard
until starred again.

You must have Manage Server permissions to use this.

=== "Usage"

	```md
	!star limit|threshold <stars>
	```

=== "Aliases"

	```md
	threshold
	```

### Lock

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Locks the starboard from being processed.

This is a moderation tool that allows you to temporarily
disable the starboard to aid in dealing with star spam.

When the starboard is locked, no new entries are added to
the starboard as the bot will no longer listen to reactions or
star/unstar commands.

To unlock the starboard, use the unlock subcommand.

To use this command you need Manage Server permission.

=== "Usage"

	```md
	!star lock 
	```

### Migrate

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Migrates the starboard to the newest version.

While doing this, the starboard is locked.

Note: This is an **incredibly expensive operation**.

It will take a very long time.

You must have Manage Server permissions to use this.

=== "Usage"

	```md
	!star migrate 
	```

### Random

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Shows a random starred message.

=== "Usage"

	```md
	!star random 
	```

### Show

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Shows a starred message via its ID.

To get the ID of a message you should right click on the
message and then click "Copy ID". You must have
Developer Mode enabled to get that functionality.

You can only use this command once per 10 seconds.

=== "Usage"

	```md
	!star show <message>
	```

### Stats

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Shows statistics on the starboard usage of the server or a member.

=== "Usage"

	```md
	!star stats <member>
	```

### Unlock

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Unlocks the starboard for re-processing.

To use this command you need Manage Server permission.

=== "Usage"

	```md
	!star unlock 
	```

## Starboard

Sets up the starboard for this server.

This creates a new channel with the specified name
and makes it into the server's "starboard". If no
name is passed in then it defaults to "starboard".

Choose wisely, this channel cannot be changed.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!starboard [name='starboard']
	!starboard info 
	```

=== "Examples"
	```md
	!starboard
	!starboard starboard
	```

### Info

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Shows meta information about the starboard.

=== "Usage"

	```md
	!starboard info 
	```

## Unstar

Unstars a message via message ID.

To unstar a message you should right click on the on a message and then
click "Copy ID". You must have Developer Mode enabled to get that
functionality.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!unstar <message>
	```
