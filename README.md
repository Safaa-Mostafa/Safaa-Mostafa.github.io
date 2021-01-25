<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>module2-solution</title>
   <style>
* {
    box-sizing: border-box;
  }
  h1 {
    margin-bottom: 15px;
    text-align: center;
    background-color:lightcoral;
    color:black;
  }
  
  #Item1, #Item2, #Item3 {
    float: right;
    background-color:pink;
    width: 100px;
    text-align: center;
    border: 1px solid black;
    left: 50px;
  }
  
  p {
    background-color: none;
    font-family: Monaco;
    color: black;
    padding: 10px;
    clear: both;
  }
  
  .container {
    border: 1px solid black;
    background-color: rgba(224, 127, 184, 0.329);
    height: 100%;
    position: relative;
    margin: 12px;
  }
  

  .row {
    width: 100%;
  }
  

  @media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
      float: left;
    }
    .col-lg-1 {
      width: 8.33%;
    }
    .col-lg-2 {
      width: 16.66%;
    }
    .col-lg-3 {
      width: 25%;
    }
    .col-lg-4 {
      width: 33%;
    }
    .col-lg-5 {
      width: 41.66%;
    }
    .col-lg-6 {
      width: 50%;
    }
    .col-lg-7 {
      width: 58.33%;
    }
    .col-lg-8 {
      width: 66.66%;
    }
    .col-lg-9 {
      width: 74.99%;
    }
    .col-lg-10 {
      width: 83.33%;
    }
    .col-lg-11 {
      width: 91.66%;
    }
    .col-lg-12 {
      width: 100%;
    }
  }

  @media (min-width: 767px) and (max-width: 991px) {
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
      float: left;
    }
    .col-md-1 {
      width: 8.33%;
    }
    .col-md-2 {
      width: 16.66%;
    }
    .col-md-3 {
      width: 25%;
    }
    .col-md-4 {
      width: 33.33%;
    }
    .col-md-5 {
      width: 41.66%;
    }
    .col-md-6 {
      width: 48%;
    }
    .col-md-7 {
      width: 58.33%;
    }
    .col-md-8 {
      width: 66.66%;
    }
    .col-md-9 {
      width: 74.99%;
    }
    .col-md-10 {
      width: 83.33%;
    }
    .col-md-11 {
      width: 91.66%;
    }
    .col-md-12 {
      width: 96%;
    }
  }</style>
</head>
<body>
<h1>Our Menu</h1>

<div class="row">
  <div class="col-lg-4 col-md-6">
        <div class="container"> 
        <div id="Item1">Chicken</div>
            <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit. 
                    Aenean commodo ligula eget dolor. 
                    Aenean massa. Cum sociis natoque 
                    penatibus et magnis dis parturient 
                    montes, nascetur ridiculus mus. Donec 
            </p>
        </div>
</div>
  <div class="col-lg-4 col-md-6">
        <div class="container"> 
        <div id="Item2">Beef</div>
            <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit. 
                    Aenean commodo ligula eget dolor. 
                    Aenean massa. Cum sociis natoque 
                    penatibus et magnis dis parturient 
                    montes, nascetur ridiculus mus. Donec 
            </p>
        </div>
</div>
  <div class="col-lg-4 col-md-12">
    <div class="container"> 
    <div id="Item3">Sushi</div>
            <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit. 
                    Aenean commodo ligula eget dolor. 
                    Aenean massa. Cum sociis natoque 
                    penatibus et magnis dis parturient 
                    montes, nascetur ridiculus mus. Donec 
            </p>
    </div>
  </div>
</div>

</body>
</html
