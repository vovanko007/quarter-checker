##Quarter Checker 

A simple JavaScript project which allows 
to identify a point quarter based on
input values of its 'x' and 'y' axis.</span> 

Here is its code:

``` Javascript

    if (isNaN(x) || isNaN(y)) {
        print('Some coordinate was passed with incorrect value!');
    }
    if (x == '' || y == '') {
        print('Some coordinate value is empty!');   
    }
    else if (x > 0 && y > 0) {
        print('Point is in the first QUARTER!');
    }
    else if (x < 0 && y > 0) {
        print('Point is in the second QUARTER!');
    }
    else if (x < 0 && y < 0) {
        print('Point is in the third QUARTER!');
    }
    else if (x > 0 && y < 0) {
        print('Point is in the fourth QUARTER!');
    }
    else if (x == 0 && y > 0) {
        print('Point is in the 1st and in the 2nd QUARTERS!');
    }
    else if (x == 0 && y < 0) {
        print('Point is in the 3rd and in the 4th QUARTERS!');
    }
    else if (x < 0 && y == 0) {
        print('Point is in the 2st and in the 3rd QUARTERS!');
    }
    else if (x > 0 && y == 0) {
        print('Point is in the 1st and in the 4th QUARTERS!');
    }
    else if (x == 0 && y == 0) {
        print('Point is in the beginning of coordinate system!');
    }
  ```
    Project published: 
    
 https://vovanko007.github.io/quarter-checker/