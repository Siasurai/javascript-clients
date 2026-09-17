[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / Dashboard

# Interface: Dashboard

Defined in: [api.ts:531](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L531)

## Export

Dashboard

## Properties

### cves\_by\_severity

> **cves\_by\_severity**: [`DashboardCvesBySeverity`](DashboardCvesBySeverity.md)

Defined in: [api.ts:543](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L543)

#### Memberof

Dashboard

***

### cves\_total

> **cves\_total**: `number`

Defined in: [api.ts:537](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L537)

Number of unique CVEs discovered on the managed systems.

#### Memberof

Dashboard

***

### exploited\_cves\_count

> **exploited\_cves\_count**: `number`

Defined in: [api.ts:573](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L573)

unique number of CVEs having known exploit affecting at least one system

#### Memberof

Dashboard

***

### recent\_cves

> **recent\_cves**: [`ExecutiveReportRecentCves`](ExecutiveReportRecentCves.md)

Defined in: [api.ts:549](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L549)

#### Memberof

Dashboard

***

### recent\_rules

> **recent\_rules**: [`DashboardRecentRules`](DashboardRecentRules.md)[]

Defined in: [api.ts:555](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L555)

List of recently (14 days) released security rules.

#### Memberof

Dashboard

***

### rules\_cves\_total

> **rules\_cves\_total**: `number`

Defined in: [api.ts:561](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L561)

Total number of CVEs with associated security rules affecting given account.

#### Memberof

Dashboard

***

### system\_count

> **system\_count**: `number`

Defined in: [api.ts:567](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L567)

Total systems registered to Vulnerability service (with applied filtering).

#### Memberof

Dashboard
