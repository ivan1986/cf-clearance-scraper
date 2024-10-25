# CF clearance scraper helm chart

## Configuration

The following tables lists the configurable parameters of the nginx-share chart and their default values.

| Parameter                      | Description                         | Default                         |
|--------------------------------|-------------------------------------|---------------------------------|
| `images.container.repository`  | Image repository                    | `ivan1986/cf-clearance-scraper` |
| `images.container.tag`         | Image tag. Possible values listed   | `latest`                        |
| `images.pullPolicy`            | Image pull policy                   | `IfNotPresent`                  |
| `browserLimit`                 | Limin of run browsers               | `2`                             |
| `nodeSelector`                 | Node labels for pod assignment      | ``                              |
| `resources`                    | CPU/Memory resource requests/limits | `{}`                            |

Read through the [values.yaml](values.yaml) file. It has several commented out suggested values.
