---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)


result, err := graphClient.SitesById("site-id").TermStore().GroupsById("group-id").SetsById("set-id").TermsById("term-id").Get(context.Background(), nil)


```