# Dummy paragraph generator

![Screenshot](images/ss.png)

It generates random paragraph whenever you click on regenerate.
You can use copy button to copy the generated text.

You can also generate a random paragraph in your website with our library.
Head to
```
assets/js/
```
Download ```script.js```
Add our library file inside your ```head``` tag, now before closing ```body``` tag
open bellow code within ```script``` tag
```
$("NULL").init($("NULL").randomNuml());
```
That will create a variable ```string``` containing the random generated paragraph.
Now to add the generated text inside a div anywhere in your website, simply create a div with an ```id```
and the write the bellow code
```
$("ep").add();
```
where ```ep``` will be you div ```id```
