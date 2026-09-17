[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaCvesAllOf

# Interface: MetaCvesAllOf

Defined in: [api.ts:1593](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1593)

## Export

MetaCvesAllOf

## Properties

### business\_risk\_id

> **business\_risk\_id**: `string` \| `null`

Defined in: [api.ts:1599](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1599)

Filter based on business risk IDs.

#### Memberof

MetaCvesAllOf

***

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:1665](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1665)

CVEs without Errata feature flag

#### Memberof

MetaCvesAllOf

***

### cvss\_from

> **cvss\_from**: `number` \| `null`

Defined in: [api.ts:1605](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1605)

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

#### Memberof

MetaCvesAllOf

***

### cvss\_to

> **cvss\_to**: `number` \| `null`

Defined in: [api.ts:1611](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1611)

Filter based on cvss score, up to the value.

#### Memberof

MetaCvesAllOf

***

### first\_reported\_from

> **first\_reported\_from**: `string` \| `null`

Defined in: [api.ts:1653](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1653)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaCvesAllOf

***

### first\_reported\_to

> **first\_reported\_to**: `string` \| `null`

Defined in: [api.ts:1659](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1659)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaCvesAllOf

***

### impact

> **impact**: `string` \| `null`

Defined in: [api.ts:1629](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1629)

Filter based on impact IDs.

#### Memberof

MetaCvesAllOf

***

### patch\_access

> **patch\_access**: `boolean` \| `null`

Defined in: [api.ts:1647](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1647)

If show_advisories=true shows access to patch service else null

#### Memberof

MetaCvesAllOf

***

### public\_from

> **public\_from**: `string` \| `null`

Defined in: [api.ts:1617](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1617)

Filter CVEs based on their published date, starting from the date.

#### Memberof

MetaCvesAllOf

***

### public\_to

> **public\_to**: `string` \| `null`

Defined in: [api.ts:1623](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1623)

Filter CVEs based on their published date, up to the date.

#### Memberof

MetaCvesAllOf

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:1641](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1641)

Filter based on presence of security rule

#### Memberof

MetaCvesAllOf

***

### status\_id

> **status\_id**: `string` \| `null`

Defined in: [api.ts:1635](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1635)

Filer based on CVE status ID.

#### Memberof

MetaCvesAllOf
