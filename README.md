# ParMETIS
ParMETIS 4.0.3 from http://glaros.dtc.umn.edu/

## Why?

The original source is not accessible via git. This makes using it in CMake
files a little bit more obnoxious. In addition, the original download requires
users to modify files before compiling which is not useful when dealing with the
ExternalProject Module.

## Modifications

The default for this repository is 64 bit widths. 

## CMake Template

To use this code within CMake, I recommend creating a new file with the
following content:
```


```