---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let availableProviderTypes = await client.api('/identityProviders/availableProviderTypes')
	.get();

```