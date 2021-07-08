# Mill River Discharge v. Water Quality Correlation 
## Goal:

- Determine correlation between (1) and (2) below:
    
   1)  water quality data collected by Connecticut River Conservancy from site Mill River, Northampton at Rope Swing off Smith College Path at coordinates (-72.650227, 42.317161)
    
    2) discharge data from USGS site '0117500 Mill River at Northampton, MA,' located 1.4 mi upstream from monitor site near the Clement Street Bridge.


## Method:
- First tested for Pearson R correlations between discharge data for: 
    - Day of measurement 
    - " " + 1 day prior
    - " " + 2 days prior
    - " " + 3 days prior 
- Then tested for Spearman R correlations between discharge data and quality rankings:
    1) 'Blue Clean for Boating and Swimming'
    2) 'Yellow Clean for Boating'
    3) 'Red Not Clean for Boating or Swimming'

## Results:

### Pearson R Correlation Results: 

|             |    3days |     2days |       1days |       0days|
--------------|---------|-----------|-------------|-----------
|pearson_corrs | 0.116268 | 0.153425  | 0.275235    | 0.27112     |
|p-vals        | 0.12767  | 0.0438721 | 0.000247389 | 0.000308573 |


### Spearman R Correlation Results:

| |3days |2days |1days |0days|
---------------|---------|----------|-----------|-----------
|spearman_corrs | 0.113745 | 0.156522  | 0.207701   | 0.223033   | 
|p-vals         | 0.136205 | 0.0397344 | 0.00610577 | 0.00318268 |

