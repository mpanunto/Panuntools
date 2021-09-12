***Latest version is 20210911***

## About

PanunTools is a ***very*** cleverly named toolbox created for GISS on wildfire incidents, and currently contains the following tools:

1. [Calculate Containment](docs/README_CalculateContainment.md)
2. [Calculate Ownership](docs/README_CalculateOwnership.md)
3. [Create Fire Progression](docs/README_CreateFireProgression.md)
4. [GISS Workflow Assistant](docs/README_GISSWorkflowAssistant.md)
5. [Multi Export PDF](docs/README_MultiExportPDF.md)
6. [Update Perimeter IR](docs/README_UpdatePerimeterIR.md)

These tools have only been tested for use in ArcGIS Pro 2.7. In the future, some of these tools may be migrated to the [Community GISS Tools](https://github.com/smHooper/giss_community_tools) repository, but for now it was easier to just create my own. I also hope to eventually convert this toolbox of script tools into a Python toolbox in order to tidy up files, enhance collaboration, and improve the visibility of version changes.

## Usage

To use this toolbox:
1. [Download the repository](https://github.com/mpanunto/PanunTools/archive/refs/heads/main.zip)
2. Extract PanunTools.tbx, and the following Python scripts & files to the incident's tools directory:
    - MultiExportPDF.py
    - MultiExportPDF.xlsx
3. Keep Python scripts in the same directory as the extracted toolbox
4. Run tools using ArcGIS Pro

Where possible, I would recommend setting your incident's default input values in the script tool parameters. Doing so will speed up the process of running these tools throughout the duration of the incident.

## Contact
Feel free to contact me (Matt Panunto) at mpanunto@blm.gov with any comments, questions, or error reports.
