---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = ChatMessage(
	body = ItemBody(
		content_type = BodyType.Html,
		content = "<emoji alt=\"😶‍🌫️\"></emoji>",
	),
)

result = await graph_client.chats.by_chat_id('chat-id').messages.post(request_body = request_body)


```