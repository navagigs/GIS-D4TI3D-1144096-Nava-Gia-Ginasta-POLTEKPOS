**Background:**
 In the use of Geographic Information Systems, there are many among us who do not know how to use the data retrieved on geospatial data. Padapertemuan 4th Geographical Information Systems I will explain how to use geospatial shapefile data using python programming language and also how to use classes and methods in python.

What was Retrieve Data?
What it Shapefile?
What is it geometry?
How Data Retrieval Operations?
Make Class Geospatial Editor?
Create Method Select, Where the State?
contents:
Retrieve Data is retrieving / reading data, this time we will read vector data is data shapefile.Operasi retrieving data at this time using python library named pyshp.


Shapefile (ESRI shapefile) is a data format in a geospatial vector data format is more popular in the data vektor.Format this data developed by the company ESRI.Shapefile 2 is divided into geometry data (shp) and database tables (.dbf) ,

Geometry is the data that make up the coordinates of Flat or geometry, which are:
Import shape.file
Sf.fields () // u / view attributes
Sf.record () // to retrieve all the records
Sf.record (n) // to take the line to the nth record

Point / point [1]
Line / lines [3] Shape Type
Polygon [5]
Operations Data Collection
Library pyshp class shapefile

Method DBF:
Import shape.file Sf.fields () // u / view attributes Sf.record () // to retrieve all the records Sf.record (n) // to take the line to the nth record
Fields
Record (n)
Record (n) lines to (n) records

Method SHP:
shapefile import
sf = shapefile.Reader ( "namafile.shp")
sf.shapes ()
a = sf.shapes ()
 len (a)

Shapes () = display all
Shape (n) = Display with a parameter
Bbox = boundary view map
Parts = determine whether the record is part of another record or fractional relation
Points = coordinates map formation
Shape type = type of geometry of points
Practice:
Creating Class Geospatial editor
Create a file containing the tugas.py with the following code:




**Conclusion:**
Here we create a class and then Method with parameters to display the data record Negara Indonesia.
**Suggestion:**
Should be more frequently practiced in class and at home respectively in order to master this material.
