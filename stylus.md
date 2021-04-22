[22/04/2021] - Stylus doesn't allow you to use sub elements in @keyframes. You're expected to expand it yourself, instead of using a framework specifically to make CSS easier to use and manage. For example:

```styl
@keyframes anim
    from
        h1
            color red
        h2
            color blue
    to
        h1
            color green
        h2
            color yellow 
```