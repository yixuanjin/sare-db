# sare-db
## Database of Saptial Augmented Reality Modeling and Experitemnts: Manual to access the data

### How to Present and Get Access of Scourses and Data 
The original code of software and algorithem, modeling and experitmantal data will be generated, uploaded , srored and made accessible on yixuanjin GitHub Repository. All data could be shared by submitting pull requests to this repository or by sending data via email to [Yixuan Jin] (mailto: yixuan2019.jin@connect.polyu.hk). 

### File Format;
The software will be developed by applying C++ computer language, and the code of software and algorithms will be created and arranged in the folder named “sources”, with subfolders of each software and algorithms, where the files of software should contain standard files of C++ in the format such as *.h, *.cpp, *.vcproj, *vcxproj. Moreover, the experimental and modeling data will be 2D images in *.PNG format, 3D images in *.obj , and point cloud file in *.ply format, stored in the folder named “data”. Examples of how to organize the data are involved in [here] (https://github.com/yixuanjin/sare-db/tree/master/sources)

### File Naming 
For the sources folder, the subfolder will be named as the name of each software individually. For example, a subfolder could be named as “calibration”. And the standard subfile of each C++ software will also be named as the name of the software, such as calibration.h, calibration.cpp, calibration.vcproj. For the data folder, the subfolders are named as the signal experiment and model. For example, the folder of the first model created for a PolyU new building design project could be named as “PolyU1”. And the 2D, 3D and point cloud files will be named as same as the folder names of the model they belong to, such as PolyU1.PNG, PolyU1,obj and PolyU1.ply.

### File Organization 
The file experimental and modeling data of each building design project should be stored and named in the different files, number sequentially, such as PolyU1.PNG and PolyU2.PNG.

### File Description 
The text files to describe the usage instructions of the software code will be uploaded to “sources” folder. And the description of the experimental environment, general conditions of the design buildings, and the generating process of the 2D, 3D and point cloud files will be stored in the “data” folder.
