# Decker Family Genealogy

This repository contains a genealogical flowchart tracing the Decker family line from Peter Decker (~1710-1716 - ~1775) to Clifford Decker (1915 - , died in Gainesville, FL), including all known siblings and children along the direct lineage. The chart is generated using [Mermaid.js](https://mermaid-js.github.io/), which GitHub supports natively in Markdown. Data is sourced from the "webGED: DECKER FAMILIES Data Page" and supplemented by web searches, including obituary records.

## Family Line Flowchart

Below is the flowchart showing the descent from Peter Decker to Clifford Decker. The direct line is highlighted with a thicker border and light purple fill. Each node includes the individual's name, birth/death years, and spouse (for the direct line). Siblings and children are included as branches off their parents. Additional findings, such as Brian Decker (1957 - ), are integrated from external sources.


```mermaid
graph TD
    A["Peter Decker<br>~1710-1775<br>b. Ulster Co., NY<br>Settler of Deckertown (now Sussex, NJ)<br>m. Susanna (~1715 - ?)"]:::root 
    A --> B["Isaac Decker<br>~1743 - 1840<br>b. Sussex Co., NJ<br>m. Dorcas Chamberlain (~1750 - ?)<br>Landowner in Deckertown"]:::direct
    A --> C["Levi Decker<br>b. Unknown<br>Fled to Minisink, NY after 1779"]
    A --> D["Isaiah Decker<br>b. Unknown<br>Roadmaster in Minisink, NY (1789)"]
    A --> E["Benjamin Decker<br>b. Unknown<br>Settled in Sullivan County, NY"]
    
    B --> F["Ebenezer Decker<br>1771 - 1850<br>b. NJ or NY"]
    B --> G["John Decker<br>1775 - 1854<br>b. Sussex, NJ"]
    B --> H["Eunice Decker<br>1777 - >1850"]
    B --> I["Christopher Decker<br>*1780 - ?"]
    B --> J["Jacob Decker<br>~1784 - 1835<br>b. Sussex Co., NJ<br>m. Elizabeth Irwin (~1785 - ?)"]:::direct
    B --> K["Daniel Decker<br>*1787 - 1840"]

    J --> L["Mary M Decker<br>1800 - 1889"]
    J --> M["Robert Decker<br>1805 - ?"]
    J --> N["Daniel Decker<br>1808 - 1887<br>b. NJ<br>m. Sara Martin (*1813 - 1885)"]:::direct
    J --> O["Nancy Decker<br>*1809 - ?"]
    J --> P["Isaac Decker<br>*1817 - ?"]
    J --> Q["John Decker<br>1816 - 1860"]
    J --> R["George Decker<br>*1817 - ?"]

    N --> S["Job Decker<br>1837 - 1899<br>b. Fairfield Twp., PA"]
    N --> T["John Decker<br>1844 - <1900<br>m. Isabella Davis (1844 - >1920)"]:::direct
    N --> U["James W Decker<br>1843 - 1865"]
    N --> V["Isaac Decker<br>1850 - ?"]

    T --> W["William Chamberlain Decker<br>1865 - 1896<br>m. Deborah Henrietta Peer (1870 - 1938)"]:::direct
    T --> X["David Elmer Decker<br>1870 - 1951"]

    W --> Y["John Francis Decker<br>1891 - 1955"]
    W --> Z["Clifford J. Decker<br>1896 - ~1970s<br>m. Anna Carbaugh (~1891 - ?)"]:::direct

    Z --> Z1["Clifford Decker<br>1915 - ?<br>d. Gainesville, FL<br>m. Marjorie (~1919 - ?)"]:::direct

    Z1 --> AA["Paul Christian Decker<br>*1950 - ?"]
    Z1 --> AB["Clifford John Decker<br>*1950 - ?"]
    Z1 --> AC["Brian Decker<br>*1950 - 2023"]

    AA --> AD["Sara Decker<br>*1980 - ?"]
    AA --> AE["Christin Decker<br>*1983 - ?"]
    AB --> AF["John Decker<br>*1985 - ?"]
    AB --> AG["Andrew Decker<br>*1987 - ?"]
    AB --> AH["Scott Decker<br>*1990 - ?"]
    AC --> AI["Stephen Decker<br>*1982 - ?"]
    AC --> AJ["Chrissy Decker<br>*1984 - ?"]
    AC --> AK["Margorie Decker<br>*1986 - ?"]
    AC --> AL["Beth Decker<br>*1989 - ?"]

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
