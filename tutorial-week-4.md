##TUTORIAL ON ARRAYS
* I-Working with Arrays

 -A-INTRO

 -B-What is an array?

* II-arrays within arrays

* III-benefits of usage

* IV-other defining attributes and characteristics of an array

* V-practical applications
* VI-CONCLUSION



My tutorial for week four will be concerned with arrays.
We will explore the definition and usage of the array within the context of JavaScript, or .js as we will refer
to it in this tutorial.
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
if you had multiple guitars and you wanted to loop through them to locate any one particular guitar, an efficient way to do this would be to employ the use of an
use an Array. 
The literal syntax structure of this is as follows:

var array-name = [item1, item2, ...];       
In our example let's use guitars, distinguished by make and model.

var guitars = ["Fender Strat","Gibson SG", "Guild Starfire", "Mosrite High Flier", "Peavey Tempest", "Fender Mustang","Fender Telecaster", "Vox Aristocract HB", "Gretsch Country Gentleman"];

In order to locate an element located within any given Array, you need a numbering system or index. Otherwise the
computer would have no point of reference on which tobase any sort of incremental system of calculation.
All Array indexes must start with zero (0) for ease of use with any computer.
Arrays are objects that rest or live or are nested within numbered indexes.


The practical application of array usage should be apparant when contemplating their ability to help group and organize groups of objects, functions, strings, methods, lists, dictionaries, etc.. Below is one pracical example
that was used in a recent code school course taught by an infamously clever computer scientist uber-programmer and 
web development instructor, whos name shall be witheld, in case any of the content is innacurrate it will not
reflect on him/her as an instructor. Any inaccuracies in this tutorial/ mock lesson are purel operator/author error.
disclamimer end here.


Back to the board. As you can see using arrays to accomplish this rank and file type xy grid can be a very efficient way of plotting for use in computer programming.
Take a look at the middle of the board, where squares will exist but empty, without any overlying object or element.
These can just as easily be expressed with NULL, but for the purpose of beiing explicit we will display them as follows.
["br","bk","bb","bQ","bK","bb","bk","br"]
["bp","bp","bp","bp","bp","bp","bp","bp"]
["", "", "", "", "", "", "", ""]/n
["", "", "", "", "", "", "", ""]
["", "", "", "", "", "", "", ""]
["", "", "", "", "", "", "", ""]
["wp","wp","wp","wp","wp","wp","wp","wp"]
["wr","wk","wb","wQ","wK","wb","wk","wr"]
**In the above example, we've essentially created a 2 dimensional array which is housing multiple arrays, which** **themselves contain character representations, string literals, of chess pieces.**
To retrieve an item out of an array you would specify the array name, and put the index number wihtin [] square brackets.

Arrays in conclusion:
In conclusion we can surmize an array with the following statements:
An array is unique type of variable because it doesn't just contain one value, it contains a list or group of 
values. And, the best uses for an array are whenever you want to efficiently group lists of items or a any group
of values that are related to one another. The flexibility of the array is also a valuable characteristic. The array
can be of any undetermined size and can remain forever flexible in its ability to help organize information.

