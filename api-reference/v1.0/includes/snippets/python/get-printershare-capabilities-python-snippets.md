---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = PrinterShareRequestBuilder.PrinterShareRequestBuilderGetQueryParameters(
		select = ["id","displayName","capabilities"],
)

request_configuration = PrinterShareRequestBuilder.PrinterShareRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.print.shares.by_share_id('printerShare-id').get(request_configuration = request_configuration)


```