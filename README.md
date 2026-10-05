# Data-Cleaning-using-Power-Query---CDR-Real-Job-Query-
his file contains uncleaned Vodafone Call Data Records (CDR). Raw telco exports usually come with metadata headers (MSISDN, Report Date, Date Ranges) and trailing legend notes (e.g., definitions like INC :- Incoming, PP :- Prepaid), along with separator lines.

# Demonstrates Real-World Industry Skills
Unstructured Raw Export: Telecom Call Data Records (CDRs) are messy in real life. 
They don't arrive in clean tables—they come bundled with metadata headers, divider dashes (-----), and footer code legends.

# Solves "Messy Excel" Problems:
Employers look for portfolio projects that go beyond clean Kaggle CSVs. 
Cleaning metadata headers, whitespace-padded column names, and trailing footnotes shows practical ETL (Extract, Transform, Load) competency.

# Key Data Cleaning Challenges Featured
Adding this dataset lets you highlight several essential data engineering techniques:

Header & Metadata Extraction: Isolating top metadata (e.g., target subscriber MSISDN, report date, time range) before stripping non-tabular rows.

Multi-line Footnote Removal: Trimming variable-length legends and system notes at the end of the file.

Column Name Sanitization: Cleaning leading/trailing whitespace in column names (e.g., ' B PARTY NUMBER' and ' CALL_DATE').

Preserving Leading Zeros & Text IDs: Correctly casting phone numbers, Cell Tower IDs, and SMS Gateway IDs as Text to prevent Excel/Power Query from converting them to scientific notation or truncation.
