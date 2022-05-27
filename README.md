# Flexbox-ile-ilk-sitem
Html Kodları
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adventure Time</title>
    <link rel="stylesheet" href="adventuretime.css">
    <!--Css ile Html İletişim-->
</head>

<body>
    <div class="container">
        <div class="item1">
          <div class="div1">
              <ul class="li">
                  <li>Adventure</li>
                  <li>Time</li>
              </ul>

          </div>
          <div class="div2"> <img width="200" height="70"src="https://www.pngmart.com/files/13/Adventure-Time-Jake-And-Finn-PNG-Transparent.png" alt=""></div>
        </div>

        <div class="itemm">
            <div class="item2">
                <div class="kutu"><ul class="r">
                    <li>Finn</li><br>
                    <li>Köpek Jake</li><br>
                    <li>BMO </li>
                </ul></div>
                <div class="kutu1"><img width="200" height="149" src="https://i.ytimg.com/vi/P_Vo6wrUhQQ/maxresdefault.jpg" alt="resim"></div>
            </div>
            <div class="item3">
               <div class="r1"><img width="200" height="149" src="https://i.pinimg.com/236x/a4/34/d5/a434d5be26b1eaa7376f567d893fb969.jpg" alt=""></div>
               <div class="r2" >Adventure Time, Cartoon Network için Frederator Studios ve Cartoon Network Studios ile Pendleton Ward tarafından yapılmış olan bir Amerikan çizgi dizisidir. Seri, Finn adındaki bir insan çocuk ve esneyerek büyüyebilme, şekil değişebilme gibi sihirli güçlere sahip en iyi arkadaşı ve üvey kardeşi olan köpek Jake'in maceralarını anlatmaktadır. Finn ve Jake post apokaliptik Ooo Diyarı'nda Prenses Ciklet, Buz Kralı, Marceline, BMO ve diğer karakterlerle birlikte yaşamaktadır.</div>
               <div class="r3">İlk olarak 2007 yılında Nickelodeon'ın Random! Cartoons adlı programında pilot bölümü yayınlanmıştır. Pilot bölüm internette popüler olsa da Nickelodeon yöneticileri kabul etmemişlerdir. Daha sonra Cartoon Network tarafından alınıp, 5 Nisan 2010'da yayınlanmaya başlamıştır. Türkiye'de ilk kez TNT kanalında 2 Temmuz 2011'de çıkmış, daha sonra da 1 Ağustos 2011'de Cartoon Network tarafından yayınlanmaya başlanmıştı.</div>
               <div class="geenel">
                    <div class="r4"></div>
               <div class="r5"></div>
               <div class="r6"></div>
               </div>
              
            </div>
        </div>



        <div class="item4">
            <div class="item41">Karakterler </div>
            <div class="item41">Ana Karakterler</div>
            <div class="item41"> Diğer Karakterler</div>
            <div class="item41"> Konu</div>
        </div>
    </div>

</body>

</html>
CSS Kodları
*{
margin:0px;
padding:0px;
}
.container{
    background-color: antiquewhite;
    display:flex;
    flex-direction: column;
    
    
   margin: 0 50px;
}
.item1{
    background-color: black;
    border-radius:10px;

}
.div1{
    
    width:20%;
    background-color: pink;
    float:left;
    height: 73px;
    border-radius:10px;

}
.div2{
       width:20%;
      
       float:right;
        
    
    
}
li{
    list-style: none outside none;
    display: inline;
    
}
.itemm{
    background-color:rgba(187, 193, 201, 0.295) ;

}
.item2{
   
    background-color: rgba(187, 193, 201, 0.295);
   width: 21%;
    float:left; 
 
    
  
   

    
}
.kutu{
 background-color: pink;
 width: 100%;
 height: 149px;
   border-radius:10px;

}
.kutu1{
    background-color: pink;
    width:30%;
   
}
.item3{
    background-color: rgba(187, 193, 201, 0.295);
  width: 75%;
  margin-left:10px;
   float:left;
   border-radius: 10px;
   
    
}
.r1{
    background-color: rgba(187, 193, 201, 0.295);
    width:20%;
    float:left;


}

.r2{
    background-color: rgba(187, 193, 201, 0.295);
    width:70%;
    float:left;
    height: 149px;
    margin-left:60px;
    border-radius: 10px;
    
}
.r3{
    background-color: rgba(187, 193, 201, 0.295);
    width:100%;
   height: 75px;
   margin-top: 160px;
   border-radius: 10px;
    
}
.geenel{
    
    width:100%;
    height: 60px;
    display: flex;
    flex-wrap: wrap;
    align-content: space-around;
    justify-content: space-between;
    align-items: flex-start;
}
.r4{
    background-color: pink;
    width:20%;
    height: 50px; 
    float:left;
    border-radius: 10px;
    
}
.r5{
    background-color: pink;
    width:20%;
    height: 50px;
    float: left;
    border-radius: 10px;
    
    
}
.r6{
    background-color: pink;
    width:20%;
    height: 50px;
    float: left;
    border-radius: 10px;
    
    
}

.item4{
    background-color: pink;
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-evenly;
}
.item41{
 width: 20%;
 height: 40px;
 
}
.r{
    list-style: none outside none;
    text-align: center;
}

