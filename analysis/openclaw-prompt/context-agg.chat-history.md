Conversation info (untrusted metadata):

```json
{
  "message_id": "msg-12345",
  "message_id_full": "telegram:msg-12345-full",
  "reply_to_id": "msg-12340",
  "sender_id": "289522496",
  "conversation_label": "dev-team",
  "sender": "+1234567890",
  "group_subject": "OpenClaw Development",
  "group_channel": "#general",
  "group_space": "Engineering",
  "thread_label": "API discussion",
  "is_forum": true,
  "was_mentioned": true
}
```

Sender (untrusted metadata):

```json
{
  "label": "Wayne Low (+1234567890)",
  "name": "Wayne Low",
  "username": "waynelow",
  "tag": "Wayne Low#1234",
  "e164": "+1234567890"
}
```

Thread starter (untrusted, for context):

```json
{
  "body": "Let's discuss the new API endpoints"
}
```

Replied message (untrusted, for context):

```json
{
  "sender_label": "Alice Chen",
  "body": "Can you check the API status?"
}
```

Forwarded message context (untrusted metadata):

```json
{
  "from": "Bob Smith",
  "type": "user",
  "username": "bobsmith",
  "title": "Tech Lead",
  "signature": "Bob",
  "chat_type": "private",
  "date_ms": 1706000000000
}
```

Chat history since last reply (untrusted, for context):

```json
[
  {
    "sender": "Alice Chen",
    "timestamp_ms": 1706000060000,
    "body": "I noticed the /health endpoint is slow"
  },
  {
    "sender": "Bob Smith",
    "timestamp_ms": 1706000120000,
    "body": "Same here, latency is >2s"
  },
  {
    "sender": "Wayne Low",
    "timestamp_ms": 1706000180000,
    "body": "Let me investigate"
  }
]
```
