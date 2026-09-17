[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaCves

# Interface: MetaCves

Defined in: [api.ts:1454](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1454)

## Export

MetaCves

## Properties

### business\_risk\_id

> **business\_risk\_id**: `string` \| `null`

Defined in: [api.ts:1520](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1520)

Filter based on business risk IDs.

#### Memberof

MetaCves

***

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:1586](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1586)

CVEs without Errata feature flag

#### Memberof

MetaCves

***

### cvss\_from

> **cvss\_from**: `number` \| `null`

Defined in: [api.ts:1526](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1526)

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

#### Memberof

MetaCves

***

### cvss\_to

> **cvss\_to**: `number` \| `null`

Defined in: [api.ts:1532](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1532)

Filter based on cvss score, up to the value.

#### Memberof

MetaCves

***

### data\_format

> **data\_format**: `string`

Defined in: [api.ts:1508](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1508)

Format of the output data, either JSON (default) or CSV.

#### Memberof

MetaCves

***

### filter

> **filter**: `string` \| `null`

Defined in: [api.ts:1460](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1460)

Full text filter

#### Memberof

MetaCves

***

### first\_reported\_from

> **first\_reported\_from**: `string` \| `null`

Defined in: [api.ts:1574](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1574)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaCves

***

### first\_reported\_to

> **first\_reported\_to**: `string` \| `null`

Defined in: [api.ts:1580](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1580)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaCves

***

### impact

> **impact**: `string` \| `null`

Defined in: [api.ts:1550](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1550)

Filter based on impact IDs.

#### Memberof

MetaCves

***

### limit

> **limit**: `number`

Defined in: [api.ts:1466](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1466)

Maximum number of paginated results.

#### Memberof

MetaCves

***

### offset

> **offset**: `number`

Defined in: [api.ts:1472](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1472)

First record of paginated response.

#### Memberof

MetaCves

***

### page

> **page**: `number`

Defined in: [api.ts:1478](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1478)

Page number of paginated response.

#### Memberof

MetaCves

***

### page\_size

> **page\_size**: `number`

Defined in: [api.ts:1484](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1484)

Number of records per page of paginated response.

#### Memberof

MetaCves

***

### pages

> **pages**: `number`

Defined in: [api.ts:1490](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1490)

Total number of pages of paginated response.

#### Memberof

MetaCves

***

### patch\_access

> **patch\_access**: `boolean` \| `null`

Defined in: [api.ts:1568](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1568)

If show_advisories=true shows access to patch service else null

#### Memberof

MetaCves

***

### permissions

> **permissions**: `string`[]

Defined in: [api.ts:1514](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1514)

Fetched permissions from RBAC for given user

#### Memberof

MetaCves

***

### public\_from

> **public\_from**: `string` \| `null`

Defined in: [api.ts:1538](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1538)

Filter CVEs based on their published date, starting from the date.

#### Memberof

MetaCves

***

### public\_to

> **public\_to**: `string` \| `null`

Defined in: [api.ts:1544](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1544)

Filter CVEs based on their published date, up to the date.

#### Memberof

MetaCves

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:1562](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1562)

Filter based on presence of security rule

#### Memberof

MetaCves

***

### sort

> **sort**: `string` \| `null`

Defined in: [api.ts:1496](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1496)

Sorting filter.

#### Memberof

MetaCves

***

### status\_id

> **status\_id**: `string` \| `null`

Defined in: [api.ts:1556](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1556)

Filer based on CVE status ID.

#### Memberof

MetaCves

***

### total\_items

> **total\_items**: `number`

Defined in: [api.ts:1502](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1502)

Total number of records.

#### Memberof

MetaCves
