# Decker Family Genealogy

This repository contains a genealogical flowchart tracing the Decker family line from Isaac Decker (*1743 - ~1840) to Clifford Decker (1915 - , died in Gainesville, FL), including all known siblings and children along the direct lineage. The chart is generated using [Mermaid.js](https://mermaid-js.github.io/), which is supported natively in GitHub Markdown.

## Family Line Flowchart

Below is the flowchart showing the descent from Isaac Decker to Clifford Decker. The direct line is highlighted with a thicker border and light purple fill. Each node includes the individual's name, birth/death years, and spouse (for the direct line). Siblings and children are included as branches off their parents.

```mermaid
graph TD
    subgraph Gen1
        A[Isaac Decker<br>*1743 - ~1840<br>m. Dorcas Chamberlain<br>~1750 - ]
        A --> B[Ebenezer<br>1771 - 1850]
        A --> C[John<br>1775 - 1854]
        A --> D[Eunice<br>1777 - >1850]
        A --> E[Christopher<br>*1780 - ]
        A --> F[Jacob Decker<br>~1784 - 1835<br>m. Elizabeth Irwin<br>~1785 - ]:::direct
        A --> G[Daniel<br>*1787 - 1840]
    end

    subgraph Gen2
        F --> H[Mary M<br>1800 - 1889]
        F --> I[Robert<br>1805 - ]
        F --> J[Daniel Decker<br>1808 - 1887<br>m. Sara Martin<br>*1813 - 1885]:::direct
        F --> K[Nancy<br>*1809 - ]
        F --> L[Jacob<br>*1809 - ]
        F --> M[James K<br>*1810 - ]
        F --> N[John<br>1816 - 1860]
        F --> O[George<br>*1817 - ]
        F --> P[Isaac<br>*1817 - ]
    end

    subgraph Gen3
        J --> Q[Job<br>1837 - 1899]
        J --> R[John Decker<br>1844 - <1900<br>m. Isabella Davis<br>1844 - >1920]:::direct
        J --> S[James W<br>1843 - 1865]
        J --> T[Isaac<br>1850 - ]
    end

    subgraph Gen4
        R --> U[William Chamberlain Decker<br>1865 - 1896<br>m. Deborah Henrietta Peer<br>1870 - 1938]:::direct
        R --> V[David Elmer<br>1870 - 1951]
    end

    subgraph Gen5
        U --> W[John Francis<br>1891 - 1955]
        U --> X[Clifford J Decker<br>1896 - <br>m. Anna Carbaugh<br>*1891 - ]:::direct
    end

    subgraph Gen6
        X --> Y[Clifford Decker<br>1915 - <br>d. Gainesville, FL<br>m. Marjorie<br>*1919 - ]:::direct
    end

    subgraph Gen7
        Y --> Z1[One Son<br>*1950 - ]
        Y --> Z2[Two Son<br>*1950 - ]
    end

    classDef direct fill:#f9f,stroke:#333,stroke-width:2px;

'''
