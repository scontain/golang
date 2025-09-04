# Shared Tags

As the upstream `golang` images, we maintain shared tags. These shared tage always point to the container images that has the highest patch or minor level. This is easier to visualize using the following table:

| Simple Tag | Shared Tags |
| --- | --- |
| 1.25.1-trixie | 1.25.1, 1.25, 1, latest |
| 1.25.1-bookworm |  |
| 1.25.1-alpine3.22 | 1.25-alpine3.22, 1-alpine3.22, alpine3.22, 1.25.1-alpine, 1.25-alpine, 1-alpine, alpine |
| 1.25.1-alpine3.21 | 1.25-alpine3.21, 1-alpine3.21, alpine3.21 |
| 1.24.7-trixie | 1.24.7, 1.24 |
| 1.24.7-bookworm |  |
| 1.24.7-alpine3.22 | 1.24-alpine3.22, 1.24.7-alpine, 1.24-alpine |
| 1.24.7-alpine3.21 | 1.24-alpine3.21 |


(We automatically update the table each time we update the shared tags)