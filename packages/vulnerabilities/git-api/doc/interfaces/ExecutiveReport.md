[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / ExecutiveReport

# Interface: ExecutiveReport

Defined in: [api.ts:767](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L767)

## Export

ExecutiveReport

## Properties

### cves\_by\_severity

> **cves\_by\_severity**: [`ExecutiveReportCvesBySeverity`](ExecutiveReportCvesBySeverity.md)

Defined in: [api.ts:791](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L791)

#### Memberof

ExecutiveReport

***

### cves\_total

> **cves\_total**: `number`

Defined in: [api.ts:785](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L785)

Number of unique CVEs discovered on the managed systems.

#### Memberof

ExecutiveReport

***

### meta?

> `optional` **meta?**: [`MetaPermissions`](MetaPermissions.md)

Defined in: [api.ts:827](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L827)

#### Memberof

ExecutiveReport

***

### recent\_cves

> **recent\_cves**: [`ExecutiveReportRecentCves`](ExecutiveReportRecentCves.md)

Defined in: [api.ts:797](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L797)

#### Memberof

ExecutiveReport

***

### rules\_by\_severity

> **rules\_by\_severity**: [`ExecutiveReportRulesBySeverity`](ExecutiveReportRulesBySeverity.md)

Defined in: [api.ts:803](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L803)

#### Memberof

ExecutiveReport

***

### rules\_total

> **rules\_total**: `number`

Defined in: [api.ts:809](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L809)

Number of unique CVEs discovered on the managed systems.

#### Memberof

ExecutiveReport

***

### system\_count

> **system\_count**: `number`

Defined in: [api.ts:779](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L779)

Total number of systems managed by vulnerability application.

#### Memberof

ExecutiveReport

***

### system\_count\_per\_type?

> `optional` **system\_count\_per\_type?**: [`MetaVulnerabilitiesOutAllOfSystemCountPerType`](MetaVulnerabilitiesOutAllOfSystemCountPerType.md)

Defined in: [api.ts:773](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L773)

#### Memberof

ExecutiveReport

***

### top\_cves?

> `optional` **top\_cves?**: [`ExecutiveReportTopCves`](ExecutiveReportTopCves.md)[]

Defined in: [api.ts:815](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L815)

#### Memberof

ExecutiveReport

***

### top\_rules?

> `optional` **top\_rules?**: [`ExecutiveReportTopRules`](ExecutiveReportTopRules.md)[]

Defined in: [api.ts:821](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L821)

#### Memberof

ExecutiveReport
