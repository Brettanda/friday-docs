---
title: Reminder
description: Set reminders for yourself
---
# Reminder

Set reminders for yourself

## Reminder

Create a reminder for a certain time in the future.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!reminder|timer|remind <when> <message>
	!reminder|timer|remind clear 
	!reminder|timer|remind delete <id>
	!reminder|timer|remind list 
	```

=== "Aliases"
	```md
	timer,remind
	```

=== "Examples"
	```md
	!reminder 20m go buy food
	!timer do something in 20m
	!remind jan 1st happy new years
	```

### Clear

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Delete all your reminders.

=== "Usage"

	```md
	!reminder clear 
	```

### Delete

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Delete a reminder.

=== "Usage"

	```md
	!reminder delete|remove|cancel <id>
	```

=== "Aliases"

	```md
	remove,cancel
	```

=== "Examples"

	```md
	!reminder delete 1
	!timer remove 200
	```

### List

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

List all reminders.

=== "Usage"

	```md
	!reminder list 
	```

## Timezone

Commands related to managing timezone info.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!timezone 
	!timezone clear 
	!timezone set <timezone>
	```

### Clear

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Clears your timezone.

=== "Usage"

	```md
	!timezone clear 
	```

### Set

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Sets your timezone for all related commands.

=== "Usage"

	```md
	!timezone set <timezone>
	```
