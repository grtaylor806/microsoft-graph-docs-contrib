---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new Microsoft.Graph.Search.Query.QueryPostRequestBody
{
	Requests = new List<SearchRequest>
	{
		new SearchRequest
		{
			EntityTypes = new List<EntityType?>
			{
				EntityType.ExternalItem,
			},
			ContentSources = new List<string>
			{
				"/external/connections/connectionfriendlyname",
			},
			Query = new SearchQuery
			{
				QueryString = "contoso product",
			},
			From = 0,
			Size = 25,
			Fields = new List<string>
			{
				"title",
				"description",
			},
		},
	},
};
var result = await graphClient.Search.Query.PostAsync(requestBody);


```