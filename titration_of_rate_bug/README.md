# Titration of Rate 16.50 Bug Analysis

This notebook analyzes the impact of the Medium Titration bug introduced in software version 16.50 for infusion pumps. It covers:

- Data import and preprocessing for treatments and event logs
- Identification of affected pumps and treatments
- Extraction and alignment of key event codes (e.g., rate changes, authorization failures)
- Assignment of state flags (Medium Titration, authorization level, mode, software version)
- Mapping of events to treatments and software versions
- Comparative analysis of alarm/event distributions between SW 16.20 and 16.50
- Statistical testing (Z-test) of differences in password fail rates
- Visualization of mode distributions and customer account associations
- Summary of findings and conclusions

The notebook is intended for technical and clinical analysts investigating the scope and impact of the titration bug, and for generating publication-quality plots and tables.

The data used in this analysis can be found in: [TBD]
