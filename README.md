# tainaifoods
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="Firefox">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>台南食記</title>
    <link rel="icon" href="期末專題圖片/Food_437572.png" type="image/x-icon/">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
    <link rel="stylesheet" href="mycss.css">
    
        <style>
          ul li {font-size: 20px;}
             
        .kv{width: 100%;  /*.kv 首頁大圖*/
            height: 100vh;
            background-image: url(https://picsum.photos/1900/1200?blur); /*隨機圖 1900*1200（滿板封面 可適應各尺寸）?blur屬性：模糊*/
            background-size: cover;
            
        }
        .kv .text{text-align: center;} /*設定封面的位置在中間*/
        .kv .container{height: 100%;}
        .kv .container>.row{height: 100%;}


        .ml3 {
                font-weight: 900;
                font-size: 3.5em;
              }

        #p-c{
          color: black;
          background-color: #fff;
          font-size: 10px;
        }      
        .sitestatesJs {
 	display: block;
 	padding: 3px;
}


        </style>
         
</head>
<body style="background-color: rgba(101, 207, 145, 0.377);"  >
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js" referrerpolicy="no-referrer"></script>
<script src="myjs.js"></script>
<script src="js/bootstrap.bundle.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<div class="bg"> <img src="期末專題圖片/back_2.jpg" alt="" > </div>


<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>

 <nav class="navbar fixed-top navbar-expand-lg navbar-dark p-md-3">  <!--navbar-expand-lg 響應式折疊-->
  <div class="container-fluid">
    <a class="navbar-brand " href="#"><img src="期末專題圖片/logo icon.jpeg" alt="" width="40"> 台南食記</a> <!--navbar-brand 放網頁logo-->
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
    <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
          <div class="mx-auto"></div>
          <ul class="navbar-nav"> 
            <li class="nav-item"> 
              <a class="nav-link text-white" href="網頁首頁.html">首頁</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="https://www.tainan.gov.tw/">關於台南</a>
            </li>
           
            <li class="nav-item dropdown"> <!--下拉式選單-->
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false"> 
              地區美食
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="中西區 .html">中西區</a></li>
              <li><a class="dropdown-item" href="東區.html">東區</a></li>
            
              <li><a class="dropdown-item" href="安平區.html">安平區</a></li>
            </ul>
          </li>
          
          </ul>
        </div>
      </div>
    </nav>
    <div>
   


  
    <script type="text/javascript">
      var nav = document.querySelector('nav');

      window.addEventListener('scroll', function () {    //偵測滾動軸 若y軸大於100 則 添加.bg-dark 至 nav
        if (window.pageYOffset > 100) {
          nav.classList.add('bg-dark', 'shadow');
        } else {
          nav.classList.remove('bg-dark', 'shadow');
        }
      });
      
    </script> 








      <div class="kv"><!--網站第一部份封面大圖-->
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-8 col-md-6">
                    <div class="text">
                        <h1 style="color: aquamarine; background-color: rgba(0, 0, 0, 0.623); ">台南<br>-----<br>食記 </h1>
                      
                    </div>
                </div>
            </div>
        </div>
    </div> 
  
      <div class="container-fluid "> <!--左半編導覽-->
        <div class="row">
          <div class="col-2 col-xs-2 ">
            
            <nav id="sidebar"> <!--導覽-->
             
              <button type="button" id="collapse" class="collapase-btn">
                <i class="bi bi-bookmark-star-fill"></i>
              </button>
              <h3 >地區美食</h3>
              <ul>

                  <div>
                  <li> <a href="中西區 .html" >中西區</a> </li>
                  <li> <a href="東區.html"> 東區</li></a>
                  <li> <a href="安平區.html">安平區</li></a> 
                  </div>
              </ul>
              <h3>觀光地區推薦</h3>
              <ul class="navbar" >
                <div>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=147">安平古堡</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=R171">關子嶺溫泉</a></li>
                  <li><a href="taiwan.net.tw/m1.aspx?sNo=0001119&id=10889">赤崁樓</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=149">億載金城</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=2118">延平郡王祠</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=10914">草山月世界</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=2117">祀典武廟</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=10352">七股鹽山</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=A12-00135">北門遊客中心  </a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=12173">西拉雅風景區</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=A12-00076">台江國家公園</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=R105">南鯤身代天府</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=2575">虎頭埤風景區</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=A12-00023">井仔腳瓦盤鹽田</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=R16">大天后宮</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=2574">奇美博物館</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=A12-00018">七股瀉湖</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=2">曾文水庫</a></li>
                  <li><a href="https://www.taiwan.net.tw/m1.aspx?sNo=0001119&id=R76">走馬瀨農場</a></li>
               </div>
              </ul>
           </nav> 
          </div>
          <div class="col-8">
           

          <div class="main text-center"> <!--主要內容-->
            <h1>-----台南美食地圖------</h1>
            <div style="background-color: rgba(65, 83, 83, 0.548) ; color:rgba(138, 47, 47, 0.555) ; font-family: cursive; "class="lh-lg" >
            <h5 class="text-decoration-underline" id="mainh5" >
               臺南市是臺灣的發祥地，是全臺歷史最悠久的都市。<br></h5>
              西元1661年，鄭成功來台驅荷後，在臺南開府設治，屯墾拓殖，勵精圖治，當時中國大陸居民移居來臺者紛至沓來，商船雲集，市內商店櫛比，臺南都會之規模至是奠定。惟鄭王英年早歿，子經繼起，設聖廟、創學校，銳意經營，民生利賴。<br>
        
                至西元1683年，清國平臺，在臺南設臺灣府，為全臺首府。<br>
                西元1885年，臺灣建省，遂改臺灣府為臺南府，是為臺南得名之緣由。<br>
                直至十九世紀末期，臺南一直是臺灣政治經濟文化之重心，由於這層歷史淵源，故臺南市古蹟名勝特多，佔有臺灣最悠久歷史及文化發展地位，稱為文化古都，聞名全臺，實有其緣由也。<br>
                
                除了歷史文化特色之外，臺南更擁有如詩畫般的自然生態美景，及聞名遐邇的農漁產品特色美食。<br>
                春天擁有聞名的「臺灣國際蘭展」於後壁鄉臺灣蘭花生物科技園區，讓您一探早春蘭花嬌羞的風情；每年農曆正月十五更有壯觀的鹽水蜂炮，在在吸引國內外人士前往觀賞；夏天寓教於樂的梅嶺賞螢、白河賞蓮及赤嘴園活動，讓您與孩子透過生態教育聯繫感情；涼爽的秋季，可以到東山一嚐香醇的阿拉比卡咖啡；到了冬天還可以到關子嶺感受泥漿溫泉，讓疲憊的心在溫泉鄉得到解放。
                
                這般的臺南之美，美得有如活生生的歷史博物館，美在那一望無垠的田園風光，美在淳樸及熱情的人心，值得您細細品味。</h5></div>
            <p>現在，現在就利用美食，來探索台南吧！</p>
          
            <h2 style="color:rgba(138, 47, 47, 0.555); ;">影片介紹</h2> 
            <iframe width="560" height="315" src="https://www.youtube.com/embed/ivfIKHRrrq8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            
          </div>
          
        </div>



            <div class="col-2 text-center"><!--右半編導覽-->
              <nav >
                <h3>台南市相關</h3>
              <ul style=" background-color: rgba(86, 124, 111, 0.774);" >
                <li><a href="https://www.twtainan.net/">台南旅遊網</a></li>
                <li><a href="https://www.tainan.gov.tw/">台南市政府</a></li>
                <li><a href="https://2384.tainan.gov.tw/NewTNBusWeb/">大台南公車</a></li>
                <li><a href="https://news.ltn.com.tw/list/breakingnews/Tainan">台南市即時新聞</a></li>
                <li><a href="https://www.tainan.gov.tw/News.aspx?n=22873">疫情專區</a></li>
              </ul>
            </nav>
            <script src="https://SiteStates.com/show/js_text/062f86bed0505e0bb17244540b4bcf3f" type="text/javascript"></script>
            </div>
          </div>
        </div>
      </div>
    
      

      <div class="container">
        <div class="row justify-content-center">
          <div class="col-12 col-xl-6">
            <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
              <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
              </div>
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="期末專題圖片/億載金城.jpeg" class="d-block w-100" alt="..." height="400">
                </div>
                <div class="carousel-item">
                  <img src="期末專題圖片/羅拉.jpg" class="d-block w-100" alt="..." height="400">
                </div>
                <div class="carousel-item">
                  <img src="期末專題圖片/沼澤.jpg" class="d-block w-100" alt="..." height="400">
                </div>
                

              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
        </div>
      </div>




<div class="container-fluid">
  <div class="row">
    <div class="col-12 col-md-6 col-xl-3 ">
      <div class="card" style="width: 20rem;">
        <img src="news/php7LOYk3.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">謠言終結站》台南車站確診4千人？ 南市衛生局：不實消息</h5>
          <p class="card-text" id="p-c">
            網傳「臺南車站確診4000人」經台南市政府衛生局確認為不實訊息後，警察局遂據以調查。本案經查係由Twitter帳號ID：「北城浪子」在111年4月2日17時17分在Twitter 發表假訊息文章，後續再由「過分天真」
            粉絲專頁於同日17時48分於臉書截圖發表相同內容文章，相同模式Twitter帳號ID：「潯川」亦在111年4月2日發表類似內容文章，並由「浮淺Superficial」...</p>
          <a href="https://news.ltn.com.tw/news/Tainan/breakingnews/3943220" class="btn btn-primary">更多詳情</a>
        </div>
      </div>

    </div>
    <div class="col-12 col-md-6 col-xl-3 ">
      <div class="card" style="width: 20rem;">
        <img src="news/3942852_1_1.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">台南機車連環撞 3車5人摔車</h5>
          <p class="card-text" id="p-c">
            台南市東區中華東路2段上28日中午發生1件看起來頗驚悚的連環車禍，1輛單人機車（A車）先擦撞右前方1輛雙載人的機車（B車），再波及前方的雙載人機車（C車）及另1輛機車（D車人未倒地），
            A、B、C這3車共3男2女倒地受傷，其中A車男騎士傷勢較重送醫，相關肇事者經酒測均無酒駕情形，警方進一步調查、釐清肇事責任。</p>
          <a href="https://news.ltn.com.tw/news/Tainan/breakingnews/3942852" class="btn btn-primary">更多詳情</a>
        </div>
      </div>
      
    </div>
    <div class="col-12 col-md-6 col-xl-3 ">
      <div class="card" style="width: 20rem;">
        <img src="news/3942707_1_1.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">改裝車擾安寧 台南永康1～5月已取締160件</h5>
          <p class="card-text" id="p-c">永康分局交通組長葉敏旭表示，永康分局於1至5月已執行13次「環警監稽查」專案性勤務，每晚10時至隔天早上6時，於轄區「永大路二段與永明街」
            等14處，及轄內重要路段及改裝車輛易聚集熱點，採多點式守望稽查攔檢勤務，並不定時更換執法路段，使有心逃避稽查民眾無所遁形...</p>
          <a href="https://news.ltn.com.tw/news/Tainan/breakingnews/3942707" class="btn btn-primary">更多詳情</a>
        </div>
      </div>
      
    </div>
    <div class="col-12 col-md-6 col-xl-3 ">
      <div class="card" style="width: 20rem;">
        <img src="news/3942681_2_1.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">女網友誘投資精品 60歲男中招險失85萬</h5>
          <p class="card-text" id="p-c">台南市警局一分局於近日中午接獲金融機構行員通報指有1名年近60歲的男子欲將85萬台幣轉帳到陌生人銀行帳戶，行員關懷提問，男子說話卻吞吞吐吐有異。
            警方到場了解，得知男子的1名女網友要他匯款投資85萬元買國外名牌精品轉賣牟利，由於男子匯款帳戶是警示帳戶，確認是假愛情降臨的詐騙案...

            
            </p>
          <a href="https://news.ltn.com.tw/news/Tainan/breakingnews/3942681" class="btn btn-primary">更多詳情</a>
        </div>
      </div>
      
    </div>
    
  </div>
</div>
    
   


  
   
    <footer class="bg-light text-center text-lg-start">
      <div class="text-center p-3 " style="background-color: rgba(0,0,0,0.2);">
        系統四甲 4a739048 李維宸 動態網頁設計 期末專題 <br> 2022/05/19 
      </div>

    </footer>
     


    
</body>
</html>
