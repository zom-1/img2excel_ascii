img2excel_ascii
====
make a Excel ascii picture from image.

## Description
img2excel_ascii.py makes a Excel ascii picture from image.

![Original](namiura_small.jpg)
-->
![Excel File](namiura_ascii_small.jpg)

```
 python img2excel_ascii.py  [-c columns ] [-e excel_file] image_file
```

## Installation
```
git clone git://github.com/zom-1/img2excel_ascii .
```

## Example
```
python img2excel_ascii.py namiura.jpg
python img2excel_ascii.py -c 20 -e test.xlsx namiura.jpg
```

## Requirement
[openpyxl : library to r/w Excel 2010 xlsx/xlsm files](https://openpyxl.readthedocs.org/)

## See also
[img2excel : make a Excel mosaic picture from image](https://github.com/zom-1/img2excel)

## Licence
Copyright (c) 2016 zom-1, Released under the
 [MIT](http://opensource.org/licenses/mit-license.php) license

## Author
[zom-1](https://github.com/zom-1)
