[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / StatusIn

# Interface: StatusIn

Defined in: [api.ts:2303](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2303)

## Export

StatusIn

## Properties

### cve

> **cve**: [`CveOrList`](../type-aliases/CveOrList.md)

Defined in: [api.ts:2315](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2315)

#### Memberof

StatusIn

***

### inventory\_id?

> `optional` **inventory\_id?**: [`InventoryIdOrList`](../type-aliases/InventoryIdOrList.md)

Defined in: [api.ts:2309](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2309)

#### Memberof

StatusIn

***

### status\_id?

> `optional` **status\_id?**: `number`

Defined in: [api.ts:2321](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2321)

Status ID to be set, obtained by GET method. If not specified, global CVE status is set.

#### Memberof

StatusIn

***

### status\_text?

> `optional` **status\_text?**: `string` \| `null`

Defined in: [api.ts:2327](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2327)

Complementary text to the status.

#### Memberof

StatusIn
