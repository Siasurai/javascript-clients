[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / SystemDetailsOutData

# Interface: SystemDetailsOutData

Defined in: [api.ts:2536](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2536)

## Export

SystemDetailsOutData

## Properties

### host\_type

> **host\_type**: [`SystemDetailsOutDataHostTypeEnum`](../enumerations/SystemDetailsOutDataHostTypeEnum.md)

Defined in: [api.ts:2596](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2596)

Type of the host

#### Memberof

SystemDetailsOutData

***

### last\_evaluation

> **last\_evaluation**: `string` \| `null`

Defined in: [api.ts:2542](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2542)

Date of last evaluation.

#### Memberof

SystemDetailsOutData

***

### last\_upload

> **last\_upload**: `string` \| `null`

Defined in: [api.ts:2560](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2560)

Date of the latest upload of archive.

#### Memberof

SystemDetailsOutData

***

### opt\_out

> **opt\_out**: `boolean`

Defined in: [api.ts:2554](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2554)

System opt out status.

#### Memberof

SystemDetailsOutData

***

### os

> **os**: `string`

Defined in: [api.ts:2578](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2578)

Operating system.

#### Memberof

SystemDetailsOutData

***

### rhsm\_lock

> **rhsm\_lock**: `string` \| `null`

Defined in: [api.ts:2584](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2584)

System is locked to following RHSM version.

#### Memberof

SystemDetailsOutData

***

### rules\_evaluation

> **rules\_evaluation**: `string` \| `null`

Defined in: [api.ts:2548](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2548)

Date of last security rules evaluation.

#### Memberof

SystemDetailsOutData

***

### stale?

> `optional` **stale?**: `boolean`

Defined in: [api.ts:2566](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2566)

System stale status.

#### Memberof

SystemDetailsOutData

***

### tags

> **tags**: [`SystemDetailsOutDataTags`](SystemDetailsOutDataTags.md)[]

Defined in: [api.ts:2590](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2590)

#### Memberof

SystemDetailsOutData

***

### updated?

> `optional` **updated?**: `string` \| `null`

Defined in: [api.ts:2572](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2572)

Date of the lastest upload of archive taken from Inventory syndicated data.

#### Memberof

SystemDetailsOutData
