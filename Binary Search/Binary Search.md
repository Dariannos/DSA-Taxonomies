#CoreN
└──  [Binary Search Pattern]
    │
    ├── [[Classic Binary Search (On Index)]]
    │   │   / Core concept: Searching in sorted arrays with O(log n) time complexity /
    │   │
    │   ├── ─ Exact Match Search
    │   │   │   / Finding a specific target value /
    │   │   │   ├── Problem: "704. Binary Search" (Fundamental template)
    │   │   │   └── Application: "69. Sqrt(x)" (Finding integer sqrt)
    │   │   │
    │   │   ├── ─ Boundary Detection
    │   │   │   │   / Finding the first or last occurrence of a target /
    │   │   │   │   └── Problem: "34. Find First and Last Position of Element in Sorted Array"
    │   │   │
    │   │   └── ─ Position-based Applications
    │   │       │   / Finding insertion position or closest elements /
    │   │       │   ├── Problem: "35. Search Insert Position"
    │   │       │   └── Problem: "374. Guess Number Higher or Lower"
    │   │
    ├── [[Modified Search Space]]
    │   │   / Dealing with arrays that have special properties but can still use binary search /
    │   │
    │   ├── ─ Rotated Sorted Arrays
    │   │   │   / Arrays sorted then rotated around a pivot point /
    │   │   │   ├── Problem: "153. Find Minimum in Rotated Sorted Array"
    │   │   │   ├── Problem: "154. Find Minimum in Rotated Sorted Array II" (With duplicates)
    │   │   │   ├── Problem: "33. Search in Rotated Sorted Array"
    │   │   │   └── Problem: "81. Search in Rotated Sorted Array II" (With duplicates)
    │   │   │
    │   │   ├── ─ Mountain or Bitonic Arrays
    │   │   │   / Arrays that increase then decrease /
    │   │   │   ├── Problem: "852. Peak Index in a Mountain Array"
    │   │   │   ├── Problem: "162. Find a Peak Element"
    │   │   │   └── Problem: "1095. Find in Mountain Array"
    │   │   │
    │   │   └── ─ Unknown-Sized or Infinite Arrays
    │   │       / Searching when array bounds are unknown /
    │   │       └── Problem: "702. Search in a Sorted Array of Unknown Size"
    │
    ├── [[Binary Search on the Answer Space]]
    │   │   / Using binary search on possible answers rather than indices /
    │   │
    │   ├── ─ Minimize a Maximum Value
    │   │   │   / Finding the smallest possible maximum value /
    │   │   │   ├── Problem: "2616. Minimize the Maximum Difference of Pairs"
    │   │   │   ├── Problem: "410. Split Array Largest Sum"
    │   │   │   ├── Problem: "1011. Capacity To Ship Packages Within D Days"
    │   │   │   └── Problem: "875. Koko Eating Bananas"
    │   │   │
    │   │   ├── ─ Maximize a Minimum Value
    │   │   │   / Finding the largest possible minimum value /
    │   │   │   ├── Problem: "1552. Magnetic Force Between Two Balls"
    │   │   │   └── Problem: "1870. Minimum Speed to Arrive on Time"
    │   │   │
    │   │   └── ─ Mathematical & Counting Applications
    │   │       │   / Using binary search for numeric computations /
    │   │       │   ├── Problem: "69. Sqrt(x)" (Also an exact match problem)
    │   │       │   ├── Problem: "378. Kth Smallest Element in a Sorted Matrix"
    │   │       │   └── Problem: "4. Median of Two Sorted Arrays" (Hard)
    │
    └── [[Specialized Variants]]
        │   / Extensions and modifications of binary search /
        │
        ├── ─ Ternary Search
        │   │   / Dividing search space into three parts /
        │   │   ├── Application: "852. Peak Index in a Mountain Array"
        │   │   └── Use Case: "Finding extrema in unimodal functions"
        │
        ├── ─ Advanced Matrix Search
        │   │   / Binary search in 2D sorted matrices /
        │   │   ├── Problem: "74. Search a 2D Matrix" (Row-then-column sorted)
        │   │   └── Problem: "240. Search a 2D Matrix II" (Row and column sorted)
        │
        └── ─ Parallel Binary Search
            │   / Using binary search across multiple constraints /
            │   └── Problem: "1482. Minimum Number of Days to Make m Bouquets"