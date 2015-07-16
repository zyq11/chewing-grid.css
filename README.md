chewing-grid.css
======

An ideal CSS Grid for card listing design, responsive with no media-queries. 


Not just another grid
-------

Unlike regular grids, you don't have to explicitly determine when your design will break.
So you don't have to write and maintain media-queries!

For example, **the chewing-grid will handle itself to go from 4 to 3 columns** when there is no enough space.
The grid behaviour will depend on its container width and your settings:

 * Minimum and maximum card width
 * Maximum column number

![Demonstration screencast](http://tzi.github.io/chewing-grid.css/demo.gif)

You can play with it: [Live demo](http://tzi.github.io/chewing-grid.css)!

 
Quick start
-------

Install chewing-grid via bower and add it to bower.json dependencies

```sh
bower install chewing-grid --save
``` 

The following HTML create a grid where the cells are:

 * Maximum 4 in the same row
 * Minimum 300px large
 * Maximum 500px large

```html
<link rel="stylesheet" type="text/css" href="build/chewing-grid-atomic.css"/>
<ul class="chew-row chew-row--col-4 chew-row--card-min-300 chew-row--card-min-500">
    <li class="chew-cell">
        <div class="chew-card">1</div>
    </li>
    <li class="chew-cell">
        <div class="chew-card">2</div>
    </li>
    <!-- [...] -->
</ul>
```

[Read the documentation](https://github.com/tzi/chewing-grid.css/blob/master/DOCUMENTATION.md) to go further.


How to Contribute
--------

1. [Star](https://github.com/tzi/chewing-grid.css/stargazers) the project!
2. [Report a bug](https://github.com/tzi/chewing-grid.css/issues/new) that you have found.
3. Tweet and blog about chewing-grid and [Let me know](https://twitter.com/iamtzi) about it.
4. [Pull requests](https://github.com/tzi/chewing-grid/blob/master/CONTRIBUTING.md) are also highly appreciated.


Author & Community
--------

chewing-grid is under [MIT License](http://tzi.mit-license.org/).<br>
It was created & is maintained by [Thomas ZILLIOX](http://tzi.fr).