#CoreN
└── [Segment Tree & Fenwick Tree Pattern]
    │
    ├── [[Segment Tree]]
    │   │   / Tree data structure for range queries and updates /
    │   │
    │   ├── ─ [Basic Segment Tree Operations]
    │   │   │   / Core segment tree functionality /
    │   │   │   ├── [Construction]
    │   │   │   │   ├── Technique: "Building a segment tree from an array"
    │   │   │   │   └── Application: "Initializing for range queries"
    │   │   │   │
    │   │   │   ├── [Point Update]
    │   │   │   │   ├── Technique: "Updating a single element"
    │   │   │   │   └── Problem: "307. Range Sum Query - Mutable"
    │   │   │   │
    │   │   │   └── [Range Query]
    │   │   │       ├── Technique: "Querying over a range"
    │   │   │       └── Problem: "307. Range Sum Query - Mutable"
    │   │   │
    │   │   ├── [Range Query Types]
    │   │   │   / Different aggregation operations /
    │   │   │   ├── [Range Sum]
    │   │   │   │   ├── Problem: "307. Range Sum Query - Mutable"
    │   │   │   │   └── Problem: "327. Count of Range Sum"
    │   │   │   │
    │   │   │   ├── [Range Minimum/Maximum]
    │   │   │   │   ├── Problem: "239. Sliding Window Maximum" (segment tree approach)
    │   │   │   │   └── Application: "Range minimum query (RMQ)"
    │   │   │   │
    │   │   │   └── [Range GCD/LCM]
    │   │   │       ├── Application: "Finding GCD over ranges"
    │   │   │       └── Technique: "Using Segment Tree for GCD queries"
    │   │   │
    │   │   └── [Range Update Operations]
    │   │       / Updating multiple elements at once /
    │   │       ├── [Lazy Propagation]
    │   │       │   ├── Technique: "Deferring updates for efficiency"
    │   │       │   └── Problem: "699. Falling Squares"
    │   │       │
    │   │       ├── [Range Addition]
    │   │       │   ├── Problem: "370. Range Addition" (segment tree approach)
    │   │       │   └── Problem: "598. Range Addition II"
    │   │       │
    │   │       └── [Range Set Value]
    │   │           ├── Problem: "715. Range Module"
    │   │           └── Technique: "Setting all values in a range"
    │   │
    │   ├── [Advanced Segment Tree Techniques]
    │   │   / Specialized segment tree variants /
    │   │   │
    │   │   ├── [Persistent Segment Tree]
    │   │   │   / Maintaining tree history /
    │   │   │   ├── Technique: "Version control for segment trees"
    │   │   │   └── Application: "Time travel queries"
    │   │   │
    │   │   ├── [2D Segment Tree]
    │   │   │   / Handling 2D range queries /
    │   │   │   ├── Technique: "Building 2D segment trees"
    │   │   │   └── Problem: "1292. Maximum Side Length of a Square with Sum Less than or Equal to Threshold"
    │   │   │
    │   │   └── [Merge Sort Tree]
    │   │       / Storing sorted arrays at nodes /
    │   │       ├── Technique: "Segment tree with sorted arrays at each node"
    │   │       ├── Problem: "315. Count of Smaller Numbers After Self"
    │   │       └── Problem: "493. Reverse Pairs"
    │   │
    │   └── [Segment Tree Applications]
    │       / Real-world use cases /
    │       │
    │       ├── [Range Query Problems]
    │       │   / Finding information over intervals /
    │       │   ├── Problem: "699. Falling Squares"
    │       │   ├── Problem: "732. My Calendar III"
    │       │   └── Problem: "850. Rectangle Area II"
    │       │
    │       ├── [Competitive Programming Applications]
    │       │   / Segment trees in contests /
    │       │   ├── Technique: "Range updates and queries optimization"
    │       │   └── Application: "SPOJ and Codeforces problems"
    │       │
    │       └── [Interval Processing]
    │           / Managing intervals efficiently /
    │           ├── Problem: "715. Range Module"
    │           ├── Problem: "218. The Skyline Problem" (segment tree approach)
    │           └── Problem: "729. My Calendar I"
    │
    ├── [[Fenwick Tree (Binary Indexed Tree)]]
    │   │   / Efficient structure for cumulative frequency tables /
    │   │
    │   ├── ─ [Basic Fenwick Tree Operations]
    │   │   │   / Core Fenwick tree functionality /
    │   │   │   ├── [Construction]
    │   │   │   │   ├── Technique: "Building a Fenwick tree from an array"
    │   │   │   │   └── Application: "Initializing for prefix sums"
    │   │   │   │
    │   │   │   ├── [Point Update]
    │   │   │   │   ├── Technique: "Adding value to a single element"
    │   │   │   │   └── Problem: "307. Range Sum Query - Mutable" (BIT approach)
    │   │   │   │
    │   │   │   └── [Prefix Sum Query]
    │   │   │       ├── Technique: "Calculating sum up to an index"
    │   │   │       └── Problem: "303. Range Sum Query - Immutable" (BIT approach)
    │   │   │
    │   │   ├── [Range Operations]
    │   │   │   / Operations over intervals /
    │   │   │   ├── [Range Sum Query]
    │   │   │   │   ├── Technique: "Finding sum between two indices"
    │   │   │   │   └── Problem: "307. Range Sum Query - Mutable" (BIT approach)
    │   │   │   │
    │   │   │   ├── [Range Update (Using multiple BITs)]
    │   │   │   │   ├── Technique: "Updating a range efficiently"
    │   │   │   │   └── Problem: "370. Range Addition" (BIT approach)
    │   │   │   │
    │   │   │   └── [Finding Kth Element]
    │   │   │       ├── Technique: "Binary search with Fenwick tree"
    │   │   │       └── Application: "Finding kth smallest element in a changing array"
    │   │   │
    │   │   └── [Fenwick Tree Variants]
    │   │       / Specialized BIT implementations /
    │   │       ├── [2D Fenwick Tree]
    │   │       │   ├── Technique: "Handling 2D range queries"
    │   │       │   └── Problem: "308. Range Sum Query 2D - Mutable"
    │   │       │
    │   │       └── [Compressed Fenwick Tree]
    │   │           ├── Technique: "Using BIT with coordinate compression"
    │   │           └── Application: "Handling large or non-integer indices"
    │   │
    │   └── [Fenwick Tree Applications]
    │       / Common use cases /
    │       │
    │       ├── [Inversion Counting]
    │       │   / Counting out-of-order pairs /
    │       │   ├── Problem: "315. Count of Smaller Numbers After Self"
    │       │   ├── Problem: "493. Reverse Pairs"
    │       │   └── Problem: "775. Global and Local Inversions"
    │       │
    │       ├── [Rank Queries]
    │       │   / Finding element positions in sorted order /
    │       │   ├── Technique: "Tracking element ranks"
    │       │   └── Application: "Order statistics in a dynamic set"
    │       │
    │       └── [Cumulative Distribution]
    │           / Tracking frequency distributions /
    │           ├── Technique: "Maintaining histograms"
    │           └── Application: "Finding elements in certain frequency ranges"
    │
    ├── [[Comparison and Selection]]
    │   │   / Choosing between segment and Fenwick trees /
    │   │
    │   ├── ─ [Segment Tree vs. Fenwick Tree]
    │   │   │   / Trade-offs between the structures /
    │   │   │   ├── [Memory Usage Comparison]
    │   │   │   │   ├── Analysis: "Fenwick trees are more space-efficient"
    │   │   │   │   └── Application: "Memory-constrained environments"
    │   │   │   │
    │   │   │   ├── [Operation Flexibility]
    │   │   │   │   ├── Analysis: "Segment trees support more operations"
    │   │   │   │   └── Application: "Complex range operations"
    │   │   │   │
    │   │   │   └── [Implementation Complexity]
    │   │   │       ├── Analysis: "Fenwick trees are simpler to implement"
    │   │   │       └── Application: "Quick prototyping"
    │   │
    │   └── [Alternative Data Structures]
    │       / Other structures for range queries /
    │       │
    │       ├── [Sparse Table]
    │       │   / Static RMQ with O(1) queries /
    │       │   ├── Technique: "Precomputing all range queries"
    │       │   └── Application: "Static arrays with min/max queries"
    │       │
    │       ├── [Square Root Decomposition]
    │       │   / Dividing array into blocks /
    │       │   ├── Technique: "Block-based processing"
    │       │   └── Problem: "307. Range Sum Query - Mutable" (sqrt decomposition)
    │       │
    │       └── [Wavelet Tree]
    │           / Multi-level structure for ranges /
    │           ├── Technique: "Hierarchical range structure"
    │           └── Application: "Rank and select operations"
    │
    └── [[Real-World Applications]]
        │   / Practical use cases /
        │
        ├── [Database Systems]
        │   / Using trees in databases /
        │   ├── Application: "Range queries in columnar databases"
        │   └── Application: "Time-series data indexing"
        │
        ├── [Computational Geometry]
        │   / Geometric problem solving /
        │   ├── Problem: "218. The Skyline Problem"
        │   └── Application: "Rectangle intersection queries"
        │
        └── [Network Analysis]
            / Monitoring network metrics /
            ├── Application: "Traffic monitoring over time windows"
            └── Application: "Network load balancing"