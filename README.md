# ODK Diagnostics Android App
https://guides.github.com/features/mastering-markdown/

## Introduction
This app analyzes pictures of Rapid Diagnostic Test strips (RDTs) and generates 
output files indicating positive or negative results for one control line and multiple test lines. The general
use case of the app is to be called from an Open Data Kit (ODK) form from the ODK Collect app. It accepts 
input files from specified directories, and generates output files to those same directories. A subset of results and
meta data are sent back and embedded into the ODK Collect form, which is then sent to an ODK Aggregate server. The app can also be opened without 
ODK Collect, and run independently. 
 
## Development History
To my knowledge, the original ODK Diagnostics app was developed by Nicola Dell as a grad school
project at Cornell (many years ago). The original app was intended to be called by CommCare Mobile, which also uses a version of the ODK Collect
platform for form management. My work on the project began in February 2016 with Peter Digovich and Clinton Health Access Intitiative (CHAI)
where we implemented a few short-term changes to get the app to be compatible/called from the regular, non-comm-care ODK Collect, and retain 
other functionality. These compatability improvements were made as quickly as possible to support studies in Zimbabwe by 
Global Solutions for Infectious Diseases (GSID). I am now working on additional improvements and features for the app, with the original
developers permission. I have retained as much of the original app functionality as possible, and am slowly refactoring and adapting the app 
to our use case.

## Technical Overview/Specifications
The two modules in this project are the overall app project module, and a companion module for Open CV, which 
is used in the image analysis. The main specifications are for the overall project module. 

## Current development work
* Refer to "GSID April ODK Dx Update" word document




