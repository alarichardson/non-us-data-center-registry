# Dataset Information

## Description

This dataset catalogs 775 data center projects across 123 countries (after searching 193 countries), with data collection ending in the third quarter of 2024. These data center projects include existing and planned initiatives to build data centers, supercomputers, and compute clouds. We deliberately exclude data on data centers in the U.S. in order to focus our analysis on U.S. influence abroad.

The data in our dataset was collected from a mix of public sources: news articles, government announcements, and industry reports. The data search process began with individual queries for each of the 193 countries using the AI-augmented search tool Perplexity AI in Q2 and Q3 of 2024. As individual data centers were identified, researchers recorded 26 variables for each project along with the URLs of the sources of our information.

## Dataset Variables 

Core metadata include the country, year of announcement, reported project type (e.g., data center, cloud, supercomputer), and ownership model (public, private, public-private). 

We also record the intended use case (e.g., government, healthcare, R&D), reported setbacks, and whether the project reportedly involves AI/ML, edge computing, or cybersecurity applications.

To enable analysis of jurisdictional levers, we documented each instance of actor involvement by both sector and nationality. These included:
• U.S. government involvement
• U.S. company involvement
• Chinese government involvement
• Chinese company involvement
• Domestic government and company involvement
• Other international actors (government or corporate)
When available, quantitative variables such as investments ($) and number of GPUs in the projects were recorded to contextualize the compute capacity of the data center projects. Since exact metrics like number of GPUs or FLOPs were not public for most projects, we use reported investment value in the data center projects as a proxy for compute capacity.

We also recorded quotes from the articles to compile a qualitative portion of our dataset, which includes descriptions of project motivations, U.S. and Chinese involvement, and the specific types of setbacks encountered by projects. Setbacks were briefly labeled by the type of problem encountered and checked for frequency by country, but otherwise this qualitative data is not analyzed in this paper.


### Link to Paper
[TBA]

### Title
How Sovereign Is Sovereign Compute? A Review of 775 Non-U.S. Data Centers

### Authors
Richardson, A., Yi, H., Nie, M.,  Wisdom, S., Price, C., Weijers, R., Veld, S.,  & Baker, M..

### Keywords

Digital infrastructure, Data centers, Supercomputers, Cloud computing, Artificial Intelligence, Chinese infrastructure, American infrastructure

### Recommended Citation
Richardson, A., Yi, H., Nie, M., Wisdom, S., Price, C., Weijers, R., Veld, S., Price, C., & Baker, M. (2025). How Sovereign Is Sovereign Compute? A Review of 775 Non-U.S. Data Centers.

### Contact Information
arislrichardson@gmail.com

### Date
Created: 2024

Last Updated: 2025

### Sources
Various news articles and official announcements (URLs preserved in the dataset)

### Language
English

### Worksheet Descriptions

For a list and description of the fields in each sheet, see the `field_info` sheet.

## Technical Information

### Data Collection Methodology

Data was collected from publicly available news sources, government announcements, and official project documentation. A full description of the methodology is available in the accompanying paper. 

### Data Processing
- URLs are preserved for source verification
- Dates are standardized to DD-MMM-YYYY format where available
- Project and quote IDs are cross-referenced between files

### Known Data Limitations
- Limited access to data on Chinese compute projects
- Collected from public data
- Collected using Perplexity AI, which likely biases recent search results
- Some fields contain missing values
- Project timelines may be subject to updates
  
