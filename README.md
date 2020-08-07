# ROdiomX

ROdiomX is an IBSI validated software for radiomics analysis of medical images in radiation oncology                      
URL: <https://github.com/Ebadian-HFHS/ROdiomX>                                                                       
                                                                                          
Copyright (C) 2020                                                                                       
Authors: Drs. Hassan Bagher-Ebadian & Indrin J. Chetty                                                                                                                       
Location: Department of Radiation Oncology, Henry Ford Health System, Detroit, MI 48202, USA

ROdiomX is a free research software that can be shared and redistributed amongst different research users.
This software is shared and distributed among research communities to accelerate radiomic analysis as well as
supporting the goal of radiomic feature standardization based on the IBSI guidelines.

ROdiomX is an IBSI-validated software which has been developed under the MATLAB platform and is not designed
for use in clinic. The ROdiomX software is equipped with a DICOM RT structure reading module that employs the
Plastimatch-1.9.0 software. The Plastimatch software (https://gitlab.com/plastimatch/plastimatch/blob/master/src/plastimatch/LICENSE.TXT) 
is intended for research use only. The Plastimatch is an open source software for image computation in Radiation Therapy (RT) which can be used, modified, 
and distributed without cost under a BSD-style license. This module enables conversion of RT-structure data from DICOM to ANALYZE 7.5 for image processing prior
to radiomics computation.

The ROdiomX software is a MATLAB compiled in form of standalone executable file (for 64-bit Windows), which can
be called from the command line and series of graphical user interfaces (GUIs). 

In order to install and use the ROdiomX software, users will require a MATLAB Compiler Runtime
(MCR 64-bit) installation, which is a standalone set of shared libraries enabling the execution of compiled
MATLAB applications and all its components.

Following the recommendations of the IBSI, computation of the following 11 different feature categories are incorporated within the ROdiomX software: 
1- Local-Intensity                                                                                                
2- Intensity-Histogram                                                                                                
3- Intensity-Based-Statistical                                                                                                
4- Intensity-Volume-Histogram                                                                                                
5- Gray-Level-Cooccurrence                                                                                                
6- Gray-Level-Run-Length                                                                                                
7- Gray-Level-Size-Zone                                                                                                
8- Gray-Level-Distance-Zone                                                                                                
9- Neighborhood-Grey-Tone-Difference                                                                                                
10- Neighboring-Grey-Level-Dependence                                                                                                
11- Morphological                                                                                                


