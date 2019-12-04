---
layout: post
title: "JavaScript"
code: "console.log(.1 + .2);"
result: "0.30000000000000004"
---
The [decimal.js](http://mikemcl.github.io/decimal.js/) library provides an arbitrary-precision Decimal type for JavaScript.


note that integers in javascript are floats,
just check next example in your browser's dev console:

---
layout: post2
title: "Integers in javascript are floats"
code: |-
  // js in latest firefox and chrome
  103209823048320840000 + 1
  103209823048320840000 + 20000
  103209823048320840000 + 1 == 103209823048320840000
result: |-
  103209823048320840000
  103209823048320860000
  true
---

