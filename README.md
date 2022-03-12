<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>wint wint phoo is kyat ma pyae par</title>
    <link rel="stylesheet" href="ANIMATION/animate.css">
    
     <style>
        
         
         .container{
             width: 900px;
             height: 700PX;
             background-image: url(../../../photo/park.jpg);
             background-repeat: no-repeat;
             background-position: center;
             background-size: cover;
             align-items: center;
             justify-content: center;
             position: relative;
             margin: 100px auto;
         }

     .mann img{
        width: 150px;
        height: 200px;
        background-color: rgba(253, 253, 253, 0.25);
        position: absolute;
        left: 294px;
        bottom: 121px;
        backface-visibility: visible;
        animation: brokenn 2s 6s,
                    stay 6s;
        transform: translate(-300px);

        animation-play-state:paused;
    ;
    
     }
    .girl{
        width: 150px;
        height: 232px;
        position: absolute;
        left: 443px;
    bottom: 121px;
    animation: broken 2s 6s,
                stay 6s;

    transform: translate(300px);
    animation-play-state:paused;
    }
   
     .knife{
        width :150px;
        height: 200px;
        background-color:  #909eb200;;
    position: absolute;
    left: 381px;
    bottom: 151px;
    animation: knifee 4s 1.5s,
               fadeOut 2s 4s,
               /* knifeee 2s 6s infinite , */
               fadeOut 0.00002ms alternate 5s infinite,
              rollOut 2s 4s;
             transform: translate(1000px);
             animation-play-state:paused;
     }
    .fa{
         width: 140px;
         height: 180px;
         background-color: rgb(0 255 255 / 2%);
     }
     .fa-fa{
         width: 180px;
         height: 230px;
         position: absolute;
       
         left: 396px;
        height: 200px;
        bottom: 357px;
        animation:fadeInUpBig 3s 7s,
                    stay 1150s 9s,
                    flipInY 2s 9s alternate infinite;
        transform: translateY(-1000px);
        animation-play-state:paused;
        
     }

     /* @keyframes dis {
         from{
             transform: translateX(-1000px);
             transform: translateY(1000px);

         }
         to{
             transform: translateY(0px);
             transform: translateX(1000px);
         } */
         
     

    @keyframes fafa {
        from{
            transform: rotate(0deg);

        }
        to{
            transform:animatflipInY;
        }
        
    }
   
    @keyframes knifeee {
        from{
            transform: translate(0px);
        }
        tO{
            
            transform:translate(1000px);
        }
    }
    @keyframes knifee{
        0%{
            
            transform: translate Y(200px);
        }
        20%{
            transform: translate( 0px);
        }
        40%{
            transform: rotate(70deg);
        }
        50%{
            transform: rotate(-70deg);
        }
        60%{
            transform: rotate(70deg);
        }
        70%{
            transform: rotate(-70deg);
        }
        80%{
            transform: rotate(70deg);
        }
        90%{
            transform: rotate(-70deg);
        }
        100%{
            transform: rotate(360deg)  ;
            animation: fadeOut 1s;
            
        }
    }
    @keyframes broken {
        from{
            transform: translate(0px);
        }
        to{
            transform: translate(300px);
        }}
    @keyframes brokenn {
        from{
            transform: translate(0px);
        }
        to{
            transform: translate(-300px);
        }
    }
     @keyframes stay {
        from{
            transform: translate(-0px);
        }
        to{
            transform: translate(0px);
        }
         
     }
    
     .switch{
         width: 200px;
         height: 100px;
          display: inline-block;
         position: relative;
     }
     .switch input{
         width: 0;
         height: 0;
         opacity: 0;
     }
     
     .slider{
        top: 0;
            left: 0;
            right: 0;
            bottom: 0;
         
         position: absolute;
        cursor: pointer;
         background-color: rgb(97, 46, 216);
         transition: .7s;

     }
     .slider::before{
         width: 90px;
         content: "";
         height: 90px;
        
         background-color: #ebbcb7;
         transition: .7s;
         left: 4px;
         bottom: 4px;
         position: absolute;
     }
   

input:checked + .slider {
  background-color: #2196F3;
}

input:focus + .slider {
  box-shadow: 0 0 3px #7fc215;
}

input:checked + .slider::before {
  background-color: black;
  transform: translateX(100px);
}
.kk{
    width: 100px;
             height: 100px;
}
input:checked + .kk{
             background-color: #2196F3;
             animation: heartBeat 2s alternate infinite;
         }

     
        .slider {
            border-radius: 50px;
        }
        .slider::before{
            border-radius: 50%;
        }
        .button{
          




  appearance: none;
  background-color: #000000;
  border: 2px solid #1A1A1A;
  border-radius: 15px;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  display: inline-block;
  font-family: Roobert,-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";
  font-size: 16px;
  font-weight: 600;
  line-height: normal;
  margin: 0;
 
  outline: none;
  padding: 16px 24px;
  text-align: center;
  text-decoration: none;
  transition: all 300ms cubic-bezier(.23, 1, 0.32, 1);
  user-select: none;
  
  touch-action: manipulation;
  width: 200px;
  height: 130px;
  will-change: transform;
}

.button:disabled {
  pointer-events:none;
}

.button:hover{
  box-shadow: rgba(233, 7, 7, 0.25) 0 8px 15px;
  background-color: #ebbcb7;
  transition: 2s;
  transform: translateY(-10px);
}

.button:focus {
  box-shadow: none;
  background-color: rgb(101, 228, 228);
  transform: translateY(0);
}
.heart1{
    width: 200px;
    height: 130px;
    
    position: absolute;
    left: 349px;
    bottom: 332px;
    animation: heartBeat 1.5s 0s alternate infinite;}
        
        
     
    </style>

   

</head>


<body>
   
    <audio src=""></audio>
    <button class="button" onclick="myfunction()">break</button>
   <label  class="switch">
   
       <input type="checkbox" >
       <span class="slider round"></span>
   </label>
 <script>
    let photo= document.getElementsByClassName("phot")
    
    const ok= document.getElementById("knife");
    
    function myfunction(params) {
        document.getElementsByClassName("fa-fa")[0].style.animationPlayState="running";
        document.getElementsByClassName("container")[0].style.animationPlayState="running";
        document.getElementsByClassName("man")[0].style.animationPlayState="running";
        document.getElementsByClassName("knife")[0].style.animationPlayState="running";
        document.getElementsByClassName("fa-fa")[0].style.animationPlayState="running";
        document.getElementsByClassName("girl")[0].style.animationPlayState="running";
        document.getElementsByClassName("fa-fa")[0].style.animationPlayState="running";
        document.getElementsByClassName("knigecover")[0].style.animationPlayState="paused";
     }

 </script>
  <div class="container">
   <img src="../../../../../Downloads/heart-svgrepo-com.svg" class="heart1" alt="">
<div class="mann">
    <img src="../../../photo/man-sitting-on-park-chair-vector-14829333-removebg-preview__1_-removebg-preview.png" class="man" alt="">
</div>

  <img src="../../../photo/young-woman-sitting-removebg-preview (2).png" class="girl" alt="">
    
<div class="knigecover"><img src="../../../photo/knife-removebg-preview.png" class="knife dis" alt=""></div>

   
   <div class="fa-fa"><img src="../../../photo/images-removebg-preview.png" class="fa"  alt="">
<h2 style="font-weight: bolder;">Let's together fa!</h2></div>
    </div>
   
</div>

 
 

</body>
</html>
