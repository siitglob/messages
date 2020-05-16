# messages

Add a new message type format:

Create a new file with the key of the message. `message_key` for instance Love Message - `love_message`. Then use the format below to construct a message type.

```json
{
  "label": "Message label",
  "key": "message_key",
  "messages": [
  "list of messages seperated by double quotes and comma"
  ]
}  
```

Add a new message:

```
"messages": [
  "list of messages seperated by double quotes and comma",
  "another message seperated by double quotes and comma",
  "another one"
]

```

# Rules

1. Ensure you don't use unknown or any special character
2. Dont add comma to the last message in message list
3. Ensure you are using the right and valid json rules.
