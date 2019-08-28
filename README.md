# qpdata-fixer

Simple program which converts the qpdata-names, such that if they are accessible in QuPath-0.1.2, if they were produced in a newer version.

To use the application:
1) Run the executable located in the "dist" folder
2) Select the directory containing the qpdata-files to be fixed

NOTE: this is only designed to work for CellSens .vsi. It also only updates the qpdata-file-names, such that the match what was used in the QuPath-0.1.2 version. It also only works for 40x WSIs, but this will be further generalized in the future. It also only works for Windows.
