# MonitorClient

> see https://aka.ms/autorest

This is the AutoRest configuration file for MonitorClient.

---

## Getting Started

To build the SDK for MonitorClient, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`

---

## Configuration

### Basic Information

There are the global settings for the Azure Monitor Control Service (AMCS) extension.
``` yaml $(AMCS)
tag: package-2019-11-01-preview-only
```

These are the global settings for the MonitorClient API.

``` yaml
title: MonitorClient
description: Monitor Management Client
openapi-type: arm
tag: package-2019-06
```

### Tag: package-2020-05-preview

These settings apply only when `--tag=package-2020-05-preview` is specified on the command line.

```yaml $(tag) == 'package-2020-05-preview'
input-file:
- Microsoft.Insights/preview/2020-05-01-preview/scheduledQueryRule_API.json
```

### Tag: package-2020-01-01-preview-only

These settings apply only when `--tag=package-2020-01-01-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2020-01-01-preview-only'
input-file:
- Microsoft.Insights/preview/2020-01-01-preview/managementGroupDiagnosticSettings_API.json
```

### Tag: package-2020-03

These settings apply only when `--tag=package-2020-03` is specified on the command line.

```yaml $(tag) == 'package-2020-03'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/subscriptionDiagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2019-06-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2019-03-01/metricBaselines_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
- Microsoft.Insights/preview/2018-11-27-preview/vmInsightsOnboarding_API.json
- Microsoft.Insights/preview/2019-10-17-preview/privateLinkScopes_API.json
```

### Tag: package-2019-11

These settings apply only when `--tag=package-2019-11` is specified on the command line.

```yaml $(tag) == 'package-2019-11'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/subscriptionDiagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2019-06-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2019-03-01/metricBaselines_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
- Microsoft.Insights/preview/2018-11-27-preview/vmInsightsOnboarding_API.json
- Microsoft.Insights/preview/2019-10-17-preview/privateLinkScopes_API.json
```

### Tag: package-2019-10-17-preview-only

These settings apply only when `--tag=package-2019-10-17-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2019-10-17-preview-only'
input-file:
- Microsoft.Insights/preview/2019-10-17-preview/privateLinkScopes_API.json
```

### Tag: package-2019-06

These settings apply only when `--tag=package-2019-06` is specified on the command line.

```yaml $(tag) == 'package-2019-06'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2019-06-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2019-03-01/metricBaselines_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
- Microsoft.Insights/preview/2018-11-27-preview/vmInsightsOnboarding_API.json
```

### Tag: package-2019-03

These settings apply only when `--tag=package-2019-03` is specified on the command line.

```yaml $(tag) == 'package-2019-03'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2019-03-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2019-03-01/metricBaselines_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
- Microsoft.Insights/preview/2018-11-27-preview/vmInsightsOnboarding_API.json
```

### Tag: package-2018-11-preview

These settings apply only when `--tag=package-2018-11-preview` is specified on the command line.

```yaml $(tag) == 'package-2018-11-preview'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2018-09-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
- Microsoft.Insights/preview/2018-11-27-preview/vmInsightsOnboarding_API.json
```

### Tag: package-2018-09

These settings apply only when `--tag=package-2018-09` is specified on the command line.

``` yaml $(tag) == 'package-2018-09'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2018-09-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
```

### Tag: package-2018-03

These settings apply only when `--tag=package-2018-03` is specified on the command line.

``` yaml $(tag) == 'package-2018-03'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2018-03-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
```

### Tag: package-2018-02-preview

These settings apply only when `--tag=package-2018-02-preview` is specified on the command line.

``` yaml $(tag) == 'package-2018-02-preview'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2017-04-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
```

### Tag: package-2017-12

These settings apply only when `--tag=package-2017-12` is specified on the command line.

``` yaml $(tag) == 'package-2017-12'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2017-04-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/preview/2017-05-01-preview/metricDefinitions_API.json
- Microsoft.Insights/preview/2017-05-01-preview/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
```

### Tag: package-2017-09

These settings apply only when `--tag=package-2017-09` is specified on the command line.

``` yaml $(tag) == 'package-2017-09'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2018-09-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
- Microsoft.Insights/preview/2017-05-01-preview/metricDefinitions_API.json
- Microsoft.Insights/preview/2017-05-01-preview/metrics_API.json
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
```

### Tag: package-2017-08

These settings apply only when `--tag=package-2017-08` is specified on the command line.

``` yaml $(tag) == 'package-2017-08'
input-file:
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2017-04-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
```

### Tag: package-2019-11-01-preview-only

These settings apply only when `--tag=package-2019-11-01-preview-only` is specified on the command line.

``` yaml $(tag) == 'package-2019-11-01-preview-only'
input-file:
  - Microsoft.Insights/preview/2019-11-01-preview/dataCollectionRuleAssociations_API.json
  - Microsoft.Insights/preview/2019-11-01-preview/dataCollectionRules_API.json
```

### Tag: package-2019-06-01-only

These settings apply only when `--tag=package-2019-06-01-only` is specified on the command line.

```yaml $(tag) == 'package-2019-06-01-only'
input-file:
- Microsoft.Insights/stable/2019-06-01/actionGroups_API.json
```


### Tag: package-2019-03-01-only

These settings apply only when `--tag=package-2019-03-01-only` is specified on the command line.

```yaml $(tag) == 'package-2019-03-01-only'
input-file:
- Microsoft.Insights/stable/2019-03-01/actionGroups_API.json
- Microsoft.Insights/stable/2019-03-01/metricBaselines_API.json
```


### Tag: package-2018-11-27-preview-only

These settings apply only when `--tag=package-2018-11-27-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2018-11-27-preview-only'
input-file:
- Microsoft.Insights/preview/2018-11-27-preview/vmInsightsOnboarding_API.json
```


### Tag: package-2018-09-01-only

These settings apply only when `--tag=package-2018-09-01-only` is specified on the command line.

```yaml $(tag) == 'package-2018-09-01-only'
input-file:
- Microsoft.Insights/stable/2018-09-01/actionGroups_API.json
- Microsoft.Insights/stable/2018-09-01/baseline_API.json
- Microsoft.Insights/stable/2018-09-01/calculateBaseline_API.json
```


### Tag: package-2018-06-01-preview-only

These settings apply only when `--tag=package-2018-06-01-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2018-06-01-preview-only'
input-file:
- Microsoft.Insights/preview/2018-06-01-preview/guestDiagnosticSettingsAssociation_API.json
- Microsoft.Insights/preview/2018-06-01-preview/guestDiagnosticSettings_API.json
```


### Tag: package-2018-04-16-only

These settings apply only when `--tag=package-2018-04-16-only` is specified on the command line.

```yaml $(tag) == 'package-2018-04-16-only'
input-file:
- Microsoft.Insights/stable/2018-04-16/scheduledQueryRule_API.json
```


### Tag: package-2018-03-01-only

These settings apply only when `--tag=package-2018-03-01-only` is specified on the command line.

```yaml $(tag) == 'package-2018-03-01-only'
input-file:
- Microsoft.Insights/stable/2018-03-01/actionGroups_API.json
- Microsoft.Insights/stable/2018-03-01/metricAlert_API.json
```


### Tag: package-2018-01-01-only

These settings apply only when `--tag=package-2018-01-01-only` is specified on the command line.

```yaml $(tag) == 'package-2018-01-01-only'
input-file:
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
```


### Tag: package-2017-12-01-preview-only

These settings apply only when `--tag=package-2017-12-01-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2017-12-01-preview-only'
input-file:
- Microsoft.Insights/preview/2017-12-01-preview/metricNamespaces_API.json
```


### Tag: package-2017-11-01-preview-only

These settings apply only when `--tag=package-2017-11-01-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2017-11-01-preview-only'
input-file:
- Microsoft.Insights/preview/2017-11-01-preview/baseline_API.json
- Microsoft.Insights/preview/2017-11-01-preview/calculateBaseline_API.json
```


### Tag: package-2017-05-01-preview-only

These settings apply only when `--tag=package-2017-05-01-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2017-05-01-preview-only'
input-file:
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/metricDefinitions_API.json
- Microsoft.Insights/preview/2017-05-01-preview/metrics_API.json
- Microsoft.Insights/preview/2017-05-01-preview/subscriptionDiagnosticsSettings_API.json 
```


### Tag: package-2017-04-01-only

These settings apply only when `--tag=package-2017-04-01-only` is specified on the command line.

```yaml $(tag) == 'package-2017-04-01-only'
input-file:
- Microsoft.Insights/stable/2017-04-01/actionGroups_API.json
- Microsoft.Insights/stable/2017-04-01/activityLogAlerts_API.json
```


### Tag: package-2017-03-01-preview-only

These settings apply only when `--tag=package-2017-03-01-preview-only` is specified on the command line.

```yaml $(tag) == 'package-2017-03-01-preview-only'
input-file:
- Microsoft.Insights/preview/2017-03-01-preview/activityLogAlerts_API.json
```


### Tag: package-2016-09-01-only

These settings apply only when `--tag=package-2016-09-01-only` is specified on the command line.

```yaml $(tag) == 'package-2016-09-01-only'
input-file:
- Microsoft.Insights/stable/2016-09-01/metrics_API.json
- Microsoft.Insights/stable/2016-09-01/serviceDiagnosticsSettings_API.json
```


### Tag: package-2016-03-01-only

These settings apply only when `--tag=package-2016-03-01-only` is specified on the command line.

```yaml $(tag) == 'package-2016-03-01-only'
input-file:
- Microsoft.Insights/stable/2016-03-01/alertRulesIncidents_API.json
- Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- Microsoft.Insights/stable/2016-03-01/logProfiles_API.json
- Microsoft.Insights/stable/2016-03-01/metricDefinitions_API.json
```


### Tag: package-2015-07-01-only

These settings apply only when `--tag=package-2015-07-01-only` is specified on the command line.

```yaml $(tag) == 'package-2015-07-01-only'
input-file:
- Microsoft.Insights/stable/2015-07-01/serviceDiagnosticsSettings_API.json
```


### Tag: package-2015-04-01-only

These settings apply only when `--tag=package-2015-04-01-only` is specified on the command line.

```yaml $(tag) == 'package-2015-04-01-only'
input-file:
- Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- Microsoft.Insights/stable/2015-04-01/autoscale_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
- Microsoft.Insights/stable/2015-04-01/tenantActivityLogs_API.json
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-net
  - repo: azure-sdk-for-python
    after_scripts:
      - python ./scripts/multiapi_init_gen.py azure-mgmt-monitor
  - repo: azure-sdk-for-python-track2
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-js
  - repo: azure-sdk-for-node
  - repo: azure-sdk-for-ruby
    after_scripts:
      - bundle install && rake arm:regen_all_profiles['azure_mgmt_monitor']
  - repo: azure-resource-manager-schemas
    after_scripts:
      - node sdkauto_afterscript.js monitor/resource-manager
```

## Python

See configuration in [readme.python.md](./readme.python.md)

## Go

See configuration in [readme.go.md](./readme.go.md)

## Java

These settings apply only when `--java` is specified on the command line.
Please also specify `--azure-libraries-for-java-folder=<path to the root directory of your azure-libraries-for-java clone>`.

``` yaml $(java)
azure-arm: true
fluent: true
namespace: com.microsoft.azure.management.monitor
license-header: MICROSOFT_MIT_NO_CODEGEN
payload-flattening-threshold: 1
output-folder: $(azure-libraries-for-java-folder)/azure-mgmt-monitor
```

# Validation

## Suppression

``` yaml
directive:
  - suppress: R3016  # DefinitionsPropertiesNamesCamelCase (to suppress the error due to odata.type)
    reason: The feature (polymorphic types) is in the process of deprecation and fixing this will require changes in the backend.
  - suppress: OperationsAPIImplementation
    from: dataCollectionRules_API.json
    where: $.paths
    reason: 'Operations API is defined in a separate swagger spec for Microsoft.Insights namespace (https://github.com/Azure/azure-rest-api-specs/blob/master/specification/monitor/resource-manager/Microsoft.Insights/stable/2015-04-01/operations_API.json)'
  - suppress: OperationsAPIImplementation
    from: dataCollectionRuleAssociations_API.json
    where: $.paths
    reason: 'Operations API is defined in a separate swagger spec for Microsoft.Insights namespace (https://github.com/Azure/azure-rest-api-specs/blob/master/specification/monitor/resource-manager/Microsoft.Insights/stable/2015-04-01/operations_API.json)'
  - suppress: R4007
    from: metricBaselines_API.json
    reason: 'Updating the error response to the new format would be a breaking change.'
```

### Tag: profile-hybrid-2019-03-01

These settings apply only when `--tag=profile-hybrid-2019-03-01` is specified on the command line.
Creating this tag to pick proper resources from the hybrid profile.

``` yaml $(tag) == 'profile-hybrid-2019-03-01'
input-file:
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
```

### Tag: profile-hybrid-2020-09-01

These settings apply only when `--tag=profile-hybrid-2020-09-01` is specified on the command line.
Creating this tag to pick proper resources from the hybrid profile.

``` yaml $(tag) == 'profile-hybrid-2020-09-01'
input-file:
- Microsoft.Insights/stable/2018-01-01/metricDefinitions_API.json
- Microsoft.Insights/stable/2018-01-01/metrics_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettings_API.json
- Microsoft.Insights/preview/2017-05-01-preview/diagnosticsSettingsCategories_API.json
- Microsoft.Insights/stable/2015-04-01/eventCategories_API.json
- Microsoft.Insights/stable/2015-04-01/operations_API.json
```

## AzureResourceSchema

See configuration in [readme.azureresourceschema.md](./readme.azureresourceschema.md)

