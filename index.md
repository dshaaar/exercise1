<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title> exercise 1 </title>
<link rel="stylesheet" href="css/bootstrap.min.css">
<link rel="stylesheet" href="css/styles.css">
<style>
    * {
        box-sizing: border-box;
        border: 1px solid black;
    }
    #name {
        background-color: rgb(165, 98, 135);
    }
    h2 {
        float: right;
    }
    @media(min-width: 992px) 
    {
        p {
            background-color: aqua;
        }
    }
    
    @media(min-width: 768px) and (max-width: 991px) 
    {
        p { 
            background-color:blueviolet; 
        }
    }
    @media(max-width: 767px) 
    {
        p { 
            background-color:rgb(219, 80, 166); 
        }
    }

</style>
</head>
<body>
    <div id="name">
        <div>
           <h1 style="text-align: center;"> Our menu </h1>
        </div>
        <div class="row">
            <div class="col-lg-4 col-md-6 col-xs-6"> <h2> Chicken </h2> <p> Lorem ipsum dolor sit amet consectetur, adipisicing elit. Illo vitae culpa nesciunt sed, quae laborum voluptatibus quis odio unde officiis beatae recusandae in repudiandae officia delectus exercitationem incidunt? Ad, in.</p></div>
            <div class="col-lg-4 col-md-6 col-xs-6"> <h2> Beef </h2> <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores suscipit saepe laboriosam quo dolorum nesciunt fuga soluta fugiat impedit similique, consectetur labore tempora, enim in repudiandae laudantium nostrum deleniti ex.</p></div>
            <div class="col-lg-4 col-md-6 col-xs-6"> <h2> Sushi </h2> <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam velit corrupti, iusto sit esse nulla magnam consectetur excepturi laborum sint, odio aliquid necessitatibus eaque enim a hic fuga est placeat? </p></div>
        </div>
    </div>
        
</body> 
</html>
