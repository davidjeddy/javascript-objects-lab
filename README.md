[!WARNING]
**⚠️ This project has been archived and is no longer maintained. ⚠️**

Github has shown it does not respect its users. Other have said it better than I can.

- https://www.theregister.com/2022/06/30/software_freedom_conservancy_quits_github/
- https://www.andrlik.org/dispatches/migrating-from-github-motivation/
- https://techresolve.blog/2025/12/27/looking-to-migrate-company-off-github-whats-the/
- https://lord.io/leaving-github/
- https://dev.to/alanwest/how-to-actually-migrate-from-github-to-codeberg-without-losing-your-mind-33bf>
> Development has moved to Codeberg:
> **➡️ https://codeberg.org/DavidJEddy/javascript-objects-lab**
>
> Please update your remotes:
> ```bash
> git remote set-url origin https://codeberg.org/DavidJEddy/javascript-objects-lab
> ```

---
# JavaScript Objects Lab

## Overview

In this lab, we'll create objects and perform various operations on them. 

## Instructions

Be sure to run the tests to get a feel for the types of problems this lab is
asking you to solve. In particular, you'll need to define a `recipes` object and
then apply certain updates (destructively and non-destructively) in various
functions.

![recipes](https://67.media.tumblr.com/6587a382f1b0e5a7d495d8bd4fc55fcd/tumblr_njax7zRQFH1sakzt7o1_500.gif)

Good luck!

**HINT**: You might find `deleteFromObjectByKey` to be a bit hard to write non-destructively. Think about how we learned to use `Object.assign`. What happens if we do

``` javascript
var obj = { foo: 'bar' }

var newObj = Object.assign({}, obj)

newObj // { foo: 'bar' }

delete newObj.foo // true

newObj // {}

obj // { foo: 'bar' }
```

Hmmmmm...

## Resources

- [MDN: Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)

<p class='util--hide'>View <a href='https://learn.co/lessons/javascript-objects-lab'>Javascript Objects Lab</a> on Learn.co and start learning to code for free.</p>