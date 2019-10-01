# ESGF climate downloads
URL's for generating bash script for bulk downloads of climate data from ESGF

Paste the below URL's into a browser to generate and download a Wget script which can be used for downloading data from ESGF servers. Before running the scripts you **must** be registered with one the the ESGF data portals - e.g. https://esgf-node.llnl.gov/projects/esgf-llnl/.

The file name wget-############.sh of the downloaded script begins with wget- followed by a time stamp, a number and the extension .sh. The script is a UNIX Shell script. Once the file is downloaded, data can be retrieved by opening up a terminal window and typing the following: `bash wget-##############.sh`

For help running the scripts the `-h` command can be appended as below:`bash wget-##############.sh -h`

The scripts generated will automatically create a directory structure similar to the one below:

`/CMIP5/Scenario/Variable/Model/Realisation/`

![CMIP5 directory structure](/DirStructure.PNG?raw=true "CMIP5 directory structure")

For more detailed usage instructions see https://www.earthsystemcog.org/projects/cog/doc/wget

## URL's 
### PR (Precipitation)
https://esgf-node.llnl.gov/esg-search/wget?distrib=true&latest=true&query=pr&download_structure=project,experiment,variable,model,ensemble&project=CMIP5&experiment=historical&experiment=rcp26&experiment=rcp45&experiment=rcp60&experiment=rcp85&experiment=piControl&cf_standard_name=precipitation_flux&variable=pr&time_frequency=mon&realm=atmos&model=ACCESS1.3&model=BCC-CSM1.1&model=CCSM4&model=CESM1(CAM5)&model=CNRM-CM5&model=CSIRO-Mk3.6.0&model=CanESM2&model=GFDL-CM3&model=GISS-E2-H&model=GISS-E2-R&model=HadGEM2-CC&model=HadGEM2-ES&model=INM-CM4&model=IPSL-CM5A-LR&model=IPSL-CM5A-MR&model=MIROC-ESM&model=MIROC5&model=MPI-ESM-LR&model=MRI-CGCM3&model=NorESM1-M&limit=10000

### SFTLF (Land/Sea mask)
https://esgf-node.llnl.gov/esg-search/wget?distrib=true&latest=true&query=sftlf&download_structure=project,experiment,variable,model,ensemble&project=CMIP5&experiment=historical&experiment=rcp26&experiment=rcp45&experiment=rcp60&experiment=rcp85&experiment=piControl&cf_standard_name=land_area_fraction&variable=sftlf&time_frequency=fx&realm=atmos&model=ACCESS1.3&model=BCC-CSM1.1&model=CCSM4&model=CESM1(CAM5)&model=CNRM-CM5&model=CSIRO-Mk3.6.0&model=CanESM2&model=GFDL-CM3&model=GISS-E2-H&model=GISS-E2-R&model=HadGEM2-CC&model=HadGEM2-ES&model=INM-CM4&model=IPSL-CM5A-LR&model=IPSL-CM5A-MR&model=MIROC-ESM&model=MIROC5&model=MPI-ESM-LR&model=MRI-CGCM3&model=NorESM1-M&limit=10000

### TS (Skin temperature)
https://esgf-node.llnl.gov/esg-search/wget?distrib=true&latest=true&query=ts&download_structure=project,experiment,variable,model,ensemble&project=CMIP5&experiment=historical&experiment=rcp26&experiment=rcp45&experiment=rcp60&experiment=rcp85&experiment=piControl&cf_standard_name=surface_temperature&variable=ts&time_frequency=mon&realm=atmos&model=ACCESS1.3&model=BCC-CSM1.1&model=CCSM4&model=CESM1(CAM5)&model=CNRM-CM5&model=CSIRO-Mk3.6.0&model=CanESM2&model=GFDL-CM3&model=GISS-E2-H&model=GISS-E2-R&model=HadGEM2-CC&model=HadGEM2-ES&model=INM-CM4&model=IPSL-CM5A-LR&model=IPSL-CM5A-MR&model=MIROC-ESM&model=MIROC5&model=MPI-ESM-LR&model=MRI-CGCM3&model=NorESM1-M&limit=10000
