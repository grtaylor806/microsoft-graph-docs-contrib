---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW VERSION OF THE SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$graphServiceClient->teams()->byTeamId('team-id')->channels()->byChannelId('channel-id')->messages()->byChatMessageId('chatMessage-id')->replies()->byChatMessageId('chatMessage-id1')->softDelete()->post()->wait();

```