# 🏰 The Ultimate DSA Mastery Roadmap (C# Edition)

[![Status](https://img.shields.io/badge/Status-In_Progress-yellow)]() [![Language](https://img.shields.io/badge/Language-C%23-purple)]() [![Focus](https://img.shields.io/badge/Focus-Patterns_&_Intuition-blue)]()

> **Goal:** Move beyond code memorization to deep algorithmic intuition.  
> **Philosophy:** Understand the *Pattern*, Visualize the *Movement*, Master the *Trade-offs*.

---


## 🚀 DSA MASTERY: THE 13-WEEK JOURNEY

```text
PHASE 1: FOUNDATIONS (Understand the Machine)
│
├── WEEK 1: COMPUTATIONAL MODEL
│   ├── Day 1: RAM Model & Pointers (How memory works)
│   ├── Day 2: Asymptotic Analysis (Big-O derivation)
│   ├── Day 3: Space Complexity (Stack vs Heap)
│   ├── Day 4: Recursion I (Stack frames, base cases)
│   └── Day 5: Recursion II (Tail recursion, mutual recursion)
│
├── WEEK 2: LINEAR STRUCTURES
│   ├── Day 1: Arrays (Cache locality, contiguous memory)
│   ├── Day 2: Dynamic Arrays (Amortized analysis)
│   ├── Day 3: Linked Lists (Pointer structures)
│   ├── Day 4: Stacks & Queues (LIFO/FIFO ADTs)
│   └── Day 5: Binary Search (Logarithmic reduction)
│
└── WEEK 3: SORTING & HASHING
    ├── Day 1: Elementary Sorts (Bubble, Insertion, Selection)
    ├── Day 2: Merge Sort & Quick Sort (Divide & Conquer)
    ├── Day 3: Heap Sort & Variants (In-place sorting)
    ├── Day 4: Hash Tables I (Hash functions, collisions)
    └── Day 5: Hash Tables II (Chaining vs Open Addressing)

PHASE 2: PATTERNS & HIERARCHIES
│
├── WEEK 4: PROBLEM-SOLVING PATTERNS
│   ├── Day 1: Two Pointers (Strategy & invariants)
│   ├── Day 2: Sliding Window - Fixed (Subarray analysis)
│   ├── Day 3: Sliding Window - Variable (Optimization)
│   ├── Day 4: Prefix Sums (Range query optimization)
│   └── Day 5: Cycle Detection (Floyd's Algorithm)
│
├── ⭐ WEEK 4.5: TIER 1 - CRITICAL PATTERNS (High ROI)
│   ├── Day 1: Hash Map / Hash Set (70% of interviews)
│   ├── Day 2: Monotonic Stack (Next Greater Element)
│   ├── Day 3: Merge Operations (Sorted structures)
│   ├── Day 4a: Partitioning (Dutch National Flag)
│   └── Day 4b: Kadane's Algorithm (Max Subarray)
│
├── WEEK 5: TREES & HEAPS
│   ├── Day 1: Binary Tree Anatomy (Properties)
│   ├── Day 2: Tree Traversals (In/Pre/Post/Level)
│   ├── Day 3: Binary Search Trees (BST invariants)
│   ├── Day 4: Heaps & Priority Queues (Complete trees)
│   └── Day 5: Balanced Trees (AVL/Red-Black concepts)
│
└── ⭐ WEEK 5.5: TIER 2 - STRATEGIC PATTERNS
    ├── Day 1: Difference Array (Range updates)
    ├── Day 2: In-Place Replacement (Space optimization)
    └── Day 3: Deque Operations (Sliding window max)

PHASE 3: GRAPHS & NETWORKS
│
├── WEEK 6: GRAPH FOUNDATIONS
│   ├── Day 1: Graph Representations (Adj Matrix vs List)
│   ├── Day 2: Breadth-First Search (Shortest path unweighted)
│   ├── Day 3: Depth-First Search (Recursive exploration)
│   ├── Day 4: Topological Sort (Dependency resolution)
│   └── Day 5: Union-Find (Disjoint Set Forest)
│
└── WEEK 7: ADVANCED GRAPHS
    ├── Day 1: Dijkstra's Algorithm (Weighted shortest path)
    ├── Day 2: Bellman-Ford & Floyd-Warshall (Negative weights)
    ├── Day 3: Minimum Spanning Trees (Kruskal & Prim)
    ├── Day 4: Network Flow I (Max Flow / Ford-Fulkerson)
    └── Day 5: Network Flow II (Min Cut / Bipartite Matching)

PHASE 4: ADVANCED TOPICS
│
├── WEEK 8: SPECIALIZED STRUCTURES
│   ├── Day 1: Tries (Prefix Trees)
│   ├── Day 2: Segment Trees I (Range Queries)
│   ├── Day 3: Segment Trees II (Lazy Propagation)
│   ├── Day 4: Fenwick Trees (Binary Indexed Trees)
│   └── Day 5: Suffix Structures (Arrays & Trees)
│
└── WEEK 9: STRING & MATH
    ├── Day 1: KMP Algorithm (Pattern matching)
    ├── Day 2: Rabin-Karp (Rolling Hash)
    ├── Day 3: Number Theory (Primes, GCD)
    ├── Day 4: Modular Arithmetic (Exponentials)
    └── Day 5: Computational Geometry (Convex Hull)

PHASE 5: ALGORITHMS & MASTERY
│
├── WEEK 10: GREEDY & BACKTRACKING
│   ├── Day 1: Greedy Paradigm (Exchange arguments)
│   ├── Day 2: Backtracking I (Constraint satisfaction)
│   ├── Day 3: Backtracking II (Advanced pruning)
│   ├── Day 4: Pruning & Optimization (Search space reduction)
│   └── Day 5: Divide and Conquer (Paradigm analysis)
│
├── WEEK 11: DYNAMIC PROGRAMMING
│   ├── Day 1: DP Philosophy (Memoization vs Tabulation)
│   ├── Day 2: 1D DP (Linear recurrence)
│   ├── Day 3: Classic Patterns (LCS, Knapsack)
│   ├── Day 4: 2D / Sequence DP (Grid problems)
│   └── Day 5: Advanced DP (Bitmask / Tree DP)
│
├── WEEK 12: INTERVIEW MASTERY (Capstone)
│   ├── Day 1: Merge Intervals (Sweep line)
│   ├── Day 2: Monotonic Stack Advanced (Rectangles)
│   ├── Day 3: Cyclic Sort (In-place rearrangement)
│   ├── Day 4: Matrix Problems (Traversal patterns)
│   └── Day 5: System Review & Integration
│
└── ⭐ WEEK 13+: TIER 3 - EXTENSION PATTERNS
    ├── Pattern 1: Fast & Slow Pointers (Extended)
    ├── Pattern 2: Reverse & Two Pointers
    ├── Pattern 3: Matrix Traversal
    └── Pattern 4: Conversion & Encoding
```

---

## 🗺️ Visual Overview

### visual summary
```mermaid
graph TD
    %% Main Nodes
    Start((🚀 Start)) --> P1
    P1[Phase 1: Foundations] --> P2[Phase 2: Patterns & Trees]
    P2 --> T1{"⭐ Week 4.5<br/>TIER 1 PATTERNS<br/>(Must Know)"}
    T1 --> P3[Phase 3: Graphs]
    P2 --> T2{"⚡ Week 5.5<br/>TIER 2 PATTERNS<br/>(Strategic)"}
    P3 --> P4[Phase 4: Adv & Math]
    P4 --> P5[Phase 5: Paradigms]
    P5 --> P6[Phase 6: Mastery]
    P6 --> T3{"🚀 Week 13+<br/>TIER 3 PATTERNS<br/>(Niche)"}

    %% Styling
    classDef tier fill:#f96,stroke:#333,stroke-width:2px,color:black;
    class T1,T2,T3 tier;
```

### Phase 1 

```mermaid
graph TB
    %% Styling
    classDef day fill:#e3f2fd,stroke:#1565c0,stroke-width:1px,rx:5,ry:5;
    classDef weekLabel fill:#1565c0,stroke:#fff,stroke-width:0px,color:#fff,font-weight:bold,rx:5,ry:5;

    %% Row 1: Week 1
    subgraph Week1 [Week 1: Core Concepts]
        direction LR
        W1_L[Week 1]:::weekLabel
        D1_1(RAM & Pointers):::day --> D1_2(Big-O Analysis):::day
        D1_2 --> D1_3(Space Complexity):::day
        D1_3 --> D1_4(Recursion I):::day
        D1_4 --> D1_5(Recursion II):::day
    end

    %% Row 2: Week 2
    subgraph Week2 [Week 2: Linear Structures]
        direction LR
        W2_L[Week 2]:::weekLabel
        D2_1(Arrays):::day --> D2_2(Dynamic Arrays):::day
        D2_2 --> D2_3(Linked Lists):::day
        D2_3 --> D2_4(Stacks & Queues):::day
        D2_4 --> D2_5(Binary Search):::day
    end

    %% Row 3: Week 3
    subgraph Week3 [Week 3: Sorting & Hashing]
        direction LR
        W3_L[Week 3]:::weekLabel
        D3_1(Elementary Sorts):::day --> D3_2(Merge/Quick):::day
        D3_2 --> D3_3(Heap Sort):::day
        D3_3 --> D3_4(Hash Tables I):::day
        D3_4 --> D3_5(Hash Tables II):::day
    end

    %% Connections to force vertical stacking
    Week1 --> Week2 --> Week3
```

### Phase 2

```mermaid
graph TB
    %% Styling
    classDef day fill:#e8eaf6,stroke:#3949ab,stroke-width:1px,rx:5,ry:5;
    classDef tierDay fill:#fff9c4,stroke:#fbc02d,stroke-width:1px,rx:5,ry:5;
    classDef weekLabel fill:#3949ab,stroke:#fff,stroke-width:0px,color:#fff,font-weight:bold,rx:5,ry:5;
    classDef tierLabel fill:#fbc02d,stroke:#fff,stroke-width:0px,color:#000,font-weight:bold,rx:5,ry:5;

    %% Row 1: Week 4
    subgraph Week4 [Week 4: Basic Patterns]
        direction LR
        W4_L[Week 4]:::weekLabel
        D4_1(Two Pointers):::day --> 
        D4_2(Sliding Window Fixed):::day
        D4_2 --> D4_3(Sliding Window Variable):::day
        D4_3 --> D4_4(Prefix Sums):::day
        D4_4 --> D4_5(Cycle Detection):::day
    end

    %% Row 2: Week 4.5 (Tier 1)
    subgraph Week45 [Week 4.5: TIER 1 PATTERNS]
        direction LR
        W45_L[⭐ TIER 1]:::tierLabel
        T1_1(Hash Map / Hash Set):::tierDay --> T1_2(Monotonic Stack):::tierDay
        T1_2 --> T1_3(Merge Operations):::tierDay
        T1_3 --> T1_4(Partitioning):::tierDay
        T1_4 --> T1_5(Kadane's Algorithm):::tierDay
    end

    %% Row 3: Week 5
    subgraph Week5 [Week 5: Trees & Heaps]
        direction LR
        W5_L[Week 5]:::weekLabel
        D5_1(Binary Tree Anatomy):::day --> D5_2(Traversals):::day
        D5_2 --> D5_3(Binary Search Trees):::day
        D5_3 --> D5_4(Heaps & Priority Queues):::day
        D5_4 --> D5_5(Balanced Trees):::day
    end

    %% Row 4: Week 5.5 (Tier 2)
    subgraph Week55 [Week 5.5: TIER 2 PATTERNS]
        direction LR
        W55_L[⚡ TIER 2]:::tierLabel
        T2_1(Difference Array):::tierDay --> T2_2(In-Place Replacement):::tierDay
        T2_2 --> T2_3(Deque Operations):::tierDay
    end

    Week4 --> Week45 --> Week5 --> Week55
```

### Phase 3

```mermaid
graph TB
    %% Styling
    classDef day fill:#f3e5f5,stroke:#8e24aa,stroke-width:1px,rx:5,ry:5;
    classDef weekLabel fill:#8e24aa,stroke:#fff,stroke-width:0px,color:#fff,font-weight:bold,rx:5,ry:5;

    %% Row 1: Week 6
    subgraph Week6 [Week 6: Graph Foundations]
        direction LR
        W6_L[Week 6]:::weekLabel
        D6_1(Graph Representations):::day --> D6_2(BFS - Shortest):::day
        D6_2 --> D6_3(DFS - Explore):::day
        D6_3 --> D6_4(Topological Sort):::day
        D6_4 --> D6_5(Union-Find):::day
    end

    %% Row 2: Week 7
    subgraph Week7 [Week 7: ADVANCED GRAPH ALGORITHMS]
        direction LR
        W7_L[Week 7]:::weekLabel
        D7_1(Dijkstra's Algorithm):::day --> D7_2(Bellman/Floyd):::day
        D7_2 --> D7_3(MST - Prim/Krus):::day
        D7_3 --> D7_4(Network Flow I):::day
        D7_4 --> D7_5(Network Flow II):::day
    end

    Week6 --> Week7
```

### Phase 4 

```mermaid
graph TB
    %% Styling
    classDef day fill:#fff3e0,stroke:#ef6c00,stroke-width:1px,rx:5,ry:5;
    classDef weekLabel fill:#ef6c00,stroke:#fff,stroke-width:0px,color:#fff,font-weight:bold,rx:5,ry:5;

    %% Row 1: Week 8
    subgraph Week8 [Week 8: SPECIALIZED STRUCTURES]
        direction LR
        W8_L[Week 8]:::weekLabel
        D8_1(Tries / Prefix):::day --> D8_2(Segment Trees I):::day
        D8_2 --> D8_3(Segment Trees II):::day
        D8_3 --> D8_4(Fenwick Tree):::day
        D8_4 --> D8_5(Suffix Structures):::day
    end

    %% Row 2: Week 9
    subgraph Week9 [Week 9: STRING & MATH ALGORITHMS]
        direction LR
        W9_L[Week 9]:::weekLabel
        D9_1(KMP):::day --> D9_2(Rabin-Karp):::day
        D9_2 --> D9_3(Number Theory):::day
        D9_3 --> D9_4(Modular Arithmetic):::day
        D9_4 --> D9_5(Computational Geometry):::day
    end

    Week8 --> Week9
```

### Phase 5 

```mermaid
graph TB
    %% Styling
    classDef day fill:#ffebee,stroke:#c62828,stroke-width:1px,rx:5,ry:5;
    classDef tierDay fill:#fff9c4,stroke:#fbc02d,stroke-width:1px,rx:5,ry:5;
    classDef weekLabel fill:#c62828,stroke:#fff,stroke-width:0px,color:#fff,font-weight:bold,rx:5,ry:5;
    classDef tierLabel fill:#fbc02d,stroke:#fff,stroke-width:0px,color:#000,font-weight:bold,rx:5,ry:5;

    %% Row 1: Week 10
    subgraph Week10 [Week 10: GREEDY & BACKTRACKING]
        direction LR
        W10_L[Week 10]:::weekLabel
        D10_1(Greedy):::day --> D10_2(Backtracking I):::day
        D10_2 --> D10_3(Backtracking II):::day
        D10_3 --> D10_4(Pruning & Optimization):::day
        D10_4 --> D10_5(Divide and Conquer):::day
    end

    %% Row 2: Week 11
    subgraph Week11 [Week 11: Dynamic Programming]
        direction LR
        W11_L[Week 11]:::weekLabel
        D11_1(DP Philosophy):::day --> D11_2(1D DP):::day
        D11_2 --> D11_3(Classic Patterns / knapsack):::day
        D11_3 --> D11_4(2D/Sequence DP):::day
        D11_4 --> D11_5(Advanced DP):::day
    end

    %% Row 3: Week 12
    subgraph Week12 [Week 12: Interview Mastery & Integration]
        direction LR
        W12_L[Week 12]:::weekLabel
        D12_1(Merge Intervals):::day --> D12_2(Adv Mono Stack):::day
        D12_2 --> D12_3(Cyclic Sort):::day
        D12_3 --> D12_4(Adv Matrix Problems):::day
        D12_4 --> D12_5(System Review & Integration):::day
    end

    %% Row 4: Week 13+ (Tier 3)
    subgraph Week13 [Week 13+: GOOD-TO-KNOW PROBLEM-SOLVING PATTERNS]
        direction LR
        W13_L[🚀 TIER 3]:::tierLabel
        T3_1(Fast & Slow Pointers Extended):::tierDay --> T3_2(Reverse & Two Pointers):::tierDay
        T3_2 --> T3_3(Matrix Traversal):::tierDay
        T3_3 --> T3_4(Conversion & Encoding):::tierDay
    end

    Week10 --> Week11 --> Week12 --> Week13
```

<!-- ![visual map summary](Assests/visual_summary.png)

![Phase 1](Assests/phase1_roadmap.png)

![Phase 2](Assests/phase2_roadmap.png)

![Phase 3](Assests/phase3_roadmap.png)

![Phase 4](Assests/phase4_roadmap.png)

![Phase 5](Assests/phase5_roadmap.png) -->

---

## 🚦 Progress Tracker

**Current Status:** `Week 0`

**Patterns Mastered:** `0 / 40`

`[░░░░░░░░░░░░░░░░░░░░] 0% Complete`

---

## 📚 The Curriculum

### 🟢 Phase 1: The Bedrock (Weeks 1-3)

*Focus: RAM Model, Big-O, and Linear Data Structures.*

<details>
<summary><strong>Week 1: Foundations & Complexity</strong></summary>

| Day | Topic | Focus | Status |
| --- | --- | --- | --- |
| **Mon** | 🧠 RAM Model & Pointers | Stack vs Heap, References in C# | [ ] |
| **Tue** | 📉 Asymptotic Analysis | Big-O, Omega, Theta | [ ] |
| **Wed** | 📦 Space Complexity | Stack Frames, Aux Space | [ ] |
| **Thu** | 🔄 Recursion I | Base cases, Visualization | [ ] |
| **Fri** | 🔄 Recursion II | Tail recursion, Tree recursion | [ ] |

</details>

<details>
<summary><strong>Week 2: Linear Structures</strong></summary>

| Day | Topic | Focus | Status |
| --- | --- | --- | --- |
| **Mon** | 🚃 Arrays & Strings | Cache locality, `Span<T>` | [ ] |
| **Tue** | 🧱 Dynamic Arrays | `List<T>` resizing logic | [ ] |
| **Wed** | 🔗 Linked Lists | Generic `LinkedList<T>` | [ ] |
| **Thu** | 🥞 Stacks & Queues | LIFO/FIFO, Monotonic conceptual | [ ] |
| **Fri** | 🔍 Binary Search | `O(log n)` reduction | [ ] |

</details>

<details>
<summary><strong>Week 3: Sorting & Hashing</strong></summary>

| Day | Topic | Focus | Status |
| --- | --- | --- | --- |
| **Mon** | 🧼 Elementary Sorts | Bubble/Insertion (Why they are slow) | [ ] |
| **Tue** | ⚡ Merge & Quick Sort | Divide & Conquer mechanics | [ ] |
| **Wed** | 🔑 Hash Tables I | Collision Theory, Load Factor | [ ] |
| **Thu** | 🗝️ Hash Tables II | `Dictionary<K,V>` internals | [ ] |
| **Fri** | 🧩 Review & Integration | Combining Sort + Hash | [ ] |

</details>

---

### 🔵 Phase 2: Patterns & Hierarchies (Weeks 4-5.5)

*Focus: The "Big 5" Patterns and Tree structures.*

<details>
<summary><strong>Week 4: Essential Patterns</strong></summary>

| Day | Topic | ROI | Status |
| --- | --- | --- | --- |
| **Mon** | 👉 Two Pointers | ⭐⭐⭐⭐⭐ | [ ] |
| **Tue** | 🪟 Sliding Window (Fixed) | ⭐⭐⭐⭐⭐ | [ ] |
| **Wed** | 🐛 Sliding Window (Var) | ⭐⭐⭐⭐⭐ | [ ] |
| **Thu** | 🔢 Prefix Sums | ⭐⭐⭐ | [ ] |
| **Fri** | 🐢 Fast & Slow Pointers | ⭐⭐⭐ | [ ] |

</details>

<details open>
<summary><strong>🔥 Week 4.5: TIER 1 - CRITICAL PATTERNS</strong></summary>
<em>These patterns solve 70% of interview questions. Do not skip.</em>

| Pattern | Usage Frequency | Key Use Case | Status |
| --- | --- | --- | --- |
| **Hash Map Pattern** | 70% | Two Sum, Frequency Counts | [ ] |
| **Monotonic Stack** | 30% | Next Greater Element | [ ] |
| **Merge Operations** | 30% | Merging sorted lists | [ ] |
| **Partitioning** | 15% | Move Zeroes, QuickSelect | [ ] |
| **Kadane's Algo** | 10% | Max Subarray Sum | [ ] |

</details>

<details>
<summary><strong>Week 5: Trees & Heaps</strong></summary>

| Day | Topic | Focus | Status |
| --- | --- | --- | --- |
| **Mon** | 🌳 Binary Tree Anatomy | Node structure, Depth vs Height | [ ] |
| **Tue** | 🚶 Tree Traversals | In/Pre/Post/Level Order | [ ] |
| **Wed** | 🔍 BST Operations | Search, Insert, Delete | [ ] |
| **Thu** | 🗻 Heaps (PriorityQueue) | Min-Heap properties | [ ] |
| **Fri** | ⚖️ Balanced Trees | AVL/Red-Black concepts | [ ] |

</details>

<details>
<summary><strong>⚡ Week 5.5: TIER 2 - STRATEGIC PATTERNS</strong></summary>

| Pattern | Usage Frequency | Key Use Case | Status |
| --- | --- | --- | --- |
| **Difference Array** | 15% | Range Updates (Booking) | [ ] |
| **In-Place Ops** | 12% | Array Manipulation | [ ] |
| **Deque Window** | 10% | Sliding Window Max | [ ] |

</details>

---

### 🟣 Phase 3: Connectivity (Weeks 6-7)

*Focus: Graphs, Networking, and Relationships.*

<details>
<summary><strong>Week 6: Graph Foundations</strong></summary>

| Day | Topic | Focus | Status |
| --- | --- | --- | --- |
| **Mon** | 🕸️ Graph Reps | Adjacency List vs Matrix | [ ] |
| **Tue** | 🌊 BFS (Shortest Path) | Queue-based traversal | [ ] |
| **Wed** | 🕵️ DFS (Exploration) | Stack/Recursion traversal | [ ] |
| **Thu** | 🏗️ Topological Sort | Dependency Resolution | [ ] |
| **Fri** | 🤝 Union-Find (DSU) | Connected Components | [ ] |

</details>

<details>
<summary><strong>Week 7: Advanced Graphs</strong></summary>

| Day | Topic | Focus | Status |
| --- | --- | --- | --- |
| **Mon** | ⚡ Dijkstra's Algo | Weighted Shortest Path | [ ] |
| **Tue** | 🔄 Bellman-Ford | Negative Weights | [ ] |
| **Wed** | 🌲 MST (Prim/Kruskal) | Network Design | [ ] |
| **Thu** | 🌊 Network Flow I | Max Flow Min Cut | [ ] |
| **Fri** | 🚢 Network Flow II | Bipartite Matching | [ ] |

</details>

---

### 🟠 Phase 4: Advanced & Math (Weeks 8-9)

*Focus: Indexing, Strings, and Number Theory.*

<details>
<summary><strong>Week 8: Specialized Indexing</strong></summary>

| Day | Topic | Status |
| --- | --- | --- |
| **Mon** | 🌲 Tries (Prefix Tree) | [ ] |
| **Tue** | 📏 Segment Trees I | [ ] |
| **Wed** | 📏 Segment Trees II | [ ] |
| **Thu** | 🌳 Fenwick Trees | [ ] |
| **Fri** | 🔤 Suffix Structures | [ ] |

</details>

<details>
<summary><strong>Week 9: String & Math</strong></summary>

| Day | Topic | Status |
| --- | --- | --- |
| **Mon** | 🧵 KMP Algorithm | [ ] |
| **Tue** | 🧵 Rabin-Karp | [ ] |
| **Wed** | 🔢 Number Theory | [ ] |
| **Thu** | 📐 Computational Geometry | [ ] |
| **Fri** | 🎲 Probability/Reservoir | [ ] |

</details>

---

### 🔴 Phase 5: Paradigms (Weeks 10-11)

*Focus: Meta-strategies for problem solving.*

<details>
<summary><strong>Week 10: Greedy & Backtracking</strong></summary>

| Day | Topic | Status |
| --- | --- | --- |
| **Mon** | 🤑 Greedy Paradigm | [ ] |
| **Tue** | 🔙 Backtracking I | [ ] |
| **Wed** | 🔙 Backtracking II | [ ] |
| **Thu** | ✂️ Pruning Strategies | [ ] |
| **Fri** | ⚔️ Divide & Conquer | [ ] |

</details>

<details>
<summary><strong>Week 11: Dynamic Programming</strong></summary>

| Day | Topic | Status |
| --- | --- | --- |
| **Mon** | 📝 Memoization vs Tabulation | [ ] |
| **Tue** | 🪜 1D DP (Linear) | [ ] |
| **Wed** | 🎒 Classic Patterns (Knapsack) | [ ] |
| **Thu** | 🧊 2D/Grid DP | [ ] |
| **Fri** | 🌳 DP on Trees | [ ] |

</details>

---

### 👑 Phase 6: Mastery & Tiers (Week 12+)

*Focus: Hard problems and specialized patterns.*

<details>
<summary><strong>Week 12: Integration Capstone</strong></summary>

| Day | Topic | Status |
| --- | --- | --- |
| **Mon** | 📅 Merge Intervals | [ ] |
| **Tue** | 🥞 Advanced Monotonic Stack | [ ] |
| **Wed** | 🔁 Cyclic Sort | [ ] |
| **Thu** | 🌀 Matrix Traversal | [ ] |
| **Fri** | 🎓 System Integration | [ ] |

</details>

<details>
<summary><strong>🚀 Week 13+: TIER 3 - SPECIALIST PATTERNS</strong></summary>

| Pattern | Usage Frequency | Key Use Case | Status |
| --- | --- | --- | --- |
| **Fast & Slow (Ext)** | 5% | Palindrome List | [ ] |
| **Reverse & Merge** | 8% | Rotate Array | [ ] |
| **Matrix Spirals** | 5% | Simulation | [ ] |
| **Encoding** | 3% | Compression | [ ] |

</details>

---

## 🎒 Resource Kit

**Tools:**

* [VisualAlgo](https://visualgo.net/en) - Visualization
* [Big-O Cheat Sheet](https://www.bigocheatsheet.com/)
* [Excalidraw](https://excalidraw.com/) - For whiteboarding

**Legend:**

* 💻 Practice Problem
* 🧠 Concept Deep Dive
* ⚔️ Challenge
* ⚠️ Common Pitfall

---

*Created with the DSA Master Instructor Framework.*

```

```