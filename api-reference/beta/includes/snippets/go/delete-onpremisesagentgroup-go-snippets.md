---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)


graphClient.OnPremisesPublishingProfilesById("onPremisesPublishingProfile-id").AgentGroupsById("onPremisesAgentGroup-id").Delete(context.Background(), nil)


```