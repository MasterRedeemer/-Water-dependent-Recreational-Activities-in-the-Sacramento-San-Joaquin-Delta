# Water dependent Recreational Activities in theSacramento-San Joaquin Delta
     Repository of Data used to make a recreation based Image of the California Sacramento-San Joaquin Delta
     Data By: Jeffrey S. Jenkins and Isaac T. Sanchez
     University of California, Merced
     Department of Management of Complex Systems
     ***IF using this repository, please cite the associated manuscript:TBA***

# Input datasets (processed and/or raw where permitted)
    Bass_Files: Adult Striped Bass DFW (Excel--main data set for adult striped bass surveys)
                Index 0-Age Striped Bass (Excel--main data set for 0-age striped bass index)
                     Both Adult and 0-age Excel workbooks contain supplementary sheets with comments and links/citations
                Bass_Plots (Figure used in Final Manuscript)
                Striped_Bass RMD File (project file in R for striped bass statistical workflow)
                    RMD File will run with Folder connection to Adult Striped Bass DFW & Index 0-Age Striped Bass
     Excel_State_Parks: Contains worked excel data used in the final product and also provides raw data files for use in R.
               Audubon Oct Mar: Delta polygon cropped eBird total observations for the months between Oct-Mar
                    + tabs used in final format to share in figures
               Delta Waterfowl hunting data: One tab with worked and analyzed data for waterfowl
               State Parks day use and boating: analyzed excel data for day use and boaters
     Rec_Activites: Contains Excel Data similar to above, minus worked excel data for purpose of importing to R
               Delta_Rec_Activities: Main RMD file used for our main figures and tables
               RecActivites_Plots: PowerPoint of used figure + supplemental figures
               Statistics Tables: Extracted statistics tables for main figure and supplemental figures
               RMD File will run with Data Folder within Rec_Activities connections in first chunk.
     Rec_BEA_Econ: Contains files associated with tourism and visitor sector based plots
               Econ Figure: PowerPoint of plot used as figure in our manuscript
               GDP by Individual Industry: Long Format excel file of 5-county recreation important sectors
                    + supplementary tab in excel citing sources and further information
              Hydrology_By_Year_Weighted: simple excel sheet of May 1 forecast--Year definitions 
              Publix_Version_Tourism_Industry: RMD File will run with connection to GDP by Individual Industry and Hydrology_By_Year_Weighted files
              Travel_Sector_percent_Share: supplementary excel of RMD output for sub-sector share
      Weighted_Hydrology:
               Seasonal_Weighted_Hydrology: Main excel sheet from which other hydrology sheets were made + supplementary tab for further info.
**Required Library Packages for R, for each R-file are at the top of each RMD document**
***All scripts are independent from each other, so no need to run in particular order across RMD files***

               
# R scripts for data cleaning, modeling, and visualization

# Figures, tables, and model outputs used in manuscript

### Open Research
      **Publicly available datasets include:**
    1. California State Parks Statistical Report (https://www.parks.ca.gov/?page_id=23308), 
    2. California Department of Fish and Wildlife hunt results (https://wildlife.ca.gov/Hunting/Waterfowl#877772-hunt-results), 
    3. eBird status and trends (https://science.ebird.org/en/status-and-trends/data-access/),
    4. Bureau of Economic Analysis gross domestic product by county (https://apps.bea.gov/regional/downloadzip.htm), 
    5. California Department of Fish and Wildlife striped bass surveys (https://doi.org/10.6073/pasta/01f75984c8ed1f64d1120af147ce9387), 
    6. California Department of Water Resources Data Exchange Center (https://cdec.water.ca.gov/reportapp/javareports?name=WSIHIST), 
    7. Adult striped Bass Survey data (https://portal.edirepository.org/nis/mapbrowse?packageid=edi.1551.1), 
    8. Summer Townet Survey for 0-age Striped Bass Indices (https://apps.wildlife.ca.gov/Townet/Main/StripedBassIndices). 
      *The archived data portals for these data sets are provided in Research Document and here, facilitating easy access for further research and analysis.*

### Native Land Acknowledgement
    The Legal Delta as it is known comprises of 5 Counties: Contra Costa, Sacramento, San Joaquin, Solano and Yolo, 
    and a sixth partially: Alameda County. Overlapping these Counties and the Legal Delta are known historic lands stewarded by Indigenous Tribes, 
    namely: Me-Wuk, Patwin, and Yokuts, but the list goes further.
    Educate yourself and your research partners on Native Lands and acknowledgments, 
    keeping in step with CARE principles: Collective Benefits, Authority to Control, Responsibility, Ethics

    ***[https://native-land.ca/maps/native-land]***
    ***[https://www.gida-global.org/care]***

### This work is open to be used within the confines of CC licensing attached to this repo
        for questions, comments, concerns: reach out to the owner of this repository: isanchezterrazas@ucmerced.edu
        Reflections and data management can help others attain personal as well as professional insights associated with the work that went into this repo
#### Link to Zenodo or likewise archival software can be found in the link bellow, providing timeless access to these data
     (work in progress)
