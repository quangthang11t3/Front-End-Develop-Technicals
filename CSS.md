1. [Tips and Tricks](https://github.com/daodc/Front-End-Develop-Technicals/blob/master/Tips-and-tricks.md)

1. [Pseudo-classes](https://github.com/daodc/Front-End-Develop-Technicals/blob/master/Pseudo-classes.md)

2. [CSS Variables](https://github.com/daodc/Front-End-Develop-Technicals/blob/master/Css-variables.md)


```javascripts 
forgot~p 
```

```javascripts
body:not(.ja) {
  font-family: "Myriad Pro",Helvetica,Arial,sans-serif;
}
```
##I. Show or Hide with CSS:

#### 1. Show:

```javascripts
  display: block;
  display: inline-block;
  opacity: 1;
  transform: translateY(0);
  transform: translateX(0);
  visibility: visible;
  backface-visibility: visible;
  -webkit-backface-visibility: visible; /* Chrome, Safari, Opera */
```

#### 2. Hidden:

```javascripts
  display: none;
  opacity: 0;
  transform: translateY(100%);
  transform: translateX(100%);
  visibility: hidden;
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden; /* Chrome, Safari, Opera */
```