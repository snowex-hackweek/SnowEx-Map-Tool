# SnowEx Data Set Map Tool

## Building a Map-Based Tool for Cross-Referencing SnowEx Data Sets

The purpose of this project is to build a map-based tool for cross-referencing SnowEx data sets. This tool will allow users to determine which data sets contain related data (i.e, snow depth) from the same snow pits, without having to download each data set. Goals for the Hackweek include: understanding the data needs of the SnowEx community, determining viable means of building a usable map tool, and creating a functional prototype of the tool.

### Collaborators

| Name | Personal goals | Can help with | Role |
| ------------- | ------------- | ------------- | ------------- |
| Jesslyn D. | Crowd source new ideas for creating a functional map-based web tool for cross-referencing SnowEx data  | I can help with understanding project goals and understanding source data  | Project Lead |
| Preetika K. | Learn about geospatial mapping of the SnowEx datasets | Python | Hackweek-Participant |
| Gail R. | Gain new skills and collaborate with Hackweek participants | Source data, SnowEx Community user metrics | Tutorial Lead |

### The problem

Published SnowEx data sets are currently searchable on the NSIDC website. The data is organized by data set title and can be filtered by campaign year. Broadly geographic information about each data set is available, i.e., "Farmer's Loop" or "Grand Mesa". However, there is currently no way to know which data sets contain data for specific snow pits without individually downloading and opening each data file. This project aims to make cross-referencing related SnowEx data sets simpler by building a map-based tool. Ideally this tool will show locations of all data collection (snow pit or otherwise), with linked information to the relevant data sets.

## Data and Methods

### Data

We will be working with published SnowEx campaign data available from NSIDC. https://nsidc.org/data/snowex/data

### Existing methods

During the 2023 campaign, a simple ArcGIS online map was constructed to track snow pit progress each data. This prompted the idea for creating a more functional map that could be used to improve data access. https://arcg.is/0Diiq

### Proposed methods/tools

Prior to the Hackweek, the initial idea for building this tool was to create a more complex and functional ArcGIS map. The Hackweek presents the opportunity to crowdsource potentially better options. Can the process be automated? Are there more functional web-based mapping tools available? What would the tool look like? How can we collaborate with the SnowEx Database project team to utilize their exisiting tools?

## Project goals and tasks

### Project goals

* Goal 1: Learn from SnowEx data users what functionalitites they would like to see in the map-tool
* Goal 2: Determine the best process for building the map-tool
* Goal 3: Build a small-scale version that can be tested by SnowEx Users
* Goal 4: Plan a course of action for after the Hackweek

### Tasks 

* Task 1: Talk with SnowEx data users about how they currently access data, and how it could be better/easier
* Task 2: Explore different mapping tools. ArcGis? Python based tools? 
* Task 3: Determine the best means of sourcing geographic data from published SnowEx data sets. Can this be pulled from the database? How can we automate this?
* Task 4: Create working model(s) of the tool that can be tested by Hackweek participants

## Project Results

* Goal 1: A data access survey was distributed to the SnowEx community, which provided greater insight into how the community accesses SnowEx data, what difficulties they having doing so, and what types of tools would improve their access to data.

* * Desired Map-Based Tool Features:
      - Interactive map with zoom/pan, hover-over data type display, and color-coded data.
      - Layer control (on/off), spatial/temporal filters, and upload support for shapefiles/KMZ.
      - Connections between related datasets, dataset previews, and metadata.

* * Pain Points:
      - Difficulty extracting specific data subsets
      - limited filters
      - complex database navigation
      - loss of search parameters
      - Need for a better GUI
  
* Goal 2: Project team members increased their knowledge base in using collaborative coding tools, such at Git, Jupyter Notebooks, and CryoCloud. Methods for building the map tool were explored, and the team chose to approach the project by working to build a Jupyter notebook that links NSIDC data sets to snow pit locations using data pulled from both NDIDC and the SnowEx Database.\
* Goal 3: The team created a protype map which locates snow pits and lables the pits with data set DOIs.
* Goal 4: Team members would like to continue collaborating on the project post Hackweek.

