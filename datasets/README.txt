#####################
Supplemental Datasets
#####################

In total, there are five wild type datasets #120830WT.csv, #121204WT.csv, #121211WT.csv, #130508WT.csv, #130607WT.csv and the aurora mutant (auroraMutant.csv). For each cell, the position of the first and the last frame before it divides is stored. All files share the same header information which are explained below:

-------------
DataRotation:
Angles for which the dataset is rotated around the x, y and z axes to create the three viewing types: Front (x-y), side (x-z) and radial (y-z).
-------------
RootCenter:
Centre of the root which is determined manually.
-------------
DataDimension:
Dimension of the raw dataset.
-------------
Id:
The unique ID for each cell nucleus.
-------------
X, Y, Z, T:
The 3D position and the time point of the cell.
-------------
Precursors:
The sorted list of precursor IDs to generate the tracking information.
-------------
Lineage:
The cell lineage identifier.
-------------
CellFile:
The cell file value which is determined manually.
-------------
Layer:
The unique layer value according to performed periclinal divisions.
-------------
DivType:
The type of division of the cell: anticlinal is 0, periclinal is 1, radial is 2. For the first pair of a cell description and the last analysed time point, a "-" is inserted.
