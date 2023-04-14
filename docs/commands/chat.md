---
title: Chat
description: Chat with Friday, say something on Friday's behalf, and more with the chat commands.
---
# Chat

Chat with Friday, say something on Friday's behalf, and more with the chat commands.

## Chat

Chat with Friday, powered by ChatGPT and get a response.

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!chat <message>
	!chat info 
	!chat reset 
	```

### Info

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Displays information about the current conversation.

=== "Usage"

	```md
	!chat info 
	```

### Reset

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Resets Friday's chat history. Helps if Friday is repeating messages

=== "Usage"

	```md
	!chat reset 
	```

## Chatchannel

Set the current channel so that I will always try to respond with something

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!chatchannel <channel>
	!chatchannel clear 
	!chatchannel list 
	!chatchannel persona <channel>
	!chatchannel remove <channel>
	!chatchannel webhook <channel> <enable>
	```

=== "Examples"
	```md
	!chatchannel #channel
	```

### Clear

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Clear the current chat channel

=== "Usage"

	```md
	!chatchannel clear 
	```

### List

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Lists the channels that Friday will always try to respond with something

=== "Usage"

	```md
	!chatchannel list 
	```

### Persona

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Change Friday's persona for a chat channel

=== "Usage"

	```md
	!chatchannel persona <channel>
	```

### Remove

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Removes a chat channel

=== "Usage"

	```md
	!chatchannel remove <channel>
	```

### Webhook

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

Toggles webhook chatting with Friday in the current chat channel

=== "Usage"

	```md
	!chatchannel webhook <channel> <enable>
	```

=== "Examples"

	```md
	!chatchannel webhook #chatbot 1
	!chatchannel webhook #chatchannel false
	!chatchannel webhook #chatchannel true
	!chatchannel webhook #chatbot 0
	```

## Reset

Resets Friday's chat history. Helps if Friday is repeating messages

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!reset 
	```

## Say

Make Friday say what ever you want

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!say|repeat <content>
	```

=== "Aliases"
	```md
	repeat
	```

## Silentsay

??? missing "Does not have a slash command to match"
	Learn more about [slash commands](/#slash-commands)

=== "Usage"
	```md
	!silentsay|saysilent <content>
	```

=== "Aliases"
	```md
	saysilent
	```
