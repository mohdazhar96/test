newhire
=======
newhire

Current chart version is `v0.1.0`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| current | bool | `false` |  |
| dockerregistry | string | `nil` |  |
| env.client | string | `nil` |  |
| env.confserver | string | `nil` |  |
| env.dashboard | string | `nil` |  |
| env.employee_management | string | `nil` |  |
| env.employee_newhire | string | `nil` |  |
| env.integration_management | string | `nil` |  |
| env.notification_management | string | `nil` |  |
| env.reference_mgmt | string | `nil` |  |
| env.reportsmgmt | string | `nil` |  |
| env.user_management | string | `nil` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.repository | string | `nil` |  |
| image.tag | string | `nil` |  |
| livenessProbe.httpGet.path | string | `"/healthz"` |  |
| livenessProbe.httpGet.port | int | `8806` |  |
| livenessProbe.initialDelaySeconds | int | `50` |  |
| livenessProbe.periodSeconds | int | `15` |  |
| nameOverride | string | `"newhire"` |  |
| readinessProbe.failureThreshold | int | `5` |  |
| readinessProbe.httpGet.path | string | `"/healthz"` |  |
| readinessProbe.httpGet.port | int | `8806` |  |
| readinessProbe.initialDelaySeconds | int | `40` |  |
| readinessProbe.periodSeconds | int | `15` |  |
| readinessProbe.timeoutSeconds | int | `2` |  |
| reason | string | `"unknown"` |  |
| replicaCount | int | `1` |  |
| tags.altdev | bool | `false` |  |
| tags.altqa | bool | `false` |  |
| tags.dev | bool | `false` |  |
| tags.perf | bool | `false` |  |
| tags.prod | bool | `false` |  |
| tags.qa | bool | `false` |  |
| tags.trng | bool | `false` |  |
| tags.uat | bool | `false` |  |
| telemetry.level | string | `"Error"` |  |
