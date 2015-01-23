create-grid.less
=======

create grid helper functions for less


```less
@import "create-grid.less";


.create-grid(12 /* @grid-columns */, 768px /* @max-width */);

.create-named-grid(sm /* @name */, 12 /* @grid-columns */, 768px /* @max-width */);
.create-named-grid(md /* @name */, 12 /* @grid-columns */, 640px /* @max-width */);
.create-named-grid(lg /* @name */, 12 /* @grid-columns */, 480px /* @max-width */);

```
