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
and distributed without cost under a BSD-style license. The ROdiomX_DICOM-RT-STRUCTURE module enables conversion of RT-structure data from DICOM to ANALYZE 7.5 for image processing prior to radiomics computation.                                                       

The ROdiomX software is a MATLAB compiled in form of standalone executable file (for 64-bit Windows), which can
be called from the command line and series of graphical user interfaces (GUIs). 

In order to install and use the ROdiomX software, users will require a MATLAB Compiler Runtime
(MCR 64-bit) installation, which is a standalone set of shared libraries enabling the execution of compiled
MATLAB applications and all its components.

Following the recommendations of the IBSI, computation of the following 11 different feature categories are                   
incorporated within the ROdiomX software:                                                                                                                                     
1- Local-Intensity .................... ROdiomX_LI                                                                                                                               
2- Intensity-Histogram .................... ROdiomX_IH                                
3- Intensity-Based-Statistical .................... ROdiomX_IBS                                                                                                
4- Intensity-Volume-Histogram .................... ROdiomX_IVH                                                                                                
5- Gray-Level-Cooccurrence .................... ROdiomX_GLCM                                                                                               
6- Gray-Level-Run-Length .................... ROdiomX_GLRLM                                                                                                
7- Gray-Level-Size-Zone .................... ROdiomX_GLSZM                                                                                               
8- Gray-Level-Distance-Zone .................... ROdiomX_GLDZM                                                                                               
9- Neighborhood-Grey-Tone-Difference .................... ROdiomX_NGTDM                                                                                             
10- Neighboring-Grey-Level-Dependence .................... ROdiomX_NGLDM                                                                                                
11- Morphological .................... ROdiomX_MORPH                                                                                            

The ‘Morphological’ feature category is still under development and more features will be added                                 
to it in the next release of the software. The software is capable of calculating 2D and 3D directional feature computation algorithms for different feature
categories, as well as various feature aggregation techniques (2D, 2.5D, and 3D) as specified with the IBSI guidelines.

Acknowledgements: This work was supported in part by a grant from Varian Medical Systems, Palo Alto, CA.

Data Citation: Bagher-Ebadian, H. and Chetty I.J, "ROdiomX: A Validated Software for Radiomics Analysis of                            
Medical Images in Radiation Oncology", Under Review, Med Phys. 2020


