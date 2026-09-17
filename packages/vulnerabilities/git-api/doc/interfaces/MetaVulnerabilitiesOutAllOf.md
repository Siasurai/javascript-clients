[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / MetaVulnerabilitiesOutAllOf

# Interface: MetaVulnerabilitiesOutAllOf

Defined in: [api.ts:2092](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2092)

## Export

MetaVulnerabilitiesOutAllOf

## Properties

### advisory\_available

> **advisory\_available**: `string` \| `null`

Defined in: [api.ts:2170](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2170)

Shows whether a CVE has available advisory or not

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### affecting

> **affecting**: `string` \| `null`

Defined in: [api.ts:2098](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2098)

Description of CVE showing preferences

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### business\_risk\_id

> **business\_risk\_id**: `string` \| `null`

Defined in: [api.ts:2104](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2104)

Filter based on business risk IDs.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### cache\_used

> **cache\_used**: `boolean`

Defined in: [api.ts:2176](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2176)

Flag if cached data was used to produce the response.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### cves\_without\_errata

> **cves\_without\_errata**: `boolean` \| `null`

Defined in: [api.ts:2164](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2164)

CVEs without Errata feature flag

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### cvss\_from

> **cvss\_from**: `number` \| `null`

Defined in: [api.ts:2110](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2110)

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### cvss\_to

> **cvss\_to**: `number` \| `null`

Defined in: [api.ts:2116](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2116)

Filter based on cvss score, up to the value.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### impact

> **impact**: `string` \| `null`

Defined in: [api.ts:2134](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2134)

Filter based on impact IDs.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### public\_from

> **public\_from**: `string` \| `null`

Defined in: [api.ts:2122](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2122)

Filter CVEs based on their published date, starting from the date.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### public\_to

> **public\_to**: `string` \| `null`

Defined in: [api.ts:2128](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2128)

Filter CVEs based on their published date, up to the date.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### rhel\_version

> **rhel\_version**: `string` \| `null`

Defined in: [api.ts:2152](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2152)

Filter base on system RHEL version.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### rule\_presence

> **rule\_presence**: `string` \| `null`

Defined in: [api.ts:2158](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2158)

Filter based on presence of security rule

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### system\_count?

> `optional` **system\_count?**: `number`

Defined in: [api.ts:2146](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2146)

Total number of systems managed by vulnerability application.

#### Memberof

MetaVulnerabilitiesOutAllOf

***

### system\_count\_per\_type?

> `optional` **system\_count\_per\_type?**: [`MetaVulnerabilitiesOutAllOfSystemCountPerType`](MetaVulnerabilitiesOutAllOfSystemCountPerType.md)

Defined in: [api.ts:2140](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L2140)

#### Memberof

MetaVulnerabilitiesOutAllOf
