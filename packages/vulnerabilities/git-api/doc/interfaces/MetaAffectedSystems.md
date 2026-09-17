[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaAffectedSystems

# Interface: MetaAffectedSystems

Defined in: [api.ts:1260](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1260)

## Export

MetaAffectedSystems

## Properties

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:1368](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1368)

CVEs without Errata feature flag

#### Memberof

MetaAffectedSystems

***

### data\_format

> **data\_format**: `string`

Defined in: [api.ts:1314](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1314)

Format of the output data, either JSON (default) or CSV.

#### Memberof

MetaAffectedSystems

***

### filter

> **filter**: `string` \| `null`

Defined in: [api.ts:1266](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1266)

Full text filter

#### Memberof

MetaAffectedSystems

***

### first\_reported\_from

> **first\_reported\_from**: `string` \| `null`

Defined in: [api.ts:1356](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1356)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaAffectedSystems

***

### first\_reported\_to

> **first\_reported\_to**: `string` \| `null`

Defined in: [api.ts:1362](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1362)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaAffectedSystems

***

### group\_ids

> **group\_ids**: `string` \| `null`

Defined in: [api.ts:1380](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1380)

ID of the inventory group.

#### Memberof

MetaAffectedSystems

***

### group\_names

> **group\_names**: `string` \| `null`

Defined in: [api.ts:1374](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1374)

Name of the inventory group.

#### Memberof

MetaAffectedSystems

***

### limit

> **limit**: `number`

Defined in: [api.ts:1272](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1272)

Maximum number of paginated results.

#### Memberof

MetaAffectedSystems

***

### offset

> **offset**: `number`

Defined in: [api.ts:1278](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1278)

First record of paginated response.

#### Memberof

MetaAffectedSystems

***

### page

> **page**: `number`

Defined in: [api.ts:1284](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1284)

Page number of paginated response.

#### Memberof

MetaAffectedSystems

***

### page\_size

> **page\_size**: `number`

Defined in: [api.ts:1290](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1290)

Number of records per page of paginated response.

#### Memberof

MetaAffectedSystems

***

### pages

> **pages**: `number`

Defined in: [api.ts:1296](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1296)

Total number of pages of paginated response.

#### Memberof

MetaAffectedSystems

***

### patch\_access

> **patch\_access**: `boolean` \| `null`

Defined in: [api.ts:1344](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1344)

If show_advisories=true shows access to patch service else null

#### Memberof

MetaAffectedSystems

***

### permissions

> **permissions**: `string`[]

Defined in: [api.ts:1320](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1320)

Fetched permissions from RBAC for given user

#### Memberof

MetaAffectedSystems

***

### rhel\_version

> **rhel\_version**: `string` \| `null`

Defined in: [api.ts:1350](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1350)

Filter base on system RHEL version.

#### Memberof

MetaAffectedSystems

***

### rule\_key

> **rule\_key**: `string` \| `null`

Defined in: [api.ts:1332](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1332)

Filters security rules by its error key.

#### Memberof

MetaAffectedSystems

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:1338](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1338)

Filter based on presence of security rule

#### Memberof

MetaAffectedSystems

***

### sort

> **sort**: `string` \| `null`

Defined in: [api.ts:1302](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1302)

Sorting filter.

#### Memberof

MetaAffectedSystems

***

### status\_id

> **status\_id**: `string` \| `null`

Defined in: [api.ts:1326](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1326)

Filer based on CVE status ID.

#### Memberof

MetaAffectedSystems

***

### total\_items

> **total\_items**: `number`

Defined in: [api.ts:1308](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1308)

Total number of records.

#### Memberof

MetaAffectedSystems
