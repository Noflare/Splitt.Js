# Splitt.Js

With Splitt.Js you can split your html page to avoid being lost

# Example

`
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <splitt-import dir="home"></splitt-import>

    <script src="./splitt.js"></script>
</body>
</html>
`
Import html with **<splitt-import dir="*Name of files*"></splitt-import>**

home.html
`
<h1 class="welcome">Welcome on Splitt.js</h1>
`
home.css
`
.welcome {
    font-size: 1.5em;
    font-weight: bold;
    color: rgb(255, 0, 0);
}
`

Directory : `
splitt/home/home.html
splitt/home/home.css
`

Result :

![image](https://user-images.githubusercontent.com/80207554/172929043-07617500-0e14-4b0f-a821-cf8163f2de64.png)
