
导入数据
-----------------------

Dragonfly可导入各种常见图像数据文件，包括标准的图像文件，原始数据，TIFF序列，以及多种商业软件使用的格式。这些文件可以从本地或网络存储设备导入，也可以从CD/DVD、USB移动存储设备导入。

对于三维体数据，Dragonfly支持以下文件格式：

图像序列（后缀名为.tif, .tiff, .jpeg, .jpg, .png, .bmp, .dib等）：图像序列为一系列的二维图像，每个二维图像代表三维空间中的一层（故又称为切片、层面、断层）。注意：每层的二维图像必须具有相同的大小和类型，才能形成一个可以进行体绘制的三维图像。

TIFF (.tif, .tiff extensions)… This file format differs from an image stack in that the entire volume is stored in a single file. Although the majority of TIFFs contain just a single image stored in a directory, some applications can generate multi-directory TIFFs that contain multiple images.

Raw data (.raw and .pic extensions)… A basic file format that saves the active image or stack as raw pixel data without a header.

DAT (.dat extension)… Header file for accompanying raw data.

Analyze (.hdr extension with accompanying .img extension)… Analyze 7.5 files. The Analyze file format was developed at the Mayo Clinic as part of a software package of the same name. Datasets in this format consist of small HDR files that describe the data and IMG files with the raw data. Although there are multiple versions of this format, Dragonfly only supports the 7.5 variant.

MRC (.mrc extension)… A file format for electron density that has become an industry standard in Cryo-electron microscopy. It was developed by the MRC (Medical Research Council) Laboratory of Molecular Biology.

REK (.rek extension)… Fraunhofer raw data file format.

TXM (.txm extension)… A file format used by ZEISS Xradia 3D X-ray Microscopes. Dragonfly Pro supports TXM files using unsigned char, unsigned short integer, or float data. Contact Object Research Systems for information about the availability of Dragonfly Pro.

ORS object file (.ORSObject)… Proprietary binary formatted files in which data is written sequentially and XML (Extensible Markup Language) is appended after the binary data.

NOTE See Image File Formats for more information about the supported files.
