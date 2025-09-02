#CoreN
└── [Design Pattern]
    │
    ├── [Data Structure Design]
    │   / Creating custom data structures /
    │
    │   ├── [Cache Design]
    │   │   / Efficiently storing and retrieving data /
    │   │   ├── [LRU Cache]
    │   │   │   ├── Problem: "146. LRU Cache"
    │   │   │   └── Application: "Page replacement algorithms"
    │   │   ├── [LFU Cache]
    │   │   │   ├── Problem: "460. LFU Cache"
    │   │   │   └── Application: "Content delivery networks"
    │   │   └── [Time-Based Caching]
    │   │       ├── Problem: "981. Time Based Key-Value Store"
    │   │       └── Application: "Session management"
    │   │
    │   ├── [Custom Hash Structures]
    │   │   / Implementing hash-based collections /
    │   │   ├── [HashMap Implementation]
    │   │   │   ├── Problem: "706. Design HashMap"
    │   │   │   └── Problem: "1146. Snapshot Array"
    │   │   ├── [HashSet Implementation]
    │   │   │   ├── Problem: "705. Design HashSet"
    │   │   │   └── Application: "Duplicate detection"
    │   │   └── [Specialized Hash Structures]
    │   │       ├── Problem: "380. Insert Delete GetRandom O(1)"
    │   │       └── Problem: "381. Insert Delete GetRandom O(1) - Duplicates allowed"
    │   │
    │   └── [Advanced Collections]
    │       / Specialized data containers /
    │       ├── [Multi-level Data Structures]
    │       │   ├── Problem: "341. Flatten Nested List Iterator"
    │       │   └── Problem: "432. All O`one Data Structure"
    │       ├── [Stack & Queue Variants]
    │       │   ├── Problem: "155. Min Stack"
    │       │   ├── Problem: "232. Implement Queue using Stacks"
    │       │   ├── Problem: "225. Implement Stack using Queues"
    │       │   └── Problem: "622. Design Circular Queue"
    │       └── [Custom Priority Structures]
    │           ├── Problem: "1845. Seat Reservation Manager"
    │           └── Problem: "895. Maximum Frequency Stack"
    │
    ├── [Tree & Graph Structures]
    │   / Designing hierarchical data structures /
    │   ├── [Tree-Based Designs]
    │   │   / Implementing tree structures /
    │   │   ├── [Trie Implementation]
    │   │   │   ├── Problem: "208. Implement Trie (Prefix Tree)"
    │   │   │   ├── Problem: "211. Design Add and Search Words Data Structure"
    │   │   │   └── Problem: "1166. Design File System"
    │   │   ├── [Binary Search Tree]
    │   │   │   ├── Problem: "173. Binary Search Tree Iterator"
    │   │   │   └── Problem: "1586. Binary Search Tree Iterator II"
    │   │   └── [Advanced Tree Structures]
    │   │       ├── Problem: "297. Serialize and Deserialize Binary Tree"
    │   │       └── Problem: "355. Design Twitter" (feed generation)
    │   ├── [Graph-Based Designs]
    │   │   / Implementing graph structures /
    │   │   ├── [Basic Graph Implementations]
    │   │   │   ├── Technique: "Adjacency list vs. matrix"
    │   │   │   └── Problem: "997. Find the Town Judge" (graph property)
    │   │   └── [Specialized Graph Structures]
    │   │       ├── Problem: "355. Design Twitter" (social network)
    │   │       └── Problem: "1136. Parallel Courses" (dependency graphs)
    │   └── [Search & Index Structures]
    │       / Fast lookup structures /
    │       ├── [Search Engine Design]
    │       │   ├── Problem: "642. Design Search Autocomplete System"
    │       │   └── Application: "Type-ahead search"
    │       └── [Database Index Design]
    │           ├── Problem: "1570. Dot Product of Two Sparse Vectors"
    │           └── Application: "Column indices for fast query"
    │
    ├── [System Design Components]
    │   / Building blocks for larger systems /
    │   ├── [File System Design]
    │   │   / Managing hierarchical data /
    │   │   ├── [Directory Structure]
    │   │   │   ├── Problem: "588. Design In-Memory File System"
    │   │   │   └── Problem: "1166. Design File System"
    │   │   └── [File Operations]
    │   │       ├── Problem: "1500. Design a File Sharing System"
    │   │       └── Application: "Distributed file systems"
    │   ├── [Rate Limiters]
    │   │   / Controlling access frequency /
    │   │   ├── [Window-Based Limiters]
    │   │   │   ├── Problem: "359. Logger Rate Limiter"
    │   │   │   └── Problem: "362. Design Hit Counter"
    │   │   └── [Token Bucket Limiters]
    │   │       └── Application: "API rate limiting"
    │   └── [Memory Management]
    │       / Efficiently allocating resources /
    │       ├── [Pool Allocators]
    │       │   ├── Problem: "1845. Seat Reservation Manager"
    │       │   └── Application: "Connection pooling"
    │       └── [Memory Efficient Structures]
    │           ├── Problem: "1570. Dot Product of Two Sparse Vectors"
    │           └── Problem: "1244. Design A Leaderboard"
    │
    ├── [Business Logic Components]
    │   / Application-specific functionality /
    │   ├── [Reservation Systems]
    │   │   / Managing time-based allocations /
    │   │   ├── [Calendar Systems]
    │   │   │   ├── Problem: "729. My Calendar I"
    │   │   │   ├── Problem: "731. My Calendar II"
    │   │   │   └── Problem: "732. My Calendar III"
    │   │   └── [Resource Booking]
    │   │       ├── Problem: "1845. Seat Reservation Manager"
    │   │       └── Problem: "1229. Meeting Scheduler"
    │   ├── [Parking Systems]
    │   │   / Vehicle management /
    │   │   ├── Problem: "1603. Design Parking System"
    │   │   └── Application: "Real-time parking allocation"
    │   └── [Game Implementations]
    │       / Interactive system design /
    │       ├── [Board Games]
    │       │   ├── Problem: "348. Design Tic-Tac-Toe"
    │       │   └── Problem: "1275. Find Winner on a Tic Tac Toe Game"
    │       └── [Other Games]
    │           ├── Problem: "353. Design Snake Game"
    │           └── Problem: "1396. Design Underground System"
    │
    ├── [User Interface Components]
    │   / Interaction-focused designs /
    │   ├── [Navigation Systems]
    │   │   / Moving through interface states /
    │   │   ├── [Browser History]
    │   │   │   ├── Problem: "1472. Design Browser History"
    │   │   │   └── Application: "Web browser navigation"
    │   │   └── [Menu Navigation]
    │   │       └── Application: "Application menu design"
    │   ├── [Text Editors]
    │   │   / Document manipulation /
    │   │   ├── Problem: "1429. First Unique Number" (related concept)
    │   │   └── Application: "Document editing with undo/redo"
    │   └── [Typeahead & Autocomplete]
    │       / Predictive user interaction /
    │       ├── Problem: "642. Design Search Autocomplete System"
    │       └── Application: "Search suggestion systems"
    │
    └── [Design Patterns & Principles]
        / Reusable solutions to common problems /
        ├── [Creational Patterns]
        │   / Object creation mechanisms /
        │   ├── [Factory Method]
        │   │   └── Application: "Creating different types of game objects"
        │   ├── [Singleton]
        │   │   └── Application: "Global access points like loggers"
        │   └── [Builder Pattern]
        │       └── Application: "Complex object construction"
        ├── [Structural Patterns]
        │   / Object composition /
        │   ├── [Adapter Pattern]
        │   │   └── Application: "Making incompatible interfaces work together"
        │   ├── [Decorator Pattern]
        │   │   └── Application: "Adding responsibilities to objects dynamically"
        │   └── [Composite Pattern]
        │       └── Application: "Tree structures like file systems"
        └── [Behavioral Patterns]
            / Communication between objects /
            ├── [Iterator Pattern]
            │   ├── Problem: "284. Peeking Iterator"
            │   ├── Problem: "341. Flatten Nested List Iterator"
            │   └── Application: "Traversing collections"
            ├── [Observer Pattern]
            │   └── Application: "Event notification systems"
            └── [Strategy Pattern]
                └── Application: "Swappable algorithms"
