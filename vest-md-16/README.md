# vest-md-2016

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-maryland-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**
- File: VEST MD 16 data file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/FPW2PW&version=65.0)
  - AWS: `md_2016.zip` (available upon request)
  - Accessed: 08/16/21
  - Note:

- File: VEST MD 16 documentation file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4938232&version=65.0)
  - AWS: `documentation.txt` (available upon request)
  - Accessed: 08/16/21
  - Note:

- File: Maryland Election Day Precinct-Level Results
  - Online: [Maryland Board of Elections Link](https://elections.maryland.gov/elections/2016/election_data/index.html)
  - AWS: `Election_Day`
  - Accessed: 08/16/21
  - Note: These can be downloaded by clicking "General" in the "General" column and "Precinct Results" row.

- File: Maryland Early, Provisional, and Absentee votes
  - Online: [Maryland Board of Elections Link](https://elections.maryland.gov/elections/2016/election_data/index.html)
  - AWS: `Absentee` 
  - Accessed: 08/17/21
  - Note: These files are only available at the county-level and must be downloaded for each county. To do so, click "General" in the "General" column and "County Results" row for each county.
    
- File: Maryland Precinct Shapefile
  - Online: [Maryland Department of Planning Link](https://planning.maryland.gov/Redistricting/Pages/2010/precinct.aspx)
  - AWS:`Shapefile`
  - Accessed: 08/18/21
  - Note: Maryland lists this as a 2010 precinct shapefile. We contacted the Department of Planning to see if there were any more recent shapefiles available and will update this as necessary.

## File processing

- `vest-md-2016-validation.ipynb` - documentation in markdown cells and comments
