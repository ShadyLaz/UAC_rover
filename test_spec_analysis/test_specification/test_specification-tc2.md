# Test specification

## tc1

### Description

Something here

- **Test name:** weather module 30 seconds measurements
- **Test filename:** weatherModule
- **Test type:** QA
- **Test level:** L1
- **Test created by:** Shady


## Preconditions

| **Action**                                                  | **Expected outcome**                                                                  |
|:------------------------------------------------------------|:--------------------------------------------------------------------------------------|
| date class that can check the time of the last measurements | use datetime function to check if the last measurement was measured less than 30s ago |


## Test

| **Action**                                                                        | **Expected outcome**    |
|:----------------------------------------------------------------------------------|:------------------------|
| add functionality to check if the time for last measurement was less than 30s ago |  if the last measurements was less than 30s ago return last measurement , if last was more than 30s ago return new measurements |


## Postconditions

| **Action**          | **Expected outcome** |
|:--------------------|:---------------------|
| no actions required |                      |
