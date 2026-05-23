# Shared Tags

As the upstream `golang` images, we maintain shared tags. These shared tage always point to the container images that has the highest patch or minor level. This is easier to visualize using the following table:

| Simple Tag | Shared Tags |
| --- | --- |
| 1.26.3-trixie | 1.26.3, 1.26, 1, latest |
| 1.26.3-bookworm |  |
| 1.26.3-alpine3.23 | 1.26-alpine3.23, 1-alpine3.23, alpine3.23, 1.26.3-alpine, 1.26-alpine, 1-alpine, alpine |
| 1.26.3-alpine3.22 | 1.26-alpine3.22, 1-alpine3.22, alpine3.22 |
| 1.25.10-trixie | 1.25.10, 1.25 |
| 1.25.10-bookworm |  |
| 1.25.10-alpine3.23 | 1.25-alpine3.23, 1.25.10-alpine, 1.25-alpine |
| 1.25.10-alpine3.22 | 1.25-alpine3.22 |


(We automatically update the table each time we update the shared tags)