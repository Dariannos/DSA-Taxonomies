#CoreN
└──  [Union Find Pattern]
    │
    ├── [[Basic Union Find Operations]]
    │   │   / Core functionality of the data structure /
    │   │
    │   ├── ─ [Initialization]
    │   │   │   / Setting up the data structure /
    │   │   │   ├── [Array Representation]
    │   │   │   │   └── Problem: "547. Number of Provinces" (implementation)
    │   │   │   │
    │   │   │   ├── [Tree Representation]
    │   │   │   │   └── Problem: "684. Redundant Connection" (implementation)
    │   │   │   │
    │   │   │   └── [Custom Element Mapping]
    │   │   │       └── Problem: "721. Accounts Merge"
    │   │   │
    │   │   ├── [Find Operation]
    │   │   │   / Determining which set an element belongs to /
    │   │   │   ├── [Basic Find]
    │   │   │   │   └── Problem: "547. Number of Provinces" (basic implementation)
    │   │   │   │
    │   │   │   ├── [Path Compression]
    │   │   │   │   ├── Problem: "684. Redundant Connection" (with path compression)
    │   │   │   │   └── Problem: "128. Longest Consecutive Sequence" (optimized)
    │   │   │   │
    │   │   │   └── [Path Splitting/Halving]
    │   │   │       └── Concept: "Alternative path compression techniques"
    │   │   │
    │   │   └── [Union Operation]
    │   │       / Merging two sets /
    │   │       ├── [Basic Union]
    │   │       │   └── Problem: "547. Number of Provinces" (basic implementation)
    │   │       │
    │   │       ├── [Union by Rank/Size]
    │   │       │   ├── Problem: "684. Redundant Connection" (with union by rank)
    │   │       │   └── Problem: "1202. Smallest String With Swaps" (optimized)
    │   │       │
    │   │       └── [Union by Custom Criteria]
    │   │           └── Problem: "1632. Rank Transform of a Matrix"
    │   │
    │   └── [Data Structure Optimizations]
    │       / Improving union-find performance /
    │       ├── [Path Compression + Union by Rank]
    │       │   ├── Problem: "684. Redundant Connection" (fully optimized)
    │       │   └── Problem: "1202. Smallest String With Swaps" (fully optimized)
    │       │
    │       ├── [Size Tracking]
    │       │   ├── Problem: "323. Number of Connected Components in an Undirected Graph" (with size)
    │       │   └── Problem: "952. Largest Component Size by Common Factor"
    │       │
    │       └── [Dynamic Element Addition]
    │           ├── Problem: "721. Accounts Merge"
    │           └── Problem: "1697. Checking Existence of Edge Length Limited Paths"
    │
    ├── [[Graph Problems]]
    │   │   / Using union-find for graph-related problems /
    │   │
    │   ├── ─ [Connected Components]
    │   │   │   / Finding isolated subgraphs /
    │   │   │   ├── [Counting Components]
    │   │   │   │   ├── Problem: "547. Number of Provinces"
    │   │   │   │   ├── Problem: "323. Number of Connected Components in an Undirected Graph"
    │   │   │   │   └── Problem: "200. Number of Islands" (with union-find)
    │   │   │   │
    │   │   │   ├── [Component Properties]
    │   │   │   │   ├── Problem: "952. Largest Component Size by Common Factor"
    │   │   │   │   └── Problem: "1319. Number of Operations to Make Network Connected"
    │   │   │   │
    │   │   │   └── [Dynamic Connectivity]
    │   │   │       ├── Problem: "305. Number of Islands II"
    │   │   │       └── Problem: "1627. Graph Connectivity With Threshold"
    │   │   │
    │   │   ├── [Cycle Detection]
    │   │   │   / Finding loops in graphs /
    │   │   │   ├── [Undirected Graph Cycles]
    │   │   │   │   ├── Problem: "684. Redundant Connection"
    │   │   │   │   └── Problem: "261. Graph Valid Tree"
    │   │   │   │
    │   │   │   ├── [Directed Graph Cycles]
    │   │   │   │   └── Problem: "685. Redundant Connection II"
    │   │   │   │
    │   │   │   └── [Cycle Classification]
    │   │   │       └── Problem: "1559. Detect Cycles in 2D Grid"
    │   │   │
    │   │   └── [Minimum Spanning Tree]
    │   │       / Finding a tree connecting all vertices with minimum weight /
    │   │       ├── [Kruskal's Algorithm]
    │   │       │   ├── Problem: "1584. Min Cost to Connect All Points"
    │   │       │   └── Problem: "1135. Connecting Cities With Minimum Cost"
    │   │       │
    │   │       └── [Critical Edges]
    │   │           └── Problem: "1489. Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree"
    │   │
    │   └── [Equivalence Relationships]
    │       / Groups of equivalent elements /
    │       ├── [String/Account Grouping]
    │       │   ├── Problem: "721. Accounts Merge"
    │       │   └── Problem: "737. Sentence Similarity II"
    │       │
    │       ├── [Equation Satisfaction]
    │       │   ├── Problem: "990. Satisfiability of Equality Equations"
    │       │   └── Problem: "1579. Remove Max Number of Edges to Keep Graph Fully Traversable"
    │       │
    │       └── [Node Classification]
    │           └── Problem: "839. Similar String Groups"
    │
    ├── [[Advanced Applications]]
    │   │   / Specialized uses of union-find /
    │   │
    │   ├── ─ [Dynamic Graph Problems]
    │   │   │   / Graphs that change over time /
    │   │   │   ├── [Online Queries]
    │   │   │   │   ├── Problem: "1697. Checking Existence of Edge Length Limited Paths"
    │   │   │   │   └── Problem: "305. Number of Islands II"
    │   │   │   │
    │   │   │   ├── [Edge Addition/Removal]
    │   │   │   │   ├── Problem: "1579. Remove Max Number of Edges to Keep Graph Fully Traversable"
    │   │   │   │   └── Problem: "924. Minimize Malware Spread"
    │   │   │   │
    │   │   │   └── [Time-Based Connectivity]
    │   │   │       └── Problem: "1724. Checking Existence of Edge Length Limited Paths II"
    │   │   │
    │   │   ├── [Grid-Based Problems]
    │   │   │   / 2D matrix applications /
    │   │   │   ├── [Island Problems]
    │   │   │   │   ├── Problem: "200. Number of Islands" (union-find approach)
    │   │   │   │   └── Problem: "305. Number of Islands II"
    │   │   │   │
    │   │   │   ├── [Grid Connectivity]
    │   │   │   │   ├── Problem: "1559. Detect Cycles in 2D Grid"
    │   │   │   │   └── Problem: "1254. Number of Closed Islands"
    │   │   │   │
    │   │   │   └── [Percolation]
    │   │   │       └── Problem: "1391. Check if There is a Valid Path in a Grid"
    │   │   │
    │   │   └── [Partition Problems]
    │   │       / Dividing elements into groups /
    │   │       ├── [Set Partitioning]
    │   │       │   ├── Problem: "1202. Smallest String With Swaps"
    │   │       │   └── Problem: "399. Evaluate Division"
    │   │       │
    │   │       ├── [Graph Coloring]
    │   │       │   └── Problem: "785. Is Graph Bipartite?" (union-find approach)
    │   │       │
    │   │       └── [Network Partition]
    │   │           └── Problem: "924. Minimize Malware Spread"
    │   │
    │   └── [Mathematical Applications]
    │       / Union-find for math problems /
    │       ├── [Number Theory Applications]
    │       │   ├── Problem: "952. Largest Component Size by Common Factor"
    │       │   └── Problem: "1627. Graph Connectivity With Threshold"
    │       │
    │       ├── [Matrix Operations]
    │       │   └── Problem: "1632. Rank Transform of a Matrix"
    │       │
    │       └── [Equation System Solving]
    │           ├── Problem: "990. Satisfiability of Equality Equations"
    │           └── Problem: "399. Evaluate Division"
    │
    └── [[Union Find Variations]]
        │   / Modified versions of the algorithm /
        │
        ├── ─ [Weighted Union Find]
        │   │   / Associating weights with elements/edges /
        │   │   ├── [Edge Weight Tracking]
        │   │   │   ├── Problem: "1697. Checking Existence of Edge Length Limited Paths"
        │   │   │   └── Problem: "1584. Min Cost to Connect All Points"
        │   │   │
        │   │   ├── [Union by Weight]
        │   │   │   └── Problem: "1631. Path With Minimum Effort" (union-find approach)
        │   │   │
        │   │   └── [Path Weights]
        │   │       └── Problem: "399. Evaluate Division"
        │
        ├── [Incremental Union Find]
        │   │   / Adding elements or edges over time /
        │   │   ├── [Online Algorithm]
        │   │   │   └── Problem: "305. Number of Islands II"
        │   │   │
        │   │   ├── [Persistent Union Find]
        │   │   │   └── Concept: "Maintaining history of unions"
        │   │   │
        │   │   └── [Reversible Union Find]
        │   │       └── Concept: "Supporting undo operations"
        │
        └── [Union Find with Custom Logic]
            / Special modifications for specific problems /
            ├── [Multiple Union Find Structures]
            │   └── Problem: "1579. Remove Max Number of Edges to Keep Graph Fully Traversable"
            │
            ├── [Lazy Union Find]
            │   └── Problem: "721. Accounts Merge" (with delayed processing)
            │
            └── [Level-Based Union Find]
                └── Problem: "1631. Path With Minimum Effort" (union-find approach)