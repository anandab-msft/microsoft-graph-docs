---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let workbookOperation = await client.api('/me/drive/items/{drive-item-id}/workbook/operations/{operation-id}')
	.get();

```