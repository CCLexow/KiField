.. :changelog:

History
-------

0.1.10 (2018-01-01)
______________________

* File backup now works on all files in a hierarchical schematic.


0.1.9 (2017-12-31)
______________________

* Fixed mishandling of quoted strings containing escaped quotation marks.


0.1.8 (2017-09-23)
______________________

* Catch exception caused by numeric fields that aren't strings interacting with vis/invis option.


0.1.7 (2017-08-14)
______________________

* Added visibility/invisibility option for fields.


0.1.6 (2017-01-30)
______________________

* Added "grouping" option (`--group`) for gathering components with the same field values onto a single line of the XLSX/CSV/TSV file.


0.1.5 (2016-11-29)
______________________

* Added recursive operations on hierarchical schematics so everything can be handled just by processing the top-level file.


0.1.4 (2016-05-29)
______________________

* Added support for TSV files (thanks, kaspar.emanuel@gmail.com).


0.1.3 (2016-05-29)
______________________

* Fixed issue where all the fields from multi-unit components in a schematic were not appearing in the csv file.


0.1.2 (2016-04-13)
______________________

* Fixed issues #3 and #4 regarding incompatibilities with openpyxl 2.4.0a1.


0.1.1 (2016-02-20)
______________________

* Added the ability to extract/insert fields in DCM files.
* Added the ability to explicitly exclude fields from extraction/insertion.


0.1.0 (2016-01-29)
______________________

* First release on PyPI.
