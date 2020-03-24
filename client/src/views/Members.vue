<template>

<section class="our-webcoderskull padding-lg">
  <div class="container">
    <div class="row heading heading-icon">
      <br>
      <br>
      <br>
        <h2>THE TEAM</h2>
    </div>
    <ul class="row">
      <li class="col-12 col-md-6 col-lg-3">
          <div class="cnt-block equal-hight">
            <figure><img src="../assets/davidrockwell.jpg" class="img-responsive" alt=""></figure>
            <h3><a href="#">David Rockwell</a></h3>
            <p>8243 E. Amherst Street Zanesville, OH 43701</p>
            <p>davidrockwell@gmail.com</p>
            <br>
            <button class="btn btn-outline-dark my-2 my-sm-0 mr-3" type="submit">view</button>
            <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">add friend</button>
            
          </div>
      </li>
      <li class="col-12 col-md-6 col-lg-3">
          <div class="cnt-block equal-hight">
            <figure><img src="../assets/marcelwanders.jpg" class="img-responsive" alt=""></figure>
            <h3><a href="#">Marcel Wanders </a></h3>
            <p>57 Rosewood Lane Mebane, NC 27302</p>
            <p>marcelwanders@gmail.com</p>
            <br>
            <button class="btn btn-outline-dark my-2 my-sm-0 mr-3" type="submit">view</button>
            <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">add friend</button>
          </div>
      </li>
      <li class="col-12 col-md-6 col-lg-3">
          <div class="cnt-block equal-hight">
            <figure><img src="../assets/kellywearstler.jpg" class="img-responsive" alt=""></figure>
            <h3><a href="#">Kelly Wearstler</a></h3>
            <p>750 Cactus Drive Kenosha, WI 53140</p>
            <br>  
            <p>kellywearstler@gmail.com</p>  
            <br>
            <button class="btn btn-outline-dark my-2 my-sm-0 mr-3" type="submit">view</button>
            <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">add friend</button>
          </div>
       </li>
    </ul>

    <div class="container">
    <ul class="row">
      <li class="col-12 col-md-6 col-lg-3">
          <div class="cnt-block equal-hight" >
            <figure><img src="../assets/nateberkus.jpg" class="img-responsive" alt=""></figure>
            <h3><a href="#">Nate Berkus</a></h3>
            <p>47 6th Lane Logansport, IN 46947</p>
            <br>  
            <p>nateberkus@gmail.com</p>
            <br>
            <button class="btn btn-outline-dark my-2 my-sm-0 mr-3" type="submit">view</button>
            <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">add friend</button>
         
          </div>
      </li>
      <li class="col-12 col-md-6 col-lg-3">
          <div class="cnt-block equal-hight" >
            <figure><img src="../assets/philippestarck.jpg" class="img-responsive" alt=""></figure>
            <h3><a href="#">Philippe Starck </a></h3>
            <p>8215 Fairfield Drive Amityville, NY 11701</p>
            <p>philippestarck@gmail.com</p>
            <br>
            <button class="btn btn-outline-dark my-2 my-sm-0 mr-3" type="submit">view</button>
            <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">add friend</button>
            
          </div>
      </li>
      <li class="col-12 col-md-6 col-lg-3">
          <div class="cnt-block equal-hight">
            <figure><img src="../assets/tomdixon.jpg" class="img-responsive" alt=""></figure>
            <h3><a href="#">Tom Dixon </a></h3>
            <p>7743 Dunbar Ave. Homestead, FL 33030</p>
            <p>tomdixon@gmail.com</p>
            <br>
            <button class="btn btn-outline-dark my-2 my-sm-0 mr-3" type="submit">view</button>
            <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">add friend</button>
            
          </div>
      </li>
      
    </ul>
    </div>
  </div>
</section>
</template>

<style>
@font-face {
  font-family: Calisto;
  src: url(/fonts/CalistoMT.ttf);
}
.row.heading h2 {
  font-family: Calisto; 
  color: rgb(46, 46, 46);
  font-size: 45px;
  font-style: italic;
  text-decoration: underline;
  font-weight: bold;
  line-height: 95px;
  text-align: center;
  margin: 0 0 40px;
  padding-bottom: 20px;

}
ul{
  margin:0;
  padding:0;
  list-style:none;
}
.heading.heading-icon {
    display: block;
}
.padding-lg {
	display: block;
	padding-top: 40px;
	padding-bottom: 30px;
}
.practice-area.padding-lg {
    padding-bottom: 55px;
    padding-top: 20px;
}
.practice-area .inner{ 
    border:1px solid #999999;
    text-align:center; 
    margin-bottom:28px; 
    padding:40px 25px;
}
.our-webcoderskull .cnt-block:hover {
    box-shadow: 0px 0px 10px rgba(105, 105, 105, 0.3);
}

.practice-area .inner img{
	display:inline-block;
}


.our-webcoderskull{
  background: #fff no-repeat center top / cover;
  
}
.our-webcoderskull .cnt-block{ 
   display: inline-block;
   text-align: center; 
   width:100%; 
   background:#fff; 
   padding: 50px 20px; 
   text-align:center; 
   margin: 20px 20px 20px 130px;
}
.our-webcoderskull .cnt-block figure{
   width:210px; 
   height:250px; 
   border-radius:100%; 
   display:inline-block;
  
}
.our-webcoderskull .cnt-block img{ 
   width:210px; 
   height:250px; 
   border-radius:40%; 
}
.our-webcoderskull .cnt-block h3{ 
  font-family: Calisto; 
  font-style: italic; 
   color:#2a2a2a; 
   font-size:20px; 
   font-weight:500; 
   padding:6px 0;
}
.our-webcoderskull .cnt-block h3 a{
  text-decoration:none;
	color:#2a2a2a;
}
.our-webcoderskull .cnt-block h3 a:hover{
	color:#000000;  
}
.our-webcoderskull .cnt-block p{ 
   color:#2a2a2a; 
   font-size:13px; 
   line-height:20px; 
   font-weight:400;
   text-align: center;
   margin-bottom: 10px; 
}

</style>