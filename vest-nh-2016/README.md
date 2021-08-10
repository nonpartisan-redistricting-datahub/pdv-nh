# vest-nh-2016

Our final election results validation report for NH 2016 General dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-new-hampshire-precinct-and-election-results/), and for NH 2016 Presidential Primary dataset [here](https://redistrictingdatahub.org/dataset/vest-2016-new-hampshire-precinct-and-presidential-primary-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST NH General 2016 file
   - Date accessed: 7/28/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4499009&datasetVersionId=251765
   - File: `nh_2016.zip`
- File: VEST NH Presidential Primary 2016 file
   - Date accessed: 7/28/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/SE51PO&version=64.0
   - File: `nh_2016_pres_primary.zip`
- File: VEST documentation file, 2016
   - Date accessed: 7/28/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863153&datasetVersionId=252739
   - File: `documentation.txt`
- File: Precinct Level Election results, 2016
  - Date accessed: 7/28/2021
  - Link: https://sos.nh.gov/elections/elections/election-results/2016/
  - Note: continue clicking 'Learn more' to get to the excel files needed. 
  - File: we have all of these downloaded, in separate excel files by county and race. 
- File: U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release
  - Date accessed: 7/28/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership20v2/st20_nh.html
  - Note: not downloading these files for the election results validation. 

## File processing:

`vest-nh-2016-validation-general.ipynb` is the script that is the basis of the validation report for the general election file
`vest-nh-2016-validation-pres-primary.ipynb` is the script that is the basis of the validation report for the presidential primary election file
