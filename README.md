- 👋 Hi, I’m @kalmeshrank
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kalmeshrank/kalmeshrank is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Css Gap</title>
    <style>
       .grid-container{
        display: grid;
        grid-template-columns: auto auto auto auto;
        gap: 50px;

       }
       .grid-container>div{
        border: 1px solid black;
        background-color: yellowgreen;
       } 
       @media screen and (max-width:720px) {
        .grid-container{
        display: grid;
        grid-template-columns: auto ;
        text-align: center;
         }
        
       }

    </style>
</head>
<body>
    

<h1>The gap Property</h1>
<p>Use the <em>gap</em> Property to specify the size of the gap between the rows and colums.
</p>

<p>This grid has a 50px gap betwween rid has a 5px gap between the rows and the columns:

</p>
<div class="grid-container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
</div>

</body>
</html>
