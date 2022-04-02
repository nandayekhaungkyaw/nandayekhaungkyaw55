# nandayekhaungkyaw.github.io
#book.html
<a src="book.html">aa</a>
<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="ANIMATION/animate.css">
    <style>
        
       
  body{
    margin: center;
    background-color: rgb(238, 205, 158);
  }
     .main{
         
         width:80%;
         display:flex;
         color: rgb(121, 98, 226) ;
         align-items: center;
         justify-content: flex-end;
         text-align: center;
        margin: auto;


        

     }
     .name{
         color:rgb(71, 71, 218);
         font-weight: 900;
         font-size: larger;
         align-items: center;
         justify-content: center;
         display: flex;

     }
     .parent{
         display: flex;
         text-align: center;
        justify-content: center;
        align-items: center;

     }
    
     
     .child{
         width: 150px;
         display: flex;
         border: 1px solid black;
         color: black;
         flex-wrap: wrap;
         text-align: center;
         border-radius: 10px;
         justify-content: center;
        align-items: center;
        background-color: rgb(162, 92, 228);
         height: 80px;
         
         
         margin:0px 12px;
     }
     .photo1{
         width: 100px;
         height: 100px;
         border-radius: 50%;
     }
     .heart{
         width: 230px;
         height: 200px;
         animation: flirt 2s 0 alternate infinite;
         display: flex;
         align-items: center;
         justify-content: center;
         margin: auto;
     }
     .menu{
         width: 40px;
         height: 40px;

     }
     .button{
         display: none;
         background-color: rgb(153, 153, 233);
         width: 50px;
         height: 50px;
         
         align-items: center;
         justify-content: center;
        
     }
    
                

            
            .photo1{
              
            width: 100px;
            height: 100px;
            border-radius: 50%;
            display: inline-block;
                    
            }
            
            .child{
                display: flex;
                width: 150px;
            
            border: 1px solid black;
            color: black;
            flex-wrap: wrap;
            text-align: center;
            border-radius: 10px;
            justify-content: center;
            align-items: center;
            margin:0px 12px;
            }
            

          
           

            @media screen and (max-width:500px) {
         
         .main{
            width:80%;
            display:flex;
           
            align-items: center;
            justify-content: space-between;
            background-color: rgb(83, 163, 233);
            text-align: center;
            margin: auto;
            border: 1px lightseagreen dotted;
            border-radius: 6px;
         }
         .button{
           
           background-color: rgb(153, 153, 233);
           width: 50px;
           height: 50px;
           display: flex;
           align-items: center;
           justify-content: center;}
         .name{
            
             display: flex;
             align-items: center;
         }
            .button{
                display: block;
            }
            .parent{
                display: none;
            }
            .parent2{
                display: block;
            }
            .photo2{
                display: none;
            }
            .child{
                display: flex;
                width: 150px;
            
            border: 1px solid black;
            color: black;
            flex-wrap: wrap;
            text-align: center;
            border-radius: 10px;
            justify-content: center;
            align-items: center;
            margin:13px 12px;
            }
           
        }
        

    

    </style>
</head>

<body>
    <div class="name">
        <h3> ပေါ်‌ေတောတောကောင်မလေး</h3>

    </div>
    <div class="main">

    
        <img src="../girl/received_473508967640871.jpeg" class="photo1" alt="">
        <button class="button" onclick="show()"><img src="arrow-down-circle.svg" class="main"></button>
      <ul class="parent">
          

          <li class="child"><a href="idol.html">Idol</a>
              </li>
          <li class="child"><a href="fire.html">မီးအကြောင်း</a>   </li>
          <li class="child"><a href="book.html">သူကြိုက်သောစာများ</a></li>
          <li class="child"> <a href="music.html"> MUsic for you</a></li>
          <li class="child"><a href="moment.html">  သူမရဲ့ချစ်စရာကောင်းသောmomentများ</a></li>

      </ul>
  
 
</div>
<img src="feather/heart.svg" class="heart" alt="">




   <script>
        feather.replace()
       let photo1=document.querySelector(".photo1")
 let control=document.querySelector(".parent")
  function show() {
      control.classList.toggle("parent2")
      photo1.classList.toggle("photo2")
      
      
  }


   </script>
</body>
</html>
