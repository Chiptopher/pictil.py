# pictil.py
pictil.py (pictil in the command line) is a Python utility for managing the names and numbering of files output by Nikon cameras. Generally, they follow the format of "DSC_0000.MOV/.JPG." This utility allows the user to easily change the numbering of those files.

## Usage
pictil is istalled via PyPI/pip
```
pip install pictil
```
To rename files, simply call pictil from the folder with the files that you wish to rename.
```
E:\Workspace\pictil\test>pictil

 > Enter the starting number ####: 1234

   -------------------------------
 > The starting number is:  1234
   -------------------------------
 > Preparing Files
   -------------------------------

 > E:\Workspace\pictil\test\DSC_0208.JPG  ->  E:\Workspace\pictil\test\DSC_1234.JPG
 > E:\Workspace\pictil\test\DSC_0215.JPG  ->  E:\Workspace\pictil\test\DSC_1235.JPG
 > E:\Workspace\pictil\test\DSC_0216.JPG  ->  E:\Workspace\pictil\test\DSC_1236.JPG
 > E:\Workspace\pictil\test\DSC_0374.MOV  ->  E:\Workspace\pictil\test\DSC_1237.MOV
 ```
