##TUTORIAL ON ARRAYS
* I-Working with Arrays

 -A-INTRO

 -B-TBD

* II-Defining an Array, within an Array***

* III-Unique html Tags

* IV-what is a column? and what is a row? really?

* V-In terms of Black and White:Creating the default piece positions

* VI-CONCLUSION



My tutorial for week four will be concerned with creating a chessboard using nothing but arrays.
This tutorial will attempt to show the method of creating only one part of the process entailed when creating a chessboard in html and/ or javascript.
 1-Arrays are made to house or store multipe values in any single variable.
 It may be helpful to view them as potentially voluminous, cotainers.
 2-An Arroy may, itself, contain or hold other Arrays!
So an Array is a special variable that is capable of holding multiple values at any particular time.


Let's say we have a list of items such as different types of guitars.
If each guitar was treated as single variable, then you could label them as such:

var guitar1="Fender Strat";
var guitar2="Gibson SG";
var guitar3="Guild Starfire";

But, 
if you had multiple guitars and you wanted to loop through them to locate any one particular guitar, you would
use an Array.  This would lie this:
The literal Syntax template of this is as follows:

var array-name = [item1, item2, ...];       

var guitars = ["Fender Strat","Gibson SG", "Guild Starfire", "Mosrite High Flier", "Peavey Tempest", "Fender Mustang","Fender Telecaster", "Vox Aristocract HB", "Gretsch Country Gentleman"];

In order to locate an element located within any given Array, you need a numbering system or index.
All Array indexes must start with zero (0).
Arrays are special objects within numbered indexes.
To Make a chessboard, you can use arrays.

["br","bk","bb","bQ","bK","bb","bk","br"]
["bp","bp","bp","bp","bp","bp","bp","bp"]
["", "", "", "", "", "", "", ""]
["", "", "", "", "", "", "", ""]
["", "", "", "", "", "", "", ""]
["", "", "", "", "", "", "", ""]
["wp","wp","wp","wp","wp","wp","wp","wp"]
["wr","wk","wb","wQ","wK","wb","wk","wr"]
In orde to make the chessboard, one must first formulate a color and title designation must be 
______________________________________________________________________

