usermgmt-dev
============
usermgmt-dev

Current chart version is `v0.1.0`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| exports.data.current | bool | `true` |  |
| exports.data.env.client | string | `"http://client.backend-dev.svc.cluster.local:8802"` |  |
| exports.data.env.confserver | string | `"http://confserver.backend-dev.svc.cluster.local:4000"` |  |
| exports.data.env.dashboard | string | `"http://dashboard.backend-dev.svc.cluster.local:8808"` |  |
| exports.data.env.employee_management | string | `"http://empmgmt.backend-dev.svc.cluster.local:8803"` |  |
| exports.data.env.employee_newhire | string | `"http://newhire.backend-dev.svc.cluster.local:8806"` |  |
| exports.data.env.integration_management | string | `"http://intmgmt.backend-dev.svc.cluster.local:8810"` |  |
| exports.data.env.notification_management | string | `"http://notifymgmt.backend-dev.svc.cluster.local:8807"` |  |
| exports.data.env.reference_mgmt | string | `"http://refmgmt.backend-dev.svc.cluster.local:8804"` |  |
| exports.data.env.reportsmgmt | string | `"http://reportsmgmt.backend-dev.svc.cluster.local:8812"` |  |
| exports.data.env.user_management | string | `"http://usermgmt.backend-dev.svc.cluster.local:8801"` |  |
| exports.data.hosts | string | `"https://portaldev.mybbsi.com"` |  |
| exports.data.image.pullPolicy | string | `"Always"` |  |
| exports.data.ingress.class | string | `"nginx-dev"` |  |
| exports.data.reason | string | `"new dev deploy"` |  |
| exports.data.replicaCount | int | `1` |  |
| exports.data.resources.limits.cpu | string | `"1000m"` |  |
| exports.data.resources.limits.memory | string | `"3096Mi"` |  |
| exports.data.resources.requests.cpu | string | `"500m"` |  |
| exports.data.resources.requests.memory | string | `"1024Mi"` |  |
| exports.data.ssl_redirect | bool | `true` |  |
| exports.data.telemetry.level | string | `"Information"` |  |
