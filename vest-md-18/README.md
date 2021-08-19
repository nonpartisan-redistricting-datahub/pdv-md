# vest-md-2018

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-maryland-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**
- File: VEST MD 18 data file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/S2NLDM&version=43.0)
  - AWS: `md_2018.zip` (available upon request)
  - Accessed: 08/16/21
  - Note:

- File: VEST MD 18 documentation file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4938247&version=43.0)
  - AWS: `documentation.txt` (available upon request)
  - Accessed: 08/16/21
  - Note:

- File: Maryland Election Day Precinct-Level Results
  - Online: [Maryland Board of Elections Link](https://elections.maryland.gov/elections/2018/election_data/index.html)
  - AWS: `Election_Day`(available upon request)
  - Accessed: 08/16/21
  - Note: These can be downloaded by clicking "General" in the "General" column and "Precinct Results" row.

- File: Maryland Early, Provisional, and Absentee votes
  - Online: [Maryland Board of Elections Link](https://elections.maryland.gov/elections/2018/election_data/index.html)
  - AWS: `Absentee` (available upon request)
  - Accessed: 08/17/21
  - Note: These files are only available at the county-level and must be downloaded for each county. To do so, click "General" in the "General" column and "County Results" row for each county.
    
- File: Maryland Precinct Shapefile
  - Online: [Maryland Department of Planning Link](https://planning.maryland.gov/Redistricting/Pages/2010/precinct.aspx)
  - AWS:`Shapefile`(available upon request)
  - Accessed: 08/18/21
  - Note: Maryland lists this as a 2010 precinct shapefile. We contacted the Department of Planning and they responded that this was the current shapefile.


## File processing

- `vest-md-2018-validation.ipynb` - documentation in markdown cells and comments
