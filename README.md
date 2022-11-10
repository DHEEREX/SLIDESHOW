<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Image Slider</title>
    <style>
      @keyframes fade {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

* {
  padding: 0;
  border: 0;
  box-sizing: border-box;
}

body {
  height: 100%;
}

body h1 {
  text-align: center;
}

.slide-container {
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 1000px;
  margin: auto;
  position: relative;
}

.slide-container .slide {
  display: none;
  width: 100%;
}

.slide-container .slide.fade {
  animation: fade 0.5s cubic-bezier(0.55, 0.085, 0.68, 0.53) both;
}

.slide-container .slide img {
  width: 100%;
}
    </style>
  </head>
  <body>
    <h1>Image Slider</h1>
    <div class="slide-container">
       <div class="slide fade">
        <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpoWsSiuhYOJtYLjVk0UAOhgqmflXVJ-sySg&usqp=CAU' alt=''>
      </div>
      <div class="slide fade">
        <img src='https://stayglam.com/wp-content/uploads/2019/03/Unique-Braided-Bob-1.jpg' alt=''>
      </div>
      <div class="slide fade">
        <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ2ICBDGvOSu2CoitjJhapgyuv2Kri23ahrZw&usqp=CAU' alt=''>
      </div>
      <div class="slide fade">
        <img src='https://leurr.com/wp-content/uploads/2022/07/266841304_455196606225068_8172323916080847629_n-819x1024.jpg' alt=''>
      </div>
       <div class="slide fade">
        <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMSY7xegHGC79yWQSLRu7t4zz98PBgTVd3aSai2_HnR-xspQahcsTo50VBf4yzfDw325k&usqp=CAU' alt=''>
      </div>
       <div class="slide fade">
        <img src='https://i.pinimg.com/originals/b9/c2/11/b9c2110b35633120b06d7b8f4aba83db.jpg' alt=''>
      </div>

      <a href="#" class="prev" title="Previous">&#10094</a>
      <a href="#" class="next" title="Next">&#10095</a>
    </div>
    <div class="dots-container">
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
    </div>
  </body>
</html>
