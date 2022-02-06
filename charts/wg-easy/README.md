# wg-easy

![Version: v0.0.1](https://img.shields.io/badge/Version-v0.0.1-informational?style=flat-square) ![AppVersion: 5](https://img.shields.io/badge/AppVersion-5-informational?style=flat-square)

A Wireguard VPN Access Server

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| additionalEnv | list | `[]` |  |
| affinity | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"weejewel/wg-easy"` |  |
| imagePullSecrets | list | `[]` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts | string | `nil` |  |
| ingress.tls | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| persistence.accessModes[0] | string | `"ReadWriteOnce"` |  |
| persistence.annotations | object | `{}` |  |
| persistence.enabled | bool | `false` |  |
| persistence.size | string | `"100Mi"` |  |
| persistence.subPath | string | `""` |  |
| replicas | int | `1` |  |
| resources | object | `{}` |  |
| strategy | object | `{}` |  |
| tolerations | list | `[]` |  |
| web.config.password | string | `"xDNvbQcF83wHnwyE6f9Wq"` |  |
| web.service.type | string | `"ClusterIP"` |  |
| wireguard.config.hostname | string | `""` |  |
| wireguard.service.type | string | `"ClusterIP"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)