---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = User(
	account_enabled = True,
	display_name = "Adele Vance",
	mail_nickname = "AdeleV",
	user_principal_name = "AdeleV@contoso.onmicrosoft.com",
	password_profile = PasswordProfile(
		force_change_password_next_sign_in = True,
		password = "xWwvJ]6NMw+bWH-d",
	),
)

result = await graph_client.users.post(request_body = request_body)


```