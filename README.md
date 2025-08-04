
 Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).

 Data set: Medical Appointment No Shows
 
 Tools: Excel / Python (Pandas)

 Data Cleaning Summary
 
 Loaded the dataset
The data was read using Python's pandas library.

Checked for missing values
There were no missing (null) values in the dataset.

Removed duplicate rows
The dataset was checked for duplicates. None were found, so no rows were removed.

Standardized text columns

Gender values were converted to uppercase (e.g., "F", "M").

"No-show" values were changed to lowercase ("yes", "no") for consistency.

Neighbourhood names were converted to title case (e.g., "Maria Ortiz").

Converted date columns

The "ScheduledDay" and "AppointmentDay" columns were changed from text to proper date format to enable date-based operations.

Cleaned column names

All column names were converted to lowercase.

Spaces were replaced with underscores.

Example: "AppointmentDay" became "appointmentday", and "No-show" became "no-show".

Checked data types

Age is confirmed as integer.

Date columns are in datetime format.

