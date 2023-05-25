<style>
.wrap {
  margin-top: 150px;
  perspective: 1000px;
  perspective-origin: 50% 50%;
}

.cube {
  margin: auto;
  position: relative;
  height: 200px;
  width: 200px;
  transform-style: preserve-3d;
}

.cube > div {
  position: absolute;
  box-sizing: border-box;
  padding: 10px;
  height: 100%;
  width: 100%;
  opacity: 0.9;
  background-color: #000;
  border: solid 1px #eeeeee;
  color: #ffffff;
}

.front {
  transform: translateZ(100px);
  transition: 3s; 
}

.back {
  transform: translateZ(-100px) rotateY(180deg);
  transition: 3s; 
}

.right {
  transform: rotateY(-270deg) translateX(100px);
  transform-origin: top right;
  transition: 3s; 
}

.left {
  transform: rotateY(270deg) translateX(-100px);
  transform-origin: center left;
  transition: 3s; 
}

.top {
  transform: rotateX(-270deg) translateY(-100px);
  transform-origin: top center;
  transition: 3s; 
}

.bottom {
  transform: rotateX(270deg) translateY(100px);
  transform-origin: bottom center;
  transition: 3s; 
}

@keyframes rotate {
  from {
    transform: rotateX(0deg) rotateY(0deg);
  }
  
  to {
    transform: rotateX(360deg) rotateY(360deg);
  }
}

.cube {
  animation: rotate 20s infinite linear;
}

.wrap:hover .front {
  transform: translateZ(200px);
  transition: 3s; 
}

.wrap:hover .back {
  transform: translateZ(-200px) rotateY(180deg);
  transition: 3s;
}

.wrap:hover .right {
  transform: rotateY(-270deg) translateZ(100px) translateX(100px);
  transition: 3s;
}

.wrap:hover .left {
  transform: rotateY(270deg) translateZ(100px) translateX(-100px);
  transition: 3s;
}

.wrap:hover .top {
  transform: rotateX(-270deg) translateZ(100px) translateY(-100px);
  transition: 3s;
}


.spinner {
    font-size: 17px;
    text-indent: -999em;
    position: relative;
    border-radius: 48%;
    overflow: hidden;
    width: 0em;
    height: 0em;
    margin: 6em auto;
    box-shadow: none;
    animation: spin6 2s infinite linear  alternate-reverse;
    animation-direction: alternate-reverse;
}
@keyframes spin6 {
    15% {
        box-shadow: -1.5em -1.5em 0 0.2em green, -1.5em 1.5em 0 0.2em blue, 1.5em 1.5em 0 0.2em red, 1.5em -1.5em 0 0.2em yellow;
        transform: rotate(0.25turn);
    }
    80% {
        width: 10em;
        height: 10em;
        margin: 1em auto;
        transform: rotate(2turn);
    }
}

.wrap:hover .bottom {
  transform: rotateX(270deg) translateZ(100px) translateY(100px);
}
</style>

<div class="wrap">
    <div class="cube">
      <div class="front">
      <div class="spinner"> </div>
      </div>
      <div class="back">
          <div class="spinner"> </div>
      </div>
      <div class="top">
       <div class="spinner"> </div>
      </div>
      <div class="bottom">
       <div class="spinner"> </div>
      </div>
      <div class="left">
          <div class="spinner"> </div>
      </div>
      <div class="right">
        <div class="spinner"> </div>
      </div>
    </div>
  </div>
  
  





[![GitHub Streak](https://streak-stats.demolab.com/?user=Sardorbecakhmedov&theme=dark)](https://github.com/Sardorbecakhmedov/)<br/>
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=zuhriddinzayniddinov&text_color=ffffff&text_bold=true&title_color=e3289c&bg_color=2b213a&card_width=495px)](https://github.com/zuhriddinzayniddinov/)</div>


<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=zuhriddinzayniddinov&show_icons=true&theme=synthwave" alt="Zuhriddin :: Profile Stats" /></p>
