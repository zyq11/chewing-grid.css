chewing-grid.css
======

A CSS Grid ideal for **card listing design** like tiles, videos or articles listing.

No media queries, yet Chewing Grid will adjust the number of columns depending on the available width and your settings regarding:

* the maximum number of columns
* the minim and maximum card width

Here's a GIF to show you how it looks.
If you want to play with it, check out [the live demo](http://tzi.github.io/chewing-grid.css).

![Demonstration screencast](http://tzi.github.io/chewing-grid.css/demo.gif)

 
Quick start
-------

Install chewing-grid via bower and add it to bower.json dependencies

```sh
bower install chewing-grid --save
``` 

You can use it with atomic classes, custom CSS rules or Sass mixins.

For example: the following HTML use atomic classes to create a grid where the cells are:

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