# Global Heatwave Warning Systems

## Problem Statement

Recognizing the critical need to protect vulnerable populations from the adverse effects of extreme heat, the establishment of effective Heat Warning Systems (HWS) is now a priority. The existing Heatwave Warning Systems Inventory developed by WMO is the primary source for understanding the HWS global distribution. However, it is incomplete, making it challenging to ascertain the extent of global preparedness for heatwaves. This research seeks to bridge this gap.

## Project Objective

The overarching objective of this project is not just to provide a snapshot of the current state of Heatwave Warning Systems (HWS) globally but to establish a robust foundation for future research and improvements. By establishing a systematic approach to data extraction, cleaning, and predictive modeling, we aim to create a blueprint that WMO and other stakeholders can leverage. The methodologies and insights presented here can guide efforts to enhance data collection, refine predictive models, and ultimately, improve heatwave preparedness worldwide. This project underscores the potential of data-driven strategies in addressing global challenges and paves the way for more informed decision-making in the realm of climate preparedness.


## Technical Details


### Libraries and Tools Used

- **Python**: The primary programming language used for data analysis and processing.
- **Pandas**: For data manipulation and analysis.
- **Selenium**: For web scraping to gather data from online research journals.
- **BeautifulSoup**: For web scraping to gather data from online research journals.
- **Hugging Face's RoBERTa**: Utilized for predicting the presence of heatwave systems based on research paper abstracts.

### Repository Structure

- `data/`: 
  - `raw/`: Contains the initial data files sourced from various platforms such as WMO, PubMed, Google Scholar, and Google Search.
  - `processed/`: Datasets that have undergone cleaning, transformation, or any other processing.
  - `supplementary_data/`: Additional datasets used for deeper insights, such as the dataset on income levels.

- `scripts/`: 
  - `data_extraction/`: Scripts and notebooks dedicated to the data extraction process from various sources.
  - `data_modeling/`: Scripts and notebooks focused on predictive modeling using tools like Hugging Face's RoBERTa.
  - `data_processing/`: Scripts and notebooks used for data cleaning, validation, and other preprocessing tasks.

- `projectdocument/`: 
  - `data_engineering/`: Documentation detailing the data engineering journey, from collection to integration.
  - `visualizations/`: Charts, graphs, and other visual representations of our findings.
  - `instructions/`: Guidelines and steps for reproducing the analysis or setting up the project.
  - `presentations/`: Slides or other presentation materials showcasing the project's results and insights.
  - `case_studies/`: Detailed examinations of specific instances or discrepancies encountered during the project, providing insights and validation steps.

- `README.md`: This document, providing an overview of the project, methodologies, and other relevant details.

