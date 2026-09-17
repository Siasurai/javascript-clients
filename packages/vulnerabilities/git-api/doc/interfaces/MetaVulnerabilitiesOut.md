[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaVulnerabilitiesOut

# Interface: MetaVulnerabilitiesOut

Defined in: [api.ts:1941](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1941)

## Export

MetaVulnerabilitiesOut

## Properties

### advisory\_available

> **advisory\_available**: `string` \| `null`

Defined in: [api.ts:2079](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2079)

Shows whether a CVE has available advisory or not

#### Memberof

MetaVulnerabilitiesOut

***

### affecting

> **affecting**: `string` \| `null`

Defined in: [api.ts:2007](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2007)

Description of CVE showing preferences

#### Memberof

MetaVulnerabilitiesOut

***

### business\_risk\_id

> **business\_risk\_id**: `string` \| `null`

Defined in: [api.ts:2013](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2013)

Filter based on business risk IDs.

#### Memberof

MetaVulnerabilitiesOut

***

### cache\_used

> **cache\_used**: `boolean`

Defined in: [api.ts:2085](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2085)

Flag if cached data was used to produce the response.

#### Memberof

MetaVulnerabilitiesOut

***

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:2073](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2073)

CVEs without Errata feature flag

#### Memberof

MetaVulnerabilitiesOut

***

### cvss\_from

> **cvss\_from**: `number` \| `null`

Defined in: [api.ts:2019](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2019)

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

#### Memberof

MetaVulnerabilitiesOut

***

### cvss\_to

> **cvss\_to**: `number` \| `null`

Defined in: [api.ts:2025](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2025)

Filter based on cvss score, up to the value.

#### Memberof

MetaVulnerabilitiesOut

***

### data\_format

> **data\_format**: `string`

Defined in: [api.ts:1995](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1995)

Format of the output data, either JSON (default) or CSV.

#### Memberof

MetaVulnerabilitiesOut

***

### filter

> **filter**: `string` \| `null`

Defined in: [api.ts:1947](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1947)

Full text filter

#### Memberof

MetaVulnerabilitiesOut

***

### impact

> **impact**: `string` \| `null`

Defined in: [api.ts:2043](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2043)

Filter based on impact IDs.

#### Memberof

MetaVulnerabilitiesOut

***

### limit

> **limit**: `number`

Defined in: [api.ts:1953](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1953)

Maximum number of paginated results.

#### Memberof

MetaVulnerabilitiesOut

***

### offset

> **offset**: `number`

Defined in: [api.ts:1959](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1959)

First record of paginated response.

#### Memberof

MetaVulnerabilitiesOut

***

### page

> **page**: `number`

Defined in: [api.ts:1965](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1965)

Page number of paginated response.

#### Memberof

MetaVulnerabilitiesOut

***

### page\_size

> **page\_size**: `number`

Defined in: [api.ts:1971](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1971)

Number of records per page of paginated response.

#### Memberof

MetaVulnerabilitiesOut

***

### pages

> **pages**: `number`

Defined in: [api.ts:1977](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1977)

Total number of pages of paginated response.

#### Memberof

MetaVulnerabilitiesOut

***

### permissions

> **permissions**: `string`[]

Defined in: [api.ts:2001](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2001)

Fetched permissions from RBAC for given user

#### Memberof

MetaVulnerabilitiesOut

***

### public\_from

> **public\_from**: `string` \| `null`

Defined in: [api.ts:2031](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2031)

Filter CVEs based on their published date, starting from the date.

#### Memberof

MetaVulnerabilitiesOut

***

### public\_to

> **public\_to**: `string` \| `null`

Defined in: [api.ts:2037](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2037)

Filter CVEs based on their published date, up to the date.

#### Memberof

MetaVulnerabilitiesOut

***

### rhel\_version

> **rhel\_version**: `string` \| `null`

Defined in: [api.ts:2061](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2061)

Filter base on system RHEL version.

#### Memberof

MetaVulnerabilitiesOut

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:2067](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2067)

Filter based on presence of security rule

#### Memberof

MetaVulnerabilitiesOut

***

### sort

> **sort**: `string` \| `null`

Defined in: [api.ts:1983](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1983)

Sorting filter.

#### Memberof

MetaVulnerabilitiesOut

***

### system\_count?

> `optional` **system\_count?**: `number`

Defined in: [api.ts:2055](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2055)

Total number of systems managed by vulnerability application.

#### Memberof

MetaVulnerabilitiesOut

***

### system\_count\_per\_type?

> `optional` **system\_count\_per\_type?**: [`MetaVulnerabilitiesOutAllOfSystemCountPerType`](MetaVulnerabilitiesOutAllOfSystemCountPerType.md)

Defined in: [api.ts:2049](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2049)

#### Memberof

MetaVulnerabilitiesOut

***

### total\_items

> **total\_items**: `number`

Defined in: [api.ts:1989](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1989)

Total number of records.

#### Memberof

MetaVulnerabilitiesOut
