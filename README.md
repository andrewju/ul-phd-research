# ul-phd-thesis
PhD Research

Suppose we must schedule parliamentary committee meetings into designated weekly time periods. We cannot assign two committees to the same time if they have a common member. How many different time periods do we need? (Or more precisely, what is the minimal number of different time periods that we need?)

We create a vertex for each committee, with two vertices adjacent when their committee have a common member. We must assign labels (time periods) to the vertices so the endpoints of each edge receive different labels. The labels have no numerical value, so we call them colors. This is the vertex coloring problem. In this example, each time period is identical, that is, each member has the same set of available time slots. But in reality people may not be available for certain time slots. Due to the difference between each committee member's available time slots, each committee meeting corresponds to a list of available time slots. Then for the graph, each vertex may be colored only a color from a prescribed set, this is the list coloring problem.

Many applications of vertex coloring are more appropriately modelled as instances of list coloring, e.g, scheduling, register allocation, etc. Therefore we argue that it is an important problem to consider. In spite of its importance few published algorithms exist for list coloring, however. In this research, we have conducted extensive experimental research on the problem, and built up benchmarks for further research in the problem.
