---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new PinnedMessagesRequestBuilderGetRequestConfiguration();
$queryParameters = PinnedMessagesRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->expand = ["message"];
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->chats()->byChatId('chat-id')->pinnedMessages()->get($requestConfiguration);


```