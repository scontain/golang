# Shared Tags

As the upstream `golang` images, we maintain shared tags. These shared tage always point to the container images that has the highest patch or minor level. This is easier to visualize using the following table:

| Simple Tag | Shared Tags |
| --- | --- |
| 1.25.3-trixie | 1.25.3, 1.25, 1, latest |
| 1.25.3-bookworm |  |
| 1.25.3-alpine3.22 | 1.25-alpine3.22, 1-alpine3.22, alpine3.22, 1.25.3-alpine, 1.25-alpine, 1-alpine, alpine |
| 1.25.3-alpine3.21 | 1.25-alpine3.21, 1-alpine3.21, alpine3.21 |
| 1.24.9-trixie | 1.24.9, 1.24 |
| 1.24.9-bookworm |  |
| 1.24.9-alpine3.22 | 1.24-alpine3.22, 1.24.9-alpine, 1.24-alpine |
| 1.24.9-alpine3.21 | 1.24-alpine3.21 |


(We automatically update the table each time we update the shared tags)