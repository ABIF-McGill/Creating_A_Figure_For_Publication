Creating a Figure for Publication
==================================

A hands-on workshop for preparing fluorescence microscopy images using FIJI/ImageJ, from raw images to a publication-ready figure.

Dataset: CHO-K1 cells stained with phalloidin AF488 (actin) and DAPI (nuclei), imaged on an upright Zeiss Axioskop with a 20x/0.5 NA objective.


CONTENTS
--------
- Raw Data Making a Figure for Publication/
	Raw .tif images (Actin, DAPI)

- Corrected Images/
	Output images from Part 1

- Example Images for Figure/                 		
	Pre-processed images for figures (part 2/3 outputs) 

- 2026-ABIF-Creating-Figure-Publication.docx/		
	Full workshop protocol

- Background-Notes-Making-Figure-Publication.pptx/
	Background lecture slides

- Making-Figure-Publication-Actin-Data.xlsx/
	Measured intensity data

- Sample-Figure.pptx/	
	Example completed figure

- Creative Commons License/
	Licensing


REQUIREMENTS
------------
- FIJI/ImageJ (https://fiji.sc/)
- Microsoft PowerPoint and Excel
- PlotsOfData web tool (https://huygens.science.uva.nl/PlotsOfData/)


WORKFLOW
--------
Part 1 - Image Corrections
  Set scale, flatfield correction, background subtraction, save as 16-bit .tif

Part 2 - Adjust Image Display
  Set brightness/contrast and gamma, add scale bar, save as .jpg

Part 3 - Colour Overlay
  Merge DAPI and Actin channels, save overlays as .jpg

Part 4 - Assemble the Figure
  Arrange images in PowerPoint, write figure caption with full metadata

Part 5 - Measure Actin Intensity
  Threshold DAPI to segment nuclei, measure mean actin intensity per cell, export to Excel

Part 6 - Plot the Data
  Upload data to PlotsOfData, explore visualizations, download plot


IMAGING METADATA
----------------
Cell line:    CHO-K1
Actin stain:  Phalloidin AF488, FITC cube, 150 ms exposure
Nuclear stain: DAPI cube, 50 ms exposure
Microscope:   Upright Zeiss Axioskop
Objective:    EC PlanNeoFluar 20x/0.5 NA
Camera:       AxioCam ICm1
Pixel size:   0.369 x 0.369 um
Scale bar:    50 um

LICENSE
-------
All materials are licensed under Creative Commons Attribution-
NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).
(c) Advanced BioImaging Facility (ABIF), McGill University, 2009-2026
https://creativecommons.org/licenses/by-nc-sa/4.0/
