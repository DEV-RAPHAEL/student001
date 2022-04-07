# student001

## Update By Praise Codes

There were many updates done in this:
1. I changed the way the links were placed in the HTML documents (The Navigation Links). The Former was:

```html
<div id="nav_link">
    <a href="index.htm">Home</a>
    <a href="card1.html">Recover Card</a>
    <a href="track.html">Track Delivery</a>
    <a href="register.html">Sign Up</a>
</div>
```
<br/>

But now changed to:
<br/>

```html
<div id="nav_link">
    <a href="./">Home</a>
    <a href="./card1">Recover Card</a>
    <a href="./track">Track Delivery</a>
    <a href="./register">Sign Up</a>
</div>
```

2. To achieve what I did in update 1 above, I had to change the entire directory structure. Previously I had the files just there in the parent directory but now I have them in folders... These folders will have the exact same names as when the files were all in the parent directory but no extensions, example
```
track.html
```
Changes to:
```
(DIR)track->index.html
```

That way I can achieve what I did in update 1.
