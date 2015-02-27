create-grid.less
=======

create grid helper functions for less


create-grid(@name, @grid-columns, @min-width[, @max-width])


```less
@import "create-grid.less";


// columns only used when size of screen fits min max width
.create-grid(xs, 12, 0, 480);
.create-grid(sm, 12, 480, 640);
.create-grid(md, 12, 640, 800);
.create-grid(lg, 12, 800);

// columns only used if size of screen fits and not overridden by larger query, like bootstrap
.create-grid(xs, 12, 0px);
.create-grid(sm, 12, 480px);
.create-grid(md, 12, 640px);
.create-grid(lg, 12, 800px);

// creates hidden classes for using hidden-@{size}, hidden-min-@{size}, and hidden-max-@{size}
.create-hidden(xs, 0, 480);
.create-hidden(sm, 480, 768);
.create-hidden(md, 768, 960);
.create-hidden(lg, 960);
```
