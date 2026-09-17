[**@redhat-cloud-services/vulnerabilities-client**](../README.md)

***

[@redhat-cloud-services/vulnerabilities-client](../globals.md) / InsightsRule

# Interface: InsightsRule

Defined in: [api.ts:1089](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1089)

## Export

InsightsRule

## Properties

### associated\_cves

> **associated\_cves**: `string`[]

Defined in: [api.ts:1137](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1137)

List of CVEs associated with the rule.

#### Memberof

InsightsRule

***

### change\_risk

> **change\_risk**: `number` \| `null`

Defined in: [api.ts:1125](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1125)

Indicates how likely remediation can change environment on the remediatied system.

#### Memberof

InsightsRule

***

### description

> **description**: `string` \| `null`

Defined in: [api.ts:1101](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1101)

Description of the rule.

#### Memberof

InsightsRule

***

### kbase\_node\_id

> **kbase\_node\_id**: `number` \| `null`

Defined in: [api.ts:1131](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1131)

ID of associated Red Hat knowledgebase article.

#### Memberof

InsightsRule

***

### playbook\_count

> **playbook\_count**: `number` \| `null`

Defined in: [api.ts:1119](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1119)

Number of available Ansible playbooks for remediation/mitigation.

#### Memberof

InsightsRule

***

### publish\_date

> **publish\_date**: `string` \| `null`

Defined in: [api.ts:1155](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1155)

Date when the rule was published.

#### Memberof

InsightsRule

***

### reboot\_required

> **reboot\_required**: `boolean` \| `null`

Defined in: [api.ts:1113](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1113)

Indicator whter reboot is required to mitigate vulnerability.

#### Memberof

InsightsRule

***

### rule\_id

> **rule\_id**: `string`

Defined in: [api.ts:1095](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1095)

ID(s) of associated security rule(s).

#### Memberof

InsightsRule

***

### rule\_impact

> **rule\_impact**: `number` \| `null`

Defined in: [api.ts:1143](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1143)

Shows rules impact number from 1 to 4

#### Memberof

InsightsRule

***

### summary

> **summary**: `string` \| `null`

Defined in: [api.ts:1107](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1107)

Summary of the rule.

#### Memberof

InsightsRule

***

### systems\_affected?

> `optional` **systems\_affected?**: `number`

Defined in: [api.ts:1149](https://github.com/Siasurai/javascript-clients/blob/main/packages/vulnerabilities/git-api/api.ts#L1149)

Number of systems affected by the rule.

#### Memberof

InsightsRule
