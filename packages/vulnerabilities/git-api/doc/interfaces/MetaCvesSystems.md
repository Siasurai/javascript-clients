[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaCvesSystems

# Interface: MetaCvesSystems

Defined in: [api.ts:1672](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1672)

## Export

MetaCvesSystems

## Properties

### business\_risk\_id

> **business\_risk\_id**: `string` \| `null`

Defined in: [api.ts:1738](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1738)

Filter based on business risk IDs.

#### Memberof

MetaCvesSystems

***

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:1804](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1804)

CVEs without Errata feature flag

#### Memberof

MetaCvesSystems

***

### cvss\_from

> **cvss\_from**: `number` \| `null`

Defined in: [api.ts:1744](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1744)

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

#### Memberof

MetaCvesSystems

***

### cvss\_to

> **cvss\_to**: `number` \| `null`

Defined in: [api.ts:1750](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1750)

Filter based on cvss score, up to the value.

#### Memberof

MetaCvesSystems

***

### data\_format

> **data\_format**: `string`

Defined in: [api.ts:1726](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1726)

Format of the output data, either JSON (default) or CSV.

#### Memberof

MetaCvesSystems

***

### filter

> **filter**: `string` \| `null`

Defined in: [api.ts:1678](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1678)

Full text filter

#### Memberof

MetaCvesSystems

***

### first\_reported\_from

> **first\_reported\_from**: `string` \| `null`

Defined in: [api.ts:1792](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1792)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaCvesSystems

***

### first\_reported\_to

> **first\_reported\_to**: `string` \| `null`

Defined in: [api.ts:1798](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1798)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaCvesSystems

***

### impact

> **impact**: `string` \| `null`

Defined in: [api.ts:1768](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1768)

Filter based on impact IDs.

#### Memberof

MetaCvesSystems

***

### limit

> **limit**: `number`

Defined in: [api.ts:1684](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1684)

Maximum number of paginated results.

#### Memberof

MetaCvesSystems

***

### offset

> **offset**: `number`

Defined in: [api.ts:1690](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1690)

First record of paginated response.

#### Memberof

MetaCvesSystems

***

### opt\_out

> **opt\_out**: `boolean`

Defined in: [api.ts:1810](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1810)

If given system was opted out.

#### Memberof

MetaCvesSystems

***

### page

> **page**: `number`

Defined in: [api.ts:1696](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1696)

Page number of paginated response.

#### Memberof

MetaCvesSystems

***

### page\_size

> **page\_size**: `number`

Defined in: [api.ts:1702](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1702)

Number of records per page of paginated response.

#### Memberof

MetaCvesSystems

***

### pages

> **pages**: `number`

Defined in: [api.ts:1708](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1708)

Total number of pages of paginated response.

#### Memberof

MetaCvesSystems

***

### patch\_access

> **patch\_access**: `boolean` \| `null`

Defined in: [api.ts:1786](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1786)

If show_advisories=true shows access to patch service else null

#### Memberof

MetaCvesSystems

***

### permissions

> **permissions**: `string`[]

Defined in: [api.ts:1732](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1732)

Fetched permissions from RBAC for given user

#### Memberof

MetaCvesSystems

***

### public\_from

> **public\_from**: `string` \| `null`

Defined in: [api.ts:1756](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1756)

Filter CVEs based on their published date, starting from the date.

#### Memberof

MetaCvesSystems

***

### public\_to

> **public\_to**: `string` \| `null`

Defined in: [api.ts:1762](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1762)

Filter CVEs based on their published date, up to the date.

#### Memberof

MetaCvesSystems

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:1780](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1780)

Filter based on presence of security rule

#### Memberof

MetaCvesSystems

***

### sort

> **sort**: `string` \| `null`

Defined in: [api.ts:1714](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1714)

Sorting filter.

#### Memberof

MetaCvesSystems

***

### status\_id

> **status\_id**: `string` \| `null`

Defined in: [api.ts:1774](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1774)

Filer based on CVE status ID.

#### Memberof

MetaCvesSystems

***

### total\_items

> **total\_items**: `number`

Defined in: [api.ts:1720](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1720)

Total number of records.

#### Memberof

MetaCvesSystems
