# Install command:
pip install requirements.txt

# To run test for EN language:
robot --variable language:EN testcases/powerbuy.robot


# To run test for TH language:
robot --variable language:TH testcases/powerbuy.robot

### All test cases is in folder /testcases/
### I define locator, testdata, site URL (dynamic datas) separately for each language (TH/EN).
### Test data for TH language is not ready yet, so please test for EN only.
