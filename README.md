## Nix Overview
Nix is an open-source package manager that employs a functional, declarative approach to software management. Nix provides precise control over software versions and dependencies, ensuring that configurations are reproducible and isolated from one another. This approach makes NixOS especially popular with developers and companies who prioritize stability, consistency, and easy rollbacks in complex or production environments.
(Nix is the package manager that can be used across different environments, while NixOS is a Linux distribution that fully leverages the Nix package manager for managing the entire system configuration.) 

## Project Brief
As Nix is still relatively unknown, Numtide—a company dedicated to developing tools and services for Nix—aims to analyze commit patterns in the NixOS nixpkgs repository. The goal is to assess whether companies are showing interest in Nix and if there is growth in that interest, helping Numtide determine if further investment in Nix is worthwhile.
Link to respository: https://github.com/NixOS/nixpkgs

Track Company Contributions: Identify the volume and frequency of commits made by companies and assess their company size.
Observe Trends: Examine how these contributions have evolved over the last three years.
Predict Future Trends: Based on historical data, forecast how corporate involvement might change in the future.

## Planned Approach
- Collect Commit Data: Use the GitHub API to retrieve commit data from the last three years, including email, timestamps, and company information if available.
- Build Data Structure: Organize data in a DataFrame for easy filtering and analysis (cleaning & wrangling)
- Filter by Companies: Separate individual contributors from company contributors by identifying company email domains, anonymizing email addresses.
- Analyze Company Size: Categorize contributing companies by size using publicly available information. (f.e. Linkedin Api, Dataset?)
- Create Visualizations: Generate charts to illustrate contribution trends over time.
(- Predict Future Trends: data patterns to estimate future company engagement.)


