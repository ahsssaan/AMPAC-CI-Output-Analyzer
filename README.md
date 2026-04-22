http://127.0.0.1:8000/

# AMPAC-CI-Output-Analyzer
Parses AMPAC PM6 CI output files and automatically extracts key excited-state results, including S1–S4 energies, wavelengths, oscillator strengths, bright transitions, and convergence trends across active-space sizes. Produces clean tables and short summaries for fast analysis.

Quantum Chemistry Output Analyzer

A simple web tool for reading AMPAC/PM6 output files and automatically extracting the most useful excited-state results, including singlet energies, wavelengths, oscillator strengths, and short convergence-style summaries.

What this project does

This project reads quantum chemistry .out files and turns long calculation outputs into clean, readable results. Instead of manually searching through the file, the tool extracts the important transitions and presents them in a compact format that is easier to compare across different CI active spaces.

Why this project is useful

I built this project as part of my quantum chemistry course, where I need to analyze AMPAC/PM6 output files and compare excited-state results. Since a lot of the work is repetitive and time-consuming, I thought it would be smarter and easier to create a tool that automates the process.

This makes it easier to:

save time
reduce manual errors
compare results for different n values
generate clean summary tables for reports
How to get started
Open the site locally.
Upload or provide your AMPAC/PM6 output file.
Let the tool parse the file automatically.
View the extracted singlet states, oscillator strengths, and summary output.
Features
Parses AMPAC/PM6 .out files
Extracts excited-state transition data
Reports S1, S2, S3, S4 values in eV, nm, and oscillator strength
Gives short summary text for each calculation
Helps compare results across active-space sizes like n = 12, 14, 16, 18, 20
Where to get help

If something does not work as expected, check:

whether the uploaded file is a valid AMPAC output file
whether the required transition section exists in the file
whether the format matches the expected PM6 output style

You can also open an issue in the repository for bugs or suggestions.

Maintainer

Created and maintained by Ahsan for a quantum chemistry course project.
