---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



getVirtualAppointmentJoinWebUrl(), err := graphClient.Me().OnlineMeetings().ByOnlineMeetingId("onlineMeeting-id").GetVirtualAppointmentJoinWebUrl().Get(context.Background(), nil)


```