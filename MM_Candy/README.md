# Description

Data files containing information about the colour distribution of *M&M Milk Chocolate candies* sampled by Josh Madison.

<br>
<br>

# Format

### **MM_Madison_tidy.csv**

A comma separated values spreadsheet with 288 rows and 6 variables in tidy format:

**pkg**

- Package identifier. Each of the 48 packages come from a single case of 48 total packages.

**weight_oz**

- Weight of package in ounces.

**year**

- Year data was collected.

**col**

- M&M colour.

**qty**

- Candy count.

**exp_col_prop**

- Expected proportion of a given colour according to the values Josh Madison obtained from the official M&M website.

**exp_col_prop**

- Expected quantity of M&Ms given ```exp_col_prop``` and the number of candies in a package. 

<br>
<br>

### **MM_Madison_wide.csv**

A comma separated values spreadsheet with 48 rows and 9 variables in wide format:

**pkg**

- Package identifier. Each of the 48 packages come from a single case of 48 total packages.

**weight_oz**

- Weight of package in ounces.

**year**

- Year data was collected.

**blue; brown; green; orange; red; yellow**

- Candy count of each respective colour.

<br>
<br>

# Source

https://joshmadison.com/2007/12/02/mms-color-distribution-analysis/






