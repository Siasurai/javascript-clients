[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaAffectedSystemsAllOf

# Interface: MetaAffectedSystemsAllOf

Defined in: [api.ts:1387](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1387)

## Export

MetaAffectedSystemsAllOf

## Properties

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:1435](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1435)

CVEs without Errata feature flag

#### Memberof

MetaAffectedSystemsAllOf

***

### first\_reported\_from

> **first\_reported\_from**: `string` \| `null`

Defined in: [api.ts:1423](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1423)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaAffectedSystemsAllOf

***

### first\_reported\_to

> **first\_reported\_to**: `string` \| `null`

Defined in: [api.ts:1429](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1429)

Filter system-cve pairs based on first time of detection of CVE.

#### Memberof

MetaAffectedSystemsAllOf

***

### group\_ids

> **group\_ids**: `string` \| `null`

Defined in: [api.ts:1447](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1447)

ID of the inventory group.

#### Memberof

MetaAffectedSystemsAllOf

***

### group\_names

> **group\_names**: `string` \| `null`

Defined in: [api.ts:1441](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1441)

Name of the inventory group.

#### Memberof

MetaAffectedSystemsAllOf

***

### patch\_access

> **patch\_access**: `boolean` \| `null`

Defined in: [api.ts:1411](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1411)

If show_advisories=true shows access to patch service else null

#### Memberof

MetaAffectedSystemsAllOf

***

### rhel\_version

> **rhel\_version**: `string` \| `null`

Defined in: [api.ts:1417](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1417)

Filter base on system RHEL version.

#### Memberof

MetaAffectedSystemsAllOf

***

### rule\_key

> **rule\_key**: `string` \| `null`

Defined in: [api.ts:1399](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1399)

Filters security rules by its error key.

#### Memberof

MetaAffectedSystemsAllOf

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:1405](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1405)

Filter based on presence of security rule

#### Memberof

MetaAffectedSystemsAllOf

***

### status\_id

> **status\_id**: `string` \| `null`

Defined in: [api.ts:1393](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1393)

Filer based on CVE status ID.

#### Memberof

MetaAffectedSystemsAllOf
