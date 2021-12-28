usermgmt-altdev
===============
usermgmt-altdev

Current chart version is `v0.1.0`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| exports.data.current | bool | `true` |  |
| exports.data.env.client | string | `"http://client.backend-altdev.svc.cluster.local:8802"` |  |
| exports.data.env.confserver | string | `"http://confserver.backend-altdev.svc.cluster.local:4000"` |  |
| exports.data.env.dashboard | string | `"http://dashboard.backend-altdev.svc.cluster.local:8808"` |  |
| exports.data.env.employee_management | string | `"http://empmgmt.backend-altdev.svc.cluster.local:8803"` |  |
| exports.data.env.employee_newhire | string | `"http://newhire.backend-altdev.svc.cluster.local:8806"` |  |
| exports.data.env.integration_management | string | `"http://intmgmt.backend-altdev.svc.cluster.local:8810"` |  |
| exports.data.env.notification_management | string | `"http://notifymgmt.backend-altdev.svc.cluster.local:8807"` |  |
| exports.data.env.reference_mgmt | string | `"http://refmgmt.backend-altdev.svc.cluster.local:8804"` |  |
| exports.data.env.reportsmgmt | string | `"http://reportsmgmt.backend-altdev.svc.cluster.local:8812"` |  |
| exports.data.env.user_management | string | `"http://usermgmt.backend-altdev.svc.cluster.local:8801"` |  |
| exports.data.hosts | string | `"http://dev.mybbsi.com"` |  |
| exports.data.image.pullPolicy | string | `"Always"` |  |
| exports.data.ingress.class | string | `"nginx-altdev"` |  |
| exports.data.reason | string | `"new altdev deploy"` |  |
| exports.data.replicaCount | int | `1` |  |
| exports.data.resources.limits.cpu | string | `"1000m"` |  |
| exports.data.resources.limits.memory | string | `"3096Mi"` |  |
| exports.data.resources.requests.cpu | string | `"500m"` |  |
| exports.data.resources.requests.memory | string | `"1024Mi"` |  |
| exports.data.ssl_redirect | bool | `true` |  |
| exports.data.telemetry.level | string | `"Information"` |  |
