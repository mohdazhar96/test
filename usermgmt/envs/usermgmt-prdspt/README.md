usermgmt-perf
=============
usermgmt-perf

Current chart version is `v0.1.0`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| exports.data.current | bool | `true` |  |
| exports.data.env.client | string | `"http://client.backend-perf.svc.cluster.local:8802"` |  |
| exports.data.env.confserver | string | `"http://confserver.backend-perf.svc.cluster.local:4000"` |  |
| exports.data.env.dashboard | string | `"http://dashboard.backend-perf.svc.cluster.local:8808"` |  |
| exports.data.env.employee_management | string | `"http://empmgmt.backend-perf.svc.cluster.local:8803"` |  |
| exports.data.env.employee_newhire | string | `"http://newhire.backend-perf.svc.cluster.local:8806"` |  |
| exports.data.env.integration_management | string | `"http://intmgmt.backend-perf.svc.cluster.local:8810"` |  |
| exports.data.env.notification_management | string | `"http://notifymgmt.backend-perf.svc.cluster.local:8807"` |  |
| exports.data.env.reference_mgmt | string | `"http://refmgmt.backend-perf.svc.cluster.local:8804"` |  |
| exports.data.env.reportsmgmt | string | `"http://reportsmgmt.backend-perf.svc.cluster.local:8812"` |  |
| exports.data.env.user_management | string | `"http://usermgmt.backend-perf.svc.cluster.local:8801"` |  |
| exports.data.hosts | string | `"https://portalperf.mybbsi.com"` |  |
| exports.data.image.pullPolicy | string | `"Always"` |  |
| exports.data.ingress.class | string | `"nginx-perf"` |  |
| exports.data.reason | string | `"new perf deploy"` |  |
| exports.data.replicaCount | int | `1` |  |
| exports.data.resources.limits.cpu | string | `"1000m"` |  |
| exports.data.resources.limits.memory | string | `"3096Mi"` |  |
| exports.data.resources.requests.cpu | string | `"500m"` |  |
| exports.data.resources.requests.memory | string | `"1024Mi"` |  |
| exports.data.ssl_redirect | bool | `true` |  |
| exports.data.telemetry.level | string | `"Information"` |  |
| nameOverride | string | `"usermgmt"` |  |
