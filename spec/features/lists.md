Stars

* first item
* second item
* third item


Dashes

- first item
- second item
- third item


Pluses

+ first item
+ second item
+ third item


Nesting

* first item first level
  * second item second level
    * third item third level
    * fourth item third level

List items on multiple lines

* this is the first item in the list
this is still the first item even if it's the second line
* this is the second item in the list
this is still the second item even if it's the second line
this is still the second item even if it's the third line

this is not part of the above list


List items on multiple lines aligned

* this is the first item in the list
  this is still the first item even if it's the second line
* this is the second item in the list
  this is still the second item even if it's the second line
  this is still the second item even if it's the third line

this is not part of the above list


Leading space are supported

  * first item
  * second item


Leading space with multiple list items

  * this is the first item in the list
    this is still the first item even if it's the second line
  * this is the second item in the list
    this is still the second item even if it's the second line
    this is still the second item even if it's the third line

The first list item could not have 4 leading spaces, this should be interpreted as a code block starting with `*`

    * this is not an item list

A single list delimiter is not a list item

*

A single list delimiter follwed by at least one space is a list item

* 

List with inline elements

* list item _ending_
with _emphasis_.

* list item
with **strong emphasis**.

* list item
with [a link](http://google.com).

* list items can have *inline content
  that spans multiple lines*
