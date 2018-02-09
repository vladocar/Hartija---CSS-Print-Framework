Hartija---CSS-Print-Framework
=============================

#### What is Hartija?

Hartija is universal printing stylesheet or best printing CSS practices all in one.

####  How Hartija works?

Just use it like normal CSS:
```sh
<link rel="stylesheet" href="print.css" type="text/css" media="print">
```
The "magic" is in  media="print", this CSS file will be used by the browser only when you print. You can also use it inside CSS like: **@media print** { .. }.

Only work you need to do is **hide** the stuff you don't need in the final print. Basically you hide some id and class in the CSS like:
```sh
#navbar, #footer, #someOtherID, .someClass, .otherClass { display : none; }
```

http://vladocar.github.io/Hartija---CSS-Print-Framework/
