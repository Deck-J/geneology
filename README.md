# Decker Family Genealogy

This repository contains a genealogical flowchart tracing the Decker family line from Isaac Decker (*1743 - ~1840) to Clifford Decker (1915 - , died in Gainesville, FL), including all known siblings and children along the direct lineage. The chart is generated using [Mermaid.js](https://mermaid-js.github.io/), which GitHub supports natively in Markdown. Data is sourced from the "webGED: DECKER FAMILIES Data Page" and supplemented by web searches, including obituary records.

## Family Line Flowchart

Below is the flowchart showing the descent from Isaac Decker to Clifford Decker. The direct line is highlighted with a thicker border and light purple fill. Each node includes the individual's name, birth/death years, and spouse (for the direct line). Siblings and children are included as branches off their parents. Additional findings, such as Brian Decker (1957 - ), are integrated from external sources.


```mermaid
graph TD
    A[Isaac Decker<br>*1743 - ~1840<br>m. Dorcas Chamberlain<br>~1750 - ]:::root --> B[Ebenezer<br>1771 - 1850]
    A --> C[John<br>1775 - 1854]
    A --> D[Eunice<br>1777 - >1850]
    A --> E[Christopher<br>*1780 - ]
    A --> F[Jacob Decker<br>~1784 - 1835<br>m. Elizabeth Irwin<br>~1785 - ]:::direct
    A --> G[Daniel<br>*1787 - 1840]

    F --> H[Mary M<br>1800 - 1889]
    F --> I[Robert<br>1805 - ]
    F --> J[Daniel Decker<br>1808 - 1887<br>m. Sara Martin<br>*1813 - 1885]:::direct
    F --> K[Nancy<br>*1809 - ]
    F --> L[Jacob<br>*1809 - ]
    F --> M[James K<br>*1810 - ]
    F --> N[John<br>1816 - 1860]
    F --> O[George<br>*1817 - ]
    F --> P[Isaac<br>*1817 - ]

    J --> Q[Job<br>1837 - 1899]
    J --> R[John Decker<br>1844 - <1900<br>m. Isabella Davis<br>1844 - >1920]:::direct
    J --> S[James W<br>1843 - 1865]
    J --> T[Isaac<br>1850 - ]

    R --> U[William Chamberlain Decker<br>1865 - 1896<br>m. Deborah Henrietta Peer<br>1870 - 1938]:::direct
    R --> V[David Elmer<br>1870 - 1951]

    U --> W[John Francis<br>1891 - 1955]
    U --> X[Clifford J Decker<br>1896 - ~1970s<br>m. Anna Carbaugh<br>*1891 - ]:::direct

    subgraph Gen6
        X --> Y[Clifford Decker<br>1915 - <br>d. Gainesville, FL<br>m. Marjorie<br>*1919 - ]:::direct
    end

    subgraph Gen7
        Y --> Z1[Paul Christian<br>*1950 - ]
        Y --> Z2[Clifford John<br>*1950 - ]
        Y --> Z3[Brian Decker<br>*1950 - 2023]
    end

    subgraph Gen8
        Z1 --> AA[Sara<br>*1980 - ]
        Z1 --> AB[Christin<br>*1983 - ]
        Z2 --> AC[John<br>*1985 - ]
        Z2 --> AD[Andrew<br>*1987 - ]
        Z2 --> AE[Scott<br>*1990 - ]
        Z3 --> AF[Stephen<br>*1982 - ]
        Z3 --> AG[Chrissy<br>*1984 - ]
        Z3 --> AH[Margorie<br>*1986 - ]
        Z3 --> AI[Beth<br>*1989 - ]
    end

    classDef root fill:#4A90E2,stroke:#333,stroke-width:2px,color:#FFF;
    classDef direct fill:#F39C12,stroke:#333,stroke-width:2px,color:#FFF;
```

## Legend
- **Blue Nodes**: Root ancestor(s)
- **Orange Nodes**: Direct lineage
- **Regular Nodes**: Other family members

### Notes
- Birth and death years are approximate where indicated with `*` or `~`.
- Direct ancestors in the primary lineage are highlighted for clarity.

This visualization makes it easy to see connections between generations and identify key family members. Let me know if you need any modifications!
