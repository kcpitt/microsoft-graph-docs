---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)

requestBody := graphmodels.NewIdentityProviderBase()
displayName := "Apple"
requestBody.SetDisplayName(&displayName) 

result, err := graphClient.Identity().IdentityProvidersById("identityProviderBase-id").Patch(context.Background(), requestBody, nil)


```