# Titration of Rate 16.50 Bug Analysis

This notebook investigates the impact of the Medium Titration bug introduced in software version 16.50 for infusion pumps, with a focus on comparative event analysis and visualization. The workflow includes:

- Importing and preprocessing treatment and event log data
- Identifying affected pumps and treatments
- Extracting and aligning key event codes (e.g., rate changes, authorization failures)
- Assigning state flags (Medium Titration, authorization level, mode, software version)
- Mapping events to treatments and software versions
- Generating summary tables for infusions, rate changes, password fail counts, and probabilities by version
- Visualizing the distribution of password fail modes by software version (grouped bar plots)
- Analyzing customer account associations for password failures
- Performing statistical testing (Z-test) of differences in password fail rates
- Summarizing findings and conclusions

The notebook is designed for technical and clinical analysts investigating the scope and impact of the titration bug, and for generating publication-quality tables and visualizations.

**Note:** Data paths and account mapping resources should be updated as needed for your environment.
