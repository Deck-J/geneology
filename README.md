# Decker Family Genealogy

This repository contains a genealogical flowchart tracing the Decker family line from Peter Decker (~1710-1716 - ~1775) to Clifford Decker (1915 - , died in Gainesville, FL), including all known siblings and children along the direct lineage. The chart is generated using [Mermaid.js](https://mermaid-js.github.io/), which GitHub supports natively in Markdown. Data is sourced from the "webGED: DECKER FAMILIES Data Page" and supplemented by web searches, including obituary records.

## Family Line Flowchart

Below is the flowchart showing the descent from Peter Decker to Clifford Decker. The direct line is highlighted with a thicker border and light purple fill. Each node includes the individual's name, birth/death years, and spouse (for the direct line). Siblings and children are included as branches off their parents. Additional findings, such as Brian Decker (1957 - ), are integrated from external sources.


```mermaid
graph TD
    A["Peter Decker
~1710-1716 - ~1775
b. Unknown
m. Susanna
~1715 - "]:::direct --> B["Isaac Decker
*1743 - ~1840
b. Sussex Co., NJ
m. Dorcas Chamberlain
~1750 - "]:::direct
    B --> C["Ebenezer
1771 - 1850"]
    B --> D["John
1775 - 1854"]
    B --> E["Eunice
1777 - >1850"]
    B --> F["Christopher
*1780 - "]
    B --> G["Jacob Decker
~1784 - 1835
m. Elizabeth Irwin
~1785 - "]:::direct
    B --> H["Daniel
*1787 - 1840"]

    G --> I["Mary M
1800 - 1889"]
    G --> J["Robert
1805 - "]
    G --> K["Daniel Decker
1808 - 1887
m. Sara Martin
*1813 - 1885"]:::direct
    G --> L["Nancy
*1809 - "]
    G --> M["Jacob
*1809 - "]
    G --> N["James K
*1810 - "]
    G --> O["John
1816 - 1860"]
    G --> P["George
*1817 - "]
    G --> Q["Isaac
*1817 - "]

    K --> R["Job
1837 - 1899"]
    K --> S["John Decker
1844 - <1900
m. Isabella Davis
1844 - >1920"]:::direct
    K --> T["James W
1843 - 1865"]
    K --> U["Isaac
1850 - "]

    S --> V["William Chamberlain Decker
1865 - 1896
m. Deborah Henrietta Peer
1870 - 1938"]:::direct
    S --> W["David Elmer
1870 - 1951"]

    V --> X["John Francis
1891 - 1955"]
    V --> Y["Clifford J Decker
1896 - ~1970s
m. Anna Carbaugh
*1891 - "]:::direct

    subgraph Gen6
        Y --> Z["Clifford Decker
1915 - 
d. Gainesville, FL
m. Marjorie
*1919 - "]:::direct
    end

    subgraph Gen7
        Z --> Z1["Paul Christian
*1950 - "]
        Z --> Z2["Clifford John
*1950 - "]
        Z --> Z3["Brian Decker
*1950 - 2023"]
    end

    subgraph Gen8
        Z1 --> AA["Sara
*1980 - "]
        Z1 --> AB["Christin
*1983 - "]
        Z2 --> AC["John
*1985 - "]
        Z2 --> AD["Andrew
*1987 - "]
        Z2 --> AE["Scott
*1990 - "]
        Z3 --> AF["Stephen
*1982 - "]
        Z3 --> AG["Chrissy
*1984 - "]
        Z3 --> AH["Margorie
*1986 - "]
        Z3 --> AI["Beth
*1989 - "]
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
