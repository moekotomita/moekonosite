<!DOCTYPE html>
<html lang="ja">
<head>
   <link rel="stylesheet"   href="style.css" />
   <meta charset="UTF-8" /> 
   <link rel="preconnect" href="https://fonts.googleapis.com">
   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
   <link href="https://fonts.googleapis.com/css2?family=M+PLUS+Rounded+1c:wght@500&family=Sawarabi+Gothic&display=swap" rel="stylesheet">
  <title>hiiammoeko</title>       
</head>

<body>
<div class="zentai-box">

<div class="namae-kakutoko">
       <h1>MOEKO TOMITA</h1>    
       <p class="pacwebteam">PAC Web-Team</p>     

</div>

<div class="music-pic">
<div class="music1">
   <img src="dean-d.jpg" class="image_33">
   <img src="dirty dancing.jpg" class="image_33">
   <img src="finnese.jpg" class="image_33">
</div>

<div class="music2">
   <img src="less of you.jpg" class="image_33">
   <img src="サントラ.jpg" class="image_33">
   <img src="like.jpg" class="image_33">
</div>

<div class="music3">
   <img src="青春病.jpg" class="image_33">
   <img src="young forever.jpg" class="image_33">
   <img src="裸の勇者.jpg" class="image_33">
</div>

<p div class="moji1">About Me</p>
 <div class="profile">
 <div class="yohaku">
 <img src="私の写真.jpg" class="watashi"></div>    

            <div class="information"> 
  <p> MOEKO TOMITA</p>
<p> 2005/02/15</p>
<P> Chiba/Shin-Urayasnu</P>
 <p> Music(Piano/Cello)</P>
 <p> Novel/Comics</P>
 <p> Basketball</p>
 <p>ENFP→ENFJ</P>

 </div>

</div>

<p div class="moji2">
                              No Comics No Life! </p>

<div class="dekaiwaku">
<div class="no-comics-no-life">
  <div class="yohaku2">
    <img src="ブルーピリオド.jpg"  class="blue-period">
  </div>
    <div class="information2">
      <p div class="daimei1">Blue Period.</p>
      <p div class="text">成績優秀、世渡り上手。</p>
      <p div class="text">飲酒喫煙夜遊び好きで人望もある</p>
      <p div class="text"> リア充高校男子が</p>
      <p div class="text">なぜか絵を描く喜びに目覚めた!?</p>
      <p div class="text"> 美大を目指して青春を燃やす</p>
      <p div class="text"> スポコン受験物語が開幕!</p>
    </div>
 </div>


 <div class="no-comics-no-life2">
   
   <div class="information3"> 
     <p div class="daimei">氷の城壁</p>
     <p>人と接するのが苦手で、他人との間を壁で隔ててしま</p>
     <p>う氷川小雪。高校では誰ともつるまずに1人で過ごし</p>
     <p> ていたけど、なぜかぐいぐい距離を詰めてくる雨宮ミ</p>
     <p>ナトと出会いーー?</p>
   </div>

   <div class="yohaku2">
     <img src="氷の城壁.jpg" class="blue-period">
     </div>
   </div>

   <div class="no-comics-no-life3">
    <div class="yohaku3">
   <img src="アクタージュ.jpg"  class="blue-period"> </div>
                              <div class="information3">
     <p div class="daimei">アクタージュ</p>
     <p> 女優を目指す女子高生・夜凪は有名芸能事務所スター</p>
     <p>ズのオーディションで天才的な芝居をするも不合格。</p>
     <p>それは彼女の危険な演技法に理由があった。しかし、</p>
     <p>夜凪の才能に魅せられた映画監督・黒山が役者の世界</p>
      <p> に誘う‼</p> </div>
  </div>
   </div>
</div>

</body>

</html>



.namae-kakutoko h1{
                           
                           margin-top:8%;  
                           margin-bottom: 0px;
                            text-align: center;
                              font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                              font-weight: 800px;
}

.pacwebteam{
                              text-align: center;
                              font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                              font-weight: bold;
                              color: #ff652d;
}    

.moji1{
                           
                           margin-top: 20%;    font-size: 40px;  text-align: left;
                           padding: 60px;
                           font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                           color: #ffffff;
                           background-color: #333333;


}

.moji2{
                           
                              margin-top: 20%;    font-size: 40px;  text-align: left;
                              padding: 60px;
                              font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                              color: #ffffff;
                              background-color: #333333;
   
   
   }


.music-pic{
                              display: flex;
                              flex-direction: column;
}

.music1{
                              display: flex;
                              flex-direction: row;
}
.music2{
                              display: flex;
                              flex-direction: row;
}
.music3{
                              display: flex;
                              flex-direction: row;
}

.image_33{
                              width: 33%;
                              margin:2px;
}

.profile img{
                              margin-top: 20%;
width: 100%;
}

.profile p{
                              font-size: 20px;
                              text-align:center ;
                              margin-top: 10%;
               font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.profile{
                              display: flex;
              justify-content: space-around;


}


.information{
                              margin-top: 10%;
                              padding-left: 1px;
                              font-weight: bold;
}

.yohaku{
                               width: 40%;                   
}

.no-comics-no-life img{
                              width:100%;
                              margin-top:10%;
}
.yohaku2{
                              flex-basis: 50%;
}

.yohaku3{
                              flex-basis: 50%;
}


.dekaiwaku{
                             margin: 0%
                             ; display: flex;
                              flex-direction: column;
}

.no-comics-no-life{
                              display:flex ;

                              justify-content: space-around;
}

.no-comics-no-life2{
                              margin-top: 0%;
                              display:flex ;
                              justify-content: space-around;

}

.no-comics-no-life3{
                              margin-top: 0%;
                              display:flex ;
                              justify-content: space-around; }

.information2{
                              margin-top: 10%;
                              padding-left: 1px;
                              flex-basis: 50%;
}

.information2 p{
                              margin-top:0%;
                              padding-left: 1px;
                              text-align: center;
}

.information3 p{
                              margin-top:0%;
                              padding-left: 1px;
                              font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                              text-align: center;
}

.text{
                              font-family: 'M PLUS Rounded 1c', sans-serif;
font-family: 'Sawarabi Gothic', sans-serif;
                      

}


.daimei{
                               font-size: 40px;
                               text-align:center ;
                               margin-top: 30%;
                               font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;      
}

.daimei1{
                              font-size: 40px;
                              text-align:center ;
                              margin-top: 30%;
                              font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;      
                            

}



.blue-period{
                              width:100% ;
}



.information3{
                              flex-basis: 50%;
                              margin-top:10%;
}

.information3 p{
                              margin-top:0%;
                              padding-left:1px;
                              font-family: 'M PLUS Rounded 1c', sans-serif;
                              font-family: 'Sawarabi Gothic', sans-serif;
                              text-align:center;

}



