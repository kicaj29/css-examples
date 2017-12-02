# css-examples

## flexbox-vs-grid
__Flexbox__ is essentially for laying out items in a __single dimension__– in a row OR a column. 
__Grid__ is for layout of items in __two dimensions__– rows and columns.   
https://tutorialzine.com/2017/03/css-grid-vs-flexbox
https://css-tricks.com/css-grid-replace-flexbox   

NOTE: but it is also possible to achieve two dimensions using flexbox, it is presented in examples flexbox-layout-possibility{n}.

### flexbox
Examples flexbox-layout-possibility{n} show how to build the same layout using different methods:

possibility1: use one flex container      
possibility2: use two flex containers

http://the-echoplex.net/flexyboxes/
* __flex-flow__:   flex-direction (default is row) flex-wrap (default is wrap). Should be used __on container.__
  * flex-direction:  When direction is row it means that elements are arranged from left to right. When direction is column the elements are arranged from top to down.
  * flex-wrap
* __flex__: flex-grow (default is 0) flex-shrink (default is 1) flex-basis (default is auto). Should be used __on items.__    
  * __flex-grow__ property specifies how much the item will grow relative to the rest of the flexible items inside the same container.
  __0 = don't grow__   
  * __flex-shrink__ property specifies how the item will shrink relative to the rest of the flexible items inside the same container.
  __0 = don't shrink__
  * __flex-basis__ property specifies the initial length of a flexible item.   __auto__ means that the length is equal to the length of the flexible item.
  If the item has no length specified, the length will be according to its content. __This property can be used to go to the new row(column).__




### grid
