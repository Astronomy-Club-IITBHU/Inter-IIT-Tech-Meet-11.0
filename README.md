# InterIIT-ISRO

Pradan: https://pradan.issdc.gov.in/

TMC-2: 
	Terrain Mapping Camera-2 (TMC-2) is a follow-on of the TMC on-board Chandrayaan-1. TMC-2 provides images (0.4μm to 0.85μm) at 5m spatial resolution & stereo triplets (fore, nadir and aft views) from a 100 km orbit for preparing Digital Elevation model (DEM) of the complete lunar surface. The triplet images from TMC-2 when processed into Digital Elevation Models, enable mapping of surface landform morphologies.

OHRC:
	OHRC provides high-resolution images of the landing site which ensure the Lander’s safe touchdown by detecting any craters or boulders, prior to separation. The images it captures, taken from two different look angles, serve dual purposes. First, these images are used to generate DEMs (Digital Elevation Models) of the landing site. Second, they are used for scientific research after its initial role in the landing phase. OHRC’s images can capture the same area on the lunar surface from two different orbits. The coverage area in this case is of 12 km x 3 km with ground resolution of 0.32 m. OHRC is an optical camera system based on Time Delay Integration (TDI) imaging sensors with 12000 detectors. It has 4 TDI settings and 7 different integration times.

- Data:
    - ohrc
    - ohrc_overlap
    - ohrc_patches
    - ohrc_tif
    - tmc_call
    - tmc_overlap
    - tmc_patches
    - tmc_tif
    - unzip_tmc
    - unziped_ohrc
    - unziped_tmc

- Utils:
    - img_tif.py: Converts a img file to a  tif file and returns it.
    - overlap_test.py: finds an overlapping region of tmc and ohrc and returns two tif files of tmc overlap and ohrc overlap respectively, with necessary metadata.
    - unzip.py: extract the zipped files downloaded from the Pradan site.
    - create_patch.py: create smaller chunks of raster data from larger raster data.
    - fjn_util.py: various utility functions
    - create_csv.py: creates csv from the given overlapping patches of appropriate size.

