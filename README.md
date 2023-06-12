# slidemap
Map plate row and column to spotted array coordinates.

SlideMap is a Perl module for the creation of MicroArray slide maps

SlideMap is used to create a row/col -> plate/well map of a microarray 
slide.  It does not as yet incorporate annotation data into the map, 
but simply creates the map object based on input parameters.  The map 
is an ordered list of spots with references to annonymous arrays 
containing array_row, array_col, plate_alias, well.  SlideMap currently 
supports 5 types of arrayers: IAS (default), MD, MD3, Lucidia, and 
Stanford.  SlideMap provides 2 methods for conversion of spots->wells and vise-versa,
based on instantiated parameters.  


