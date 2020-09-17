## Reading #5 

Block Vs Inline elements

CSS rules contain a SELECTOR and a Declaration (inside {}

h1 {color: yellow}

External CSS sheets are called inside the <head> section

```<html>
<head>
<title>Using External CSS</title>
<link href="css/styles.css" type="text/css"
      rel="stylesheet" />
  </head>
</html>```

Internal CSS - you can use CSS internally, usually inside the head

```<head>
<title>Using Internal CSS</title> <style type="text/css">
      body {
          font-family: arial;
          background-color: rgb(185,179,175);}
      h1 {
          color: rgb(255,255,255);}
    </style>
  </head>
```

## Color in CSS

Available data types

```
Color formats in CSS 

RGB
rgb(102,205,170)

RGB + Alpha
rgba(102,205,170, 1)



Hex
#66cdaa

limited preset colors by name
MediumAquaMarine

HSLA (HSL + Alpha)
hsla(0,100%,100%,0.5)
```

