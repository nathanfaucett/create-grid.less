create-grid.less
=======

create grid helper functions for less


create-grid(@name, @grid-columns, @min-width[, @max-width])


```less
@import "create-grid.less";


// columns only used when size of screen fits min max width
.create-grid(xs, 12, 0px, 480px);
.create-grid(sm, 12, 480px, 640px);
.create-grid(md, 12, 640px, 800px);
.create-grid(lg, 12, 800px);

// columns only used if size of screen fits and not overridden by larger query, like bootstrap
.create-grid(xs, 12, 0px);
.create-grid(sm, 12, 480px);
.create-grid(md, 12, 640px);
.create-grid(lg, 12, 800px);
```
