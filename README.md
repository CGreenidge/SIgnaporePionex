# SIgnaporePionex
# Data Cleaning and Processing Script

## Purpose
This script is designed for data cleaning, validation, and preparation of user data from a CSV file. It processes, validates, and organizes data, saving the cleaned and invalid entries to separate CSV files.

### Key Functionalities
1. **Clean Headers** - Converts column headers to lowercase and replaces spaces with underscores.
2. **Drop and Collect Data** - Removes specified columns and returns them as a separate DataFrame for garbage collection.
3. **Chunking** - Splits the DataFrame into chunks for parallel processing.
4. **Email and Phone Validation** - Validates email addresses and phone numbers.
5. **Name Formatting** - Capitalizes first and last names.
6. **Export Data** - Saves cleaned data and invalid data to separate CSV files.

#### Requirements
* pandas
* re

##### Example Usage
To run the script, use:
```python
import pandas as pd
import re
