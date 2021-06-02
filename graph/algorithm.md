


| **Algorithm** | **Domain** | **Init** | **Filter** | **Apply** | **Next Active** |
| --- | --- | --- | --- |
| Dijkstra | Seq SSSP | source <- 0; others <- inf | visited[u] == -1 | D[u] = min(D[u], D[v] + E(u,v)) visited[v] = -1 |  |
| △-Stepping | Par SSSP |  |  |

