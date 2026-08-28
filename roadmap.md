# Roadmap — All-Time-Great CP Syllabus

Read `context.md` first. This file is the **full topic list** and **year overview**. It is complete on purpose. We will **not** finish it in one year. Weekly Codeforces sets walk it from the top, topic by topic, and only move when Toffy’s report says the topic is deep enough.

**Problems: Codeforces only.** Use the CF tags on each topic when picking.

---

## How any agent uses this file

1. Look at **Current position** below (and `weeks/` if those files exist).
2. Stay on that topic (or the next one, if last week’s report said he’s ready).
3. Assign 8–15 CF problems on **that topic**, easy → harder, sized for 2–3 hours/day.
4. Do **not** skip ahead because LeetCode is strong. Do **not** dump a billion problems on one topic.
5. After a good report, tick the topic in the progress table and move the pointer.
6. Mixed-review weeks are allowed only as an explicit “review” week, not as the default.

**Deep enough (default):** he can take a new CF problem of that type in the week’s rating band and solve it without the topic feeling fake. Depth over count. If he struggled, stay or drop rating. If it was easy, step rating or advance the pointer.

---

## Current position

| Field | Value |
| --- | --- |
| Date started | 2026-08-23 |
| Phase | 0 — CF literacy |
| Topic id | `T00` |
| Rating band | ~800–1000 |
| Week 1 | assigned 2026-08-28 (`weeks/001-week.md`) — waiting on report |
| Last report | none |

Update this table whenever a week is closed.

---

## Year overview (what we’ll try)

Horizon: ~1 year from 2026-08-23. ~14–21 hours/week. Report-driven, not calendar-driven.

This is a **ground-up rebuild** on Codeforces, even though the standard LeetCode topics are already familiar. CF statements, constraints, constructive, and unusual setups are new muscle.

### What “a good year” looks like

We **try** to walk as far as the brain will go. Honest bands:

| If the year goes… | Likely reach | Rough CF comfort* |
| --- | --- | --- |
| Solid | through **Phase 6** (Trees I) and well into **Phase 7** (DP I) | ~1400–1700 tagged problems |
| Strong | **Phase 8–9** (strings I, range DS I) | ~1700–2000 |
| Monster | **Phase 10–12** and taste of later | 2000+ on some tags |

\*Comfort ≠ official rating. We are not optimizing rating. Live contests are optional.

Phases **13–18** stay in this file so we never run out and so the syllabus is actually “greatest CP-er,” not a 12-month trim.

### Phase map (walk in this order)

| Phase | Name | Why this order |
| --- | --- | --- |
| 0 | CF literacy & implementation | How CF problems feel |
| 1 | Array techniques | Everyday contest tools |
| 2 | Sort, search, greedy | Classic Div2 bread |
| 3 | Complete search | When brute / recurse is the skill |
| 4 | Bits & math I | Numbers, mods, counting |
| 5 | Graphs I | Connectivity, paths, DSU, MST |
| 6 | Trees I | Trees as graphs + LCA |
| 7 | DP I | The big skill jump |
| 8 | Strings I | Hash / automata-lite |
| 9 | Range data structures I | Fenwick / seg / sqrt |
| 10 | Graphs II | SCC, bridges, flow, matching |
| 11 | Trees II | HLD, centroids, virtual trees |
| 12 | DP II | Optimizations, SOS, reroot |
| 13 | Math II | NT heavy, matrices, FFT |
| 14 | Geometry I–II | From primitives to hull/sweep |
| 15 | Strings II | Suffix structures, Aho |
| 16 | Advanced DS | Treaps, persistent, LCT |
| 17 | Games, interactive, hard constructive | Contest spices |
| 18 | God-tier / World Finals rare | So the list is complete |

Do not start a later phase because it looks cool. Exceptions: a stretch problem at the bottom of a week is fine.

---

## How to pick a weekly CF set

For the current topic id:

1. Open `https://codeforces.com/problemset?tags=<tag>` (tags listed on the topic).
2. Sort by difficulty. Start at the **bottom of the current band**, then step up.
3. Prefer problems that **teach one idea** of this topic. Avoid multi-topic monsters until a review week.
4. Mix: a few “I already kind of know this from LeetCode” warmups + a few that force CF-style thinking (constructive, tight constraints, ugly implementation).
5. Mark 1–3 as **stretch** (optional).
6. Always write: CF id, URL, topic id, tag, rough rating, 1-line why.

Default bands (raise when reports are clean):

| Phase | Default band |
| --- | --- |
| 0–2 | 800–1200, stretch to 1400 |
| 3–5 | 1000–1600, stretch to 1800 |
| 6–8 | 1400–1900, stretch to 2100 |
| 9+ | 1600–2200+, stretch as needed |

---

## Progress table

Tick when a topic is **deep enough** (from the weekly report), not when it was assigned.

| Id | Topic | Phase | Done? |
| --- | --- | --- | --- |
| T00 | CF literacy, constraints, implementation | 0 | |
| T01 | Simulation, ad-hoc, casework | 0 | |
| T02 | Constructive algorithms (easy → medium) | 0 | |
| T03 | Prefix sums & difference arrays | 1 | |
| T04 | Two pointers & sliding window | 1 | |
| T05 | Coordinate compression & MEX | 1 | |
| T06 | Sorting & custom order | 2 | |
| T07 | Binary search (array + on answer) | 2 | |
| T08 | Ternary search | 2 | |
| T09 | Greedy (intervals, exchange, PQ) | 2 | |
| T10 | Brute force & careful enumeration | 3 | |
| T11 | Recursion, backtracking, subsets | 3 | |
| T12 | Meet in the middle | 3 | |
| T13 | Bitwise ops & bitmasks as sets | 4 | |
| T14 | GCD, LCM, Euclidean | 4 | |
| T15 | Primes, sieve, factorization | 4 | |
| T16 | Modular arithmetic & fast pow | 4 | |
| T17 | Combinatorics I (nCr, pigeon, IE intro) | 4 | |
| T18 | Graph representation, DFS, BFS | 5 | |
| T19 | Components, bipartite, cycles, flood fill | 5 | |
| T20 | Toposort & DAGs | 5 | |
| T21 | Shortest paths | 5 | |
| T22 | DSU | 5 | |
| T23 | MST | 5 | |
| T24 | Functional graphs | 5 | |
| T25 | Trees: basics, diameter, reroot thinking | 6 | |
| T26 | Binary lifting & LCA | 6 | |
| T27 | Euler tour on trees | 6 | |
| T28 | DP I: 1D, knapsack, LIS | 7 | |
| T29 | DP I: grids, intervals | 7 | |
| T30 | DP I: bitmasks, digits, DAG | 7 | |
| T31 | String hashing | 8 | |
| T32 | Prefix function, Z, KMP | 8 | |
| T33 | Manacher, tries | 8 | |
| T34 | Sparse table | 9 | |
| T35 | Fenwick (BIT) | 9 | |
| T36 | Segment tree (point update) | 9 | |
| T37 | Lazy segment tree | 9 | |
| T38 | Sqrt decomposition & Mo | 9 | |
| T39 | SCC, condensation | 10 | |
| T40 | Bridges, articulation, BCC | 10 | |
| T41 | 2-SAT | 10 | |
| T42 | Euler path / circuit | 10 | |
| T43 | Max flow, min cut | 10 | |
| T44 | Bipartite matching | 10 | |
| T45 | Min-cost max flow | 10 | |
| T46 | HLD | 11 | |
| T47 | Centroid decomposition | 11 | |
| T48 | Virtual trees, small-to-large | 11 | |
| T49 | Kruskal reconstruction tree | 11 | |
| T50 | Tree DP & rerooting | 12 | |
| T51 | SOS DP | 12 | |
| T52 | CHT, Li Chao | 12 | |
| T53 | D&C DP, Knuth, Alien | 12 | |
| T54 | Modular inverse, phi, CRT | 13 | |
| T55 | Mobius, Dirichlet, multiplicative | 13 | |
| T56 | Discrete log, primitive roots | 13 | |
| T57 | Matrices, Gaussian elim | 13 | |
| T58 | Probability & expectation | 13 | |
| T59 | FFT / NTT / generating functions | 13 | |
| T60 | Geometry primitives | 14 | |
| T61 | Convex hull, rotating calipers | 14 | |
| T62 | Sweep line, closest pair | 14 | |
| T63 | Half-plane, Minkowski | 14 | |
| T64 | Suffix array / LCP | 15 | |
| T65 | Suffix automaton / suffix tree | 15 | |
| T66 | Aho-Corasick, palindromic tree | 15 | |
| T67 | Treaps / splay / implicit keys | 16 | |
| T68 | Persistent segment trees | 16 | |
| T69 | Link-cut, Euler-tour trees | 16 | |
| T70 | Impartial games, Grundy | 17 | |
| T71 | Interactive problems | 17 | |
| T72 | Hard constructive | 17 | |
| T73 | Parallel binary search, CDQ | 18 | |
| T74 | General matching, matroids | 18 | |
| T75 | Wavelet, Li Chao extras, 2D DS | 18 | |
| T76 | Rare WF: planar, chordal, heavy math | 18 | |

---

## Syllabus (detail)

Each topic: what it is, CF tags, subskills, what “deep enough” means, picker notes.

---

### Phase 0 — CF literacy & implementation

The point is not “can he code.” It’s “can he read a CF problem, trust constraints, and implement the ugly thing without melting.”

#### T00 — CF literacy, constraints, implementation

- **CF tags:** `implementation`
- **Subskills:** reading statements; samples as contracts; constraint → algorithm class; 32-bit overflow; 1- vs 0-index; off-by-one; multiple test cases; output format; time/memory gut (`1e8` ops-ish).
- **Deep enough:** he looks at `n`, `t`, and limits and already knows what is allowed; he stops dying on “easy but annoying” I/O.
- **Picker:** 800–1000 implementation. Avoid needing graphs/DP.

#### T01 — Simulation, ad-hoc, casework

- **CF tags:** `implementation`, `brute force`
- **Subskills:** simulate the process; split cases; don’t force a fancy algorithm; debug on small cases.
- **Deep enough:** he can finish a messy simulate/ad-hoc without inventing unused theory.
- **Picker:** problems that look ugly and are actually “just do what it says.”

#### T02 — Constructive algorithms (easy → medium)

- **CF tags:** `constructive algorithms`
- **Subskills:** build an example that satisfies constraints; patterns; “always possible except…”; greedy construction.
- **Deep enough:** he stops staring and starts proposing a shape (repeat a block, pair odds, etc.).
- **Picker:** classic Div2 A/B constructives first, then 1200–1400.

---

### Phase 1 — Array techniques

#### T03 — Prefix sums & difference arrays

- **CF tags:** `implementation`, `data structures`, `greedy` (sometimes)
- **Subskills:** 1D prefix; range sum; difference array for range add; 2D prefix; max-subarray as prefix trick.
- **Deep enough:** range-sum / range-add on a static array is automatic.
- **Picker:** start 800–1200; include at least one 2D or difference-array problem if the easy ones were trivial.

#### T04 — Two pointers & sliding window

- **CF tags:** `two pointers`
- **Subskills:** opposite-end pointers; same-direction window; invariant; when it fails.
- **Deep enough:** he can say the invariant out loud and why each pointer only moves forward.
- **Picker:** CF `two pointers` 800–1400. Skip graph/DP hybrids.

#### T05 — Coordinate compression & MEX

- **CF tags:** `sortings`, `data structures`
- **Subskills:** map big values to `0..k`; offline unique; MEX of a set / array tricks.
- **Deep enough:** big `a_i` no longer scares him into “I need a 1e9 array.”
- **Picker:** problems that are easy *after* compression.

---

### Phase 2 — Sort, search, greedy

#### T06 — Sorting & custom order

- **CF tags:** `sortings`
- **Subskills:** sort pairs; sort by key; stability intuition; when sort enables greedy.
- **Deep enough:** he picks the right key without flailing.
- **Picker:** 800–1300 `sortings`.

#### T07 — Binary search (array + on answer)

- **CF tags:** `binary search`
- **Subskills:** lower/upper bound; search on monotonic predicate; “binary search the answer”; off-by-one discipline; parametric search intuition.
- **Deep enough:** he can define `ok(x)` and prove monotonicity (or know when he can’t).
- **Picker:** mix classic array BS and “BS on answer” 1000–1600.

#### T08 — Ternary search

- **CF tags:** `ternary search`
- **Subskills:** unimodal functions; when ternary vs binary; integer vs real; precision.
- **Deep enough:** he only uses it when the function is actually unimodal.
- **Picker:** fewer problems; this topic is thin. 5–8 is enough.

#### T09 — Greedy (intervals, exchange, PQ)

- **CF tags:** `greedy`
- **Subskills:** interval scheduling; earliest deadline; Huffman-style PQ; exchange argument vibe; counterexamples when greedy dies.
- **Deep enough:** he can argue “if I swap these two, I don’t lose” or show a fail case.
- **Picker:** 1000–1600 `greedy`. Avoid DP-labelled greeds until Phase 7.

---

### Phase 3 — Complete search

#### T10 — Brute force & careful enumeration

- **CF tags:** `brute force`
- **Subskills:** estimate `n!`, `2^n`, `n^2`; prune; iterate the smaller side.
- **Deep enough:** he knows when brute is the intended solution.
- **Picker:** 800–1400 where constraints scream brute.

#### T11 — Recursion, backtracking, subsets

- **CF tags:** `brute force`, `bitmasks`, `dfs and similar`
- **Subskills:** subsets, permutations, prune, recursion tree.
- **Deep enough:** he can generate/search without blowing the stack or revisiting junk.
- **Picker:** 1000–1600. Keep n small.

#### T12 — Meet in the middle

- **CF tags:** `meet-in-the-middle`
- **Subskills:** split n~40; two half-enumerations; combine.
- **Deep enough:** he recognizes `2^{n/2}` as the move.
- **Picker:** few problems; quality over count.

---

### Phase 4 — Bits & math I

#### T13 — Bitwise ops & bitmasks as sets

- **CF tags:** `bitmasks`, `math`
- **Subskills:** and/or/xor; shifts; popcount; iterate submasks (later SOS is T51); bit DP preview only.
- **Deep enough:** bits are a set, xor is a toggle, he doesn’t fear masks.
- **Picker:** 800–1500 `bitmasks`. Save SOS / TSP DP for later.

#### T14 — GCD, LCM, Euclidean

- **CF tags:** `math`, `number theory`
- **Subskills:** gcd properties; gcd in arrays; linear Diophantine intro (`ax+by=c`).
- **Deep enough:** gcd facts are tools, not trivia.
- **Picker:** 800–1400 number theory that is mostly gcd.

#### T15 — Primes, sieve, factorization

- **CF tags:** `number theory`
- **Subskills:** sieve of Eratosthenes; SPF; factor `n` in `O(sqrt n)`; prime checks.
- **Deep enough:** he factors and sieves without copying a blob he doesn’t understand.
- **Picker:** 1000–1600.

#### T16 — Modular arithmetic & fast pow

- **CF tags:** `math`, `number theory`
- **Subskills:** add/sub/mul mod; binary exponentiation; overflow-safe mul intuition; **not** a C++ lecture — just the math.
- **Deep enough:** `(a*b)%mod` and `a^b mod m` are boring.
- **Picker:** 800–1500. Inverses wait for T54 unless a problem needs them and he’s ready.

#### T17 — Combinatorics I

- **CF tags:** `combinatorics`, `math`
- **Subskills:** nCr / factorial (mod later); pigeonhole; stars-and-bars vibe; inclusion-exclusion **intro** (2–3 sets).
- **Deep enough:** he can count without guessing.
- **Picker:** 1000–1700 `combinatorics`. Hard IE / Mobius → T55.

---

### Phase 5 — Graphs I

#### T18 — Graph representation, DFS, BFS

- **CF tags:** `graphs`, `dfs and similar`
- **Subskills:** adj list; directed vs undirected; recursion DFS vs stack; BFS layers; implicit graphs (grids).
- **Deep enough:** he builds a graph from a statement without panic.
- **Picker:** 800–1400. Lots of “this is secretly a graph.”

#### T19 — Components, bipartite, cycles, flood fill

- **CF tags:** `graphs`, `dfs and similar`
- **Subskills:** CC / SCC later; 2-color; cycle find; grid flood.
- **Deep enough:** “connected?”, “odd cycle?”, “region count?” are automatic.
- **Picker:** 1000–1600.

#### T20 — Toposort & DAGs

- **CF tags:** `graphs`, `dfs and similar`
- **Subskills:** Kahn; DFS toposort; DP-on-DAG preview.
- **Deep enough:** he spots a DAG and an order.
- **Picker:** 1200–1700.

#### T21 — Shortest paths

- **CF tags:** `shortest paths`, `graphs`
- **Subskills:** BFS = unweighted; 0-1 BFS; Dijkstra; Bellman-Ford / neg cycles; Floyd-Warshall; when which.
- **Deep enough:** he picks the right SP algorithm from constraints.
- **Picker:** one cluster per algorithm, 1200–1900.

#### T22 — DSU

- **CF tags:** `dsu`
- **Subskills:** union by rank/size; path compression; offline connectivity; DSU on queries.
- **Deep enough:** “merge components / offline edges” → DSU.
- **Picker:** 1300–1900 `dsu`.

#### T23 — MST

- **CF tags:** `graphs`
- **Subskills:** Kruskal + DSU; Prim; MST properties (cut / cycle).
- **Deep enough:** he knows why the greedy tree is optimal and can use MST as a tool (min max-edge, etc.).
- **Picker:** 1300–1900.

#### T24 — Functional graphs

- **CF tags:** `graphs`, `dfs and similar`
- **Subskills:** each node outdegree 1; cycle + trees into cycle; tortoise-hare as optional.
- **Deep enough:** he draws the “rho” and answers path/cycle queries.
- **Picker:** 1400–1900.

---

### Phase 6 — Trees I

#### T25 — Trees: basics, diameter, reroot thinking

- **CF tags:** `trees`
- **Subskills:** n-1 edges; unique paths; two-BFS diameter; heights; “reroot in your head” (full reroot DP is T50).
- **Deep enough:** a tree is not “a scary graph.”
- **Picker:** 1200–1800 `trees`.

#### T26 — Binary lifting & LCA

- **CF tags:** `trees`
- **Subskills:** jump pointers; LCA; path aggregates if static; k-th ancestor.
- **Deep enough:** LCA is a primitive, not a whole week of confusion.
- **Picker:** 1500–2000.

#### T27 — Euler tour on trees

- **CF tags:** `trees`, `data structures`
- **Subskills:** flatten subtree to range; then later hook to Fenwick/seg (Phase 9).
- **Deep enough:** subtree ↔ segment is obvious.
- **Picker:** 1600–2100. If range DS isn’t there yet, pick tours that don’t need a segtree, or wait until T36 and come back — prefer **stay in order** and pick tour problems that only need the flatten idea.

---

### Phase 7 — DP I

He “knows DP” from LeetCode. Rebuild it in CF style anyway.

#### T28 — DP I: 1D, knapsack, LIS

- **CF tags:** `dp`
- **Subskills:** state / transition / order; 0-1 / unbounded knapsack; LIS (`n log n` later ok); LCS as optional.
- **Deep enough:** he writes the state before the code.
- **Picker:** 1000–1700 classic CF DP. Not AtCoder Educational — CF only.

#### T29 — DP I: grids, intervals

- **CF tags:** `dp`
- **Subskills:** grid paths; interval DP (matrix-chain shape); divide interval.
- **Deep enough:** he can draw the interval table.
- **Picker:** 1400–1900.

#### T30 — DP I: bitmasks, digits, DAG

- **CF tags:** `dp`, `bitmasks`
- **Subskills:** TSP-style; digit DP; DP on DAG (ties T20).
- **Deep enough:** mask/digit/DAG each have one “I could do this again” solve.
- **Picker:** 1600–2100. Don’t assign Knuth/CHT here.

---

### Phase 8 — Strings I

#### T31 — String hashing

- **CF tags:** `hashing`, `strings`
- **Subskills:** polynomial hash; collision reality; double hash; substring hash via prefix.
- **Deep enough:** he can compare substrings in O(1) and knows it’s probabilistic.
- **Picker:** 1400–2000 `hashing`.

#### T32 — Prefix function, Z, KMP

- **CF tags:** `strings`
- **Subskills:** π-array; Z-array; pattern search; prefix-suffix tricks.
- **Deep enough:** he knows what π[i] means and can use it, not only paste KMP.
- **Picker:** 1500–2100.

#### T33 — Manacher, tries

- **CF tags:** `strings`
- **Subskills:** palindromes in O(n); trie insert/search; xor-trie preview ok.
- **Deep enough:** one solid Manacher or palindrome set + one trie set.
- **Picker:** 1600–2200. Thin topic — don’t pad.

---

### Phase 9 — Range data structures I

#### T34 — Sparse table

- **CF tags:** `data structures`
- **Subskills:** idempotent range queries (min/gcd); static.
- **Deep enough:** RMQ is O(1) after O(n log n).
- **Picker:** 1500–2000.

#### T35 — Fenwick (BIT)

- **CF tags:** `data structures`
- **Subskills:** point add, prefix sum; inversion count; order tricks.
- **Deep enough:** he can write it and know what each index means.
- **Picker:** 1500–2100.

#### T36 — Segment tree (point update)

- **CF tags:** `data structures`
- **Subskills:** build/query/update; merge function; walking the tree.
- **Deep enough:** a custom merge (max + count, gcd, etc.) doesn’t freeze him.
- **Picker:** 1600–2200.

#### T37 — Lazy segment tree

- **CF tags:** `data structures`
- **Subskills:** range add/assign; push; composition of lazy.
- **Deep enough:** he can push without corrupting the tree.
- **Picker:** 1800–2400. Stay until the report is clean — this one is allowed to take more than one week.

#### T38 — Sqrt decomposition & Mo

- **CF tags:** `data structures`
- **Subskills:** block arrays; Mo’s order; add/remove; Hilbert optional.
- **Deep enough:** he knows when sqrt/Mo beats a segtree (or is easier).
- **Picker:** 1800–2400.

---

### Phase 10 — Graphs II

#### T39 — SCC, condensation

- **CF tags:** `graphs`, `dfs and similar`
- **Subskills:** Kosaraju / Tarjan; DAG of SCCs.
- **Deep enough:** “strongly connected” and “condense then DP” are available.
- **Picker:** 1700–2300.

#### T40 — Bridges, articulation, BCC

- **CF tags:** `graphs`
- **Subskills:** tin/low; edge-biconnected; block-cut tree intro.
- **Deep enough:** he can find bridges/points and use them.
- **Picker:** 1800–2400.

#### T41 — 2-SAT

- **CF tags:** `2-sat`, `graphs`
- **Subskills:** implication graph; SCC; assignment.
- **Deep enough:** he models boolean constraints as 2-SAT.
- **Picker:** 1900–2500. Few, sharp.

#### T42 — Euler path / circuit

- **CF tags:** `graphs`
- **Subskills:** Hierholzer; undirected vs directed degrees.
- **Deep enough:** he knows the degree conditions and can build the path.
- **Picker:** 1700–2200.

#### T43 — Max flow, min cut

- **CF tags:** `flows`
- **Subskills:** residual; Dinic / better-than-FF; min-cut meaning; modeling (source/sink gadgets).
- **Deep enough:** he can model a flow, not only run a template.
- **Picker:** 2000–2700 `flows`. Modeling > code golf.

#### T44 — Bipartite matching

- **CF tags:** `graph matchings`
- **Subskills:** Kuhn; König; min vertex cover = max matching; Hopcroft-Karp awareness.
- **Deep enough:** matching is a modeling tool.
- **Picker:** 1900–2600.

#### T45 — Min-cost max flow

- **CF tags:** `flows`
- **Subskills:** potentials / SPFA-in-MCMF; when cost + capacity is the model.
- **Deep enough:** one real MCMF model he could rebuild.
- **Picker:** few problems. 2200+.

---

### Phase 11 — Trees II

#### T46 — Heavy-light decomposition

- **CF tags:** `trees`, `data structures`
- **Subskills:** heavy/light; path query via chains + segtree.
- **Deep enough:** path/subtree queries are a known recipe.
- **Picker:** 2100–2700. Multi-week ok.

#### T47 — Centroid decomposition

- **CF tags:** `trees`
- **Subskills:** centroid; decompose; paths through centroid.
- **Deep enough:** “count paths with property X” → centroid is on the menu.
- **Picker:** 2200–2800.

#### T48 — Virtual trees, small-to-large

- **CF tags:** `trees`, `data structures`
- **Subskills:** compress key nodes; sack / dsu-on-tree.
- **Deep enough:** he recognizes both patterns.
- **Picker:** 2200–2800.

#### T49 — Kruskal reconstruction tree

- **CF tags:** `trees`, `dsu`
- **Subskills:** build tree from Kruskal; min-max edge queries become LCA.
- **Deep enough:** he can explain why it works.
- **Picker:** few, 2300+.

---

### Phase 12 — DP II

#### T50 — Tree DP & rerooting

- **CF tags:** `dp`, `trees`
- **Subskills:** subtree DP; reroot all-roots; combine children.
- **Deep enough:** two-pass / reroot is a method, not a miracle.
- **Picker:** 1800–2500.

#### T51 — SOS DP

- **CF tags:** `dp`, `bitmasks`
- **Subskills:** sum over subsets; zeta/mobius on subset lattice.
- **Deep enough:** `for mask; for bit` iterate is understood.
- **Picker:** 2000–2600.

#### T52 — CHT, Li Chao

- **CF tags:** `dp`, `data structures`
- **Subskills:** convex hull trick; Li Chao tree; when slopes are sorted.
- **Deep enough:** he spots `min_j a_j*x + b_j`.
- **Picker:** 2100–2700.

#### T53 — D&C DP, Knuth, Alien

- **CF tags:** `dp`, `divide and conquer`
- **Subskills:** divide-and-conquer opt; Knuth-Yao; wqs / Alien trick.
- **Deep enough:** he knows the *conditions* (quadrangle, etc.), not just names.
- **Picker:** few legendary problems. 2300+.

---

### Phase 13 — Math II

#### T54 — Modular inverse, phi, CRT

- **CF tags:** `number theory`
- **Subskills:** inv via phi / ext Euclid; Euler’s totient; Chinese Remainder.
- **Deep enough:** inverses and CRT are tools.
- **Picker:** 1600–2300.

#### T55 — Mobius, Dirichlet, multiplicative

- **CF tags:** `number theory`
- **Subskills:** μ; inversion; Dirichlet convolution; linear sieve of functions.
- **Deep enough:** he can invert a sum over divisors.
- **Picker:** 2000–2700.

#### T56 — Discrete log, primitive roots

- **CF tags:** `number theory`
- **Subskills:** baby-step giant-step; primitive root existence; order.
- **Deep enough:** one BSGS he could redo.
- **Picker:** rare. Don’t pad.

#### T57 — Matrices, Gaussian elim

- **CF tags:** `matrices`, `math`
- **Subskills:** matrix expo for recurrences; Gauss-Jordan; xor-basis / linear basis.
- **Deep enough:** linear recurrences and xor-span are normal.
- **Picker:** 1800–2500.

#### T58 — Probability & expectation

- **CF tags:** `probabilities`
- **Subskills:** linearity of expectation; expected DP; “probability as DP.”
- **Deep enough:** he uses linearity instead of expanding nightmares.
- **Picker:** 1700–2400.

#### T59 — FFT / NTT / generating functions

- **CF tags:** `fft`
- **Subskills:** convolution; NTT mods; simple GF.
- **Deep enough:** “this is a convolution” is the win, not a perfect impl from memory the first week.
- **Picker:** 2200–3000. Multi-week ok.

Also in the **math II orbit** (attach to the nearest topic, don’t make extra weeks unless needed): Miller-Rabin, Pollard Rho, Berlekamp-Massey, linear recurrence, quadratic residues. Assign if reports show he’s living here.

---

### Phase 14 — Geometry

#### T60 — Geometry primitives

- **CF tags:** `geometry`
- **Subskills:** points, vectors, cross/dot; orientation; segment intersect; area; integer geometry to avoid floats when possible.
- **Deep enough:** primitives are trusted.
- **Picker:** 1400–2000.

#### T61 — Convex hull, rotating calipers

- **CF tags:** `geometry`
- **Subskills:** monotone chain / Graham; diameter; tangents.
- **Deep enough:** hull is a tool.
- **Picker:** 1900–2600.

#### T62 — Sweep line, closest pair

- **CF tags:** `geometry`
- **Subskills:** events; status structure; closest pair D&C.
- **Deep enough:** he can design a sweep.
- **Picker:** 2000–2700.

#### T63 — Half-plane, Minkowski

- **CF tags:** `geometry`
- **Subskills:** half-plane intersection; Minkowski sum of hulls.
- **Deep enough:** names map to pictures.
- **Picker:** rare, 2400+.

---

### Phase 15 — Strings II

#### T64 — Suffix array / LCP

- **CF tags:** `string suffix structures`
- **Subskills:** SA construction awareness; LCP; distinct substrings; compare suffixes.
- **Deep enough:** he can use SA+LCP on a problem, not recite 5 construction papers.
- **Picker:** 2200–2800.

#### T65 — Suffix automaton / suffix tree

- **CF tags:** `string suffix structures`
- **Subskills:** SAM states; endpos; suffix links; “what SAM counts.”
- **Deep enough:** one SAM problem he fully gets.
- **Picker:** 2300–3000.

#### T66 — Aho-Corasick, palindromic tree, Lyndon

- **CF tags:** `strings`
- **Subskills:** multi-pattern; eertree; Lyndon factorization.
- **Deep enough:** multi-pattern → Aho is automatic.
- **Picker:** 2200–2900. Don’t force all three in one week.

---

### Phase 16 — Advanced DS

#### T67 — Treaps / splay / implicit keys

- **CF tags:** `data structures`
- **Subskills:** split/merge; implicit treap = array; sequences.
- **Deep enough:** he can split/merge with intent.
- **Picker:** 2200–3000.

#### T68 — Persistent segment trees

- **CF tags:** `data structures`
- **Subskills:** persist versions; k-th in range; offline → persist.
- **Deep enough:** “version the tree” is a reflex.
- **Picker:** 2300–3000.

#### T69 — Link-cut, Euler-tour trees

- **CF tags:** `data structures`
- **Subskills:** dynamic trees; link/cut path queries.
- **Deep enough:** he knows *when* LCT is the hammer. Implementation can take real time.
- **Picker:** very few. 2600+.

---

### Phase 17 — Games, interactive, hard constructive

#### T70 — Impartial games, Grundy

- **CF tags:** `games`
- **Subskills:** Nim; mex/grundy; sums of games.
- **Deep enough:** he can compute grundy and combine.
- **Picker:** 1600–2300.

#### T71 — Interactive problems

- **CF tags:** `interactive`
- **Subskills:** ask/answer protocol; binary-search interact; hide graph; flush discipline (language-agnostic: “the judge needs the question now”).
- **Deep enough:** he can design queries under a limit.
- **Picker:** 1200–2200 interactive. Can insert a light interactive earlier as a one-off stretch if he asks; default is wait until here.

#### T72 — Hard constructive

- **CF tags:** `constructive algorithms`
- **Subskills:** high-rated constructions; invariants; “build from the answer.”
- **Deep enough:** he enjoys these instead of fearing them.
- **Picker:** 2000–2800. Review-ish; uses all prior math/graph taste.

---

### Phase 18 — God-tier / World Finals rare

These exist so the syllabus is honest. Do not start here early.

#### T73 — Parallel binary search, CDQ

- **CF tags:** `binary search`, `divide and conquer`, `data structures`
- **Subskills:** PBS on many queries; CDQ D&C; offline 3D fenwick vibe.
- **Picker:** 2400+.

#### T74 — General matching, matroids

- **CF tags:** `graph matchings`
- **Subskills:** Blossom; matroid intersection awareness.
- **Picker:** extremely rare CF; assign only if we’re actually here.

#### T75 — Wavelet, extra Li Chao, 2D DS

- **CF tags:** `data structures`
- **Subskills:** wavelet tree; 2D fenwick/seg; sparse/dynamic seg.
- **Picker:** 2400+.

#### T76 — Rare WF: planar, chordal, heavy math

- **CF tags:** mixed (`graphs`, `math`, `fft`, `geometry`)
- **Subskills:** planar shortest paths / faces; chordal graphs; simplex-ish tricks; generatingfunctionology deep; optimization lore; anything tourist-week leftovers.
- **Picker:** only after a long, strong year. Individual CF gems, not a sheet.

---

## Cross-cutting (do not make these “Phase −1”)

These show up inside other topics. Name them so agents don’t invent a side quest.

| Skill | Where it lives |
| --- | --- |
| Observation / invariants | every phase; especially T02, T09, T72 |
| Proof / counterexample | T09, DP, greedy |
| Stress-test thinking | whenever WA; don’t turn the repo into a tester project unless Toffy asks |
| Complexity | T00, then always |
| Offline vs online | DSU, Mo, caches, PBS |
| Modeling (flow/matching/2-SAT) | Phase 10 |

---

## Sources this syllabus was checked against

Not homework. Just so another agent knows this wasn’t a vibe list:

- IOI Syllabus (included + the hard stuff IOI excludes but ICPC/CF still uses)
- ICPC Curriculum Committee course list (I–IV)
- USACO Guide bronze → platinum + advanced
- Codeforces problemset tags
- Typical cp-algorithms / e-maxx topic coverage
- Standard “red/orange+” extras: FFT, LCT, Alien, SAM, Mobius, MCMF

IOI excludes some of Phase 13–18 (FFT, heavy linear algebra, Sprague-Grundy as theory, etc.). **This roadmap includes them** because “greatest CF/ICPC-er” is wider than IOI.

---

## What we will not do in this file

- Language tutorials, STL courses, editor setup
- Quant interview tracks
- Non-CF problem links
- A fixed “week 17 = Dijkstra” calendar (reports move the pointer)
- Week 1 assignment (Toffy asks first)

When Toffy asks for Week 1: start at **T00**, band **800–1000**, tag `implementation`, 8–15 CF problems, plus a short report template. Then update **Current position**.
