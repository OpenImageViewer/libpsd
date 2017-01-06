
# Libpsd ![alt text](https://a.fsdn.com/con/app/proj/libpsd/screenshots/113493.jpg/1 "Libpsd")  

**Photoshop file format decode library written in C**  

Libpsd is a fork of the original Libpsd [project at source forge](https://sourceforge.net/projects/libpsd/).  
It was mainly created to add support for reading PSD files from memory.



---------------------------------
#### Readme from original author

Graphest Libpsd is a open source library which mainly decodes and blends *.psd files. 
There are many ways to read the psd files, however, they cannot decode all the 
information you want, and they don't provide the functions to blend psd again when 
changed the parameters or hided the layers. Libpsd can read the header, thumbnail, 
layer, mask, image resource, channel, path, pattern, adjustment layer, layer effect, 
etc. It converts 1, 8, 16 bit colors formats in Bitmap, Grayscale, Index, RGB, CMYK, 
LAB and multi-channel color spaces to 8 bit RGB color. All the features include in 
Photoshop sdk documents are implemented. After changed the parameters of layer, mask, 
channel and layer effect, Libpsd can blend the file again. It supports for Adobe 
Photoshop CS version, and is compatible with the previous versions of Photoshop. All 
the source code is C language, it's easy to run on many platforms such as Windows, 
Linux, OS2, Mac, etc. 


##### Notice about this file
Libpsd is the product of Graphest Software, copyright 2004-2007, www.graphest.com

This file is the part of Libpsd project, Libpsd is under the terms of the GNU Library 
General Public License as published by the Free Software Foundation; either version 2 
of the License, or (at your option) any later version. See the GNU General Public 
License for more details.
