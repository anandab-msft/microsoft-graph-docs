---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let administrativeUnit = await client.api('/directory/administrativeUnits/{id}')
	.get();

```