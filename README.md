<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>巅峰哥——官网</title>
    <style>
        *{
            margin: 0%;
        }
        h1{
            text-align: center;
            background-color: aqua;
            color: ivory;
            line-height: 100px;
        }
    </style>
</head>
<body>
    <h1>
        欢迎访问
    </h1>
<!--轮播图-->
   <div>
<style>

*{

margin: 0;

padding: 0;

list-style: none;

text-decoration: none;

}

#banner{

width: 500px;

height: 500px;

overflow: hidden;

border: 2px solid #999;

position: relative;

}

#banner img{

width: 800px;

height: 500px;

}

#imglist{

width: 4000px;

height: 400px;

}

#imglist li{

float: left;

}

#icolist{

position: absolute;

right: 10px;

bottom: 10px;

}

#icolist li{

float: left;

width: 30px;

height: 30px;

border-radius: 50%;

background: #666;

color: #fff;

margin-left: 5px;

text-align: center;

line-height: 30px;

cursor: pointer;

}

.prev{

background: #666;

height: 40px;

width: 30px;

position: absolute;

left: 5px;

top: 45%;

color: #fff;

line-height: 40px;

text-align: center;

cursor: pointer;

}

.next{

background: #666;

height: 40px;

width: 30px;

position: absolute;

right: 5px;

top: 45%;

color: #fff;

line-height: 40px;

text-align: center;

cursor: pointer;

}

</style>

</head>

<body>

<div id="banner">

<ul id="imglist">

<li><a href=""><img src="http://cdn.u1.huluxia.com/g4/M01/B5/08/rBAAdmMyzYiAeqebAAUW_DMW5dQ256.jpg" alt=""></a></li>

<li><a href=""><img src="img/pic2.jpeg" alt=""></a></li>

<li><a href=""><img src="http://cdn.u1.huluxia.com/g4/M01/B5/08/rBAAdmMyzYiAeqebAAUW_DMW5dQ256.jpg" alt=""></a></li>

<li><a href=""><img src="img/pic4.jpeg" alt=""></a></li>

<li><a href=""><img src="http://cdn.u1.huluxia.com/g4/M01/B5/08/rBAAdmMyzYiAeqebAAUW_DMW5dQ256.jpg" alt=""></a></li>

</ul>

<ul id="icolist">

<li>1</li>

<li>2</li>

<li>3</li>

<li>4</li>

</ul>

<div class="prev">《</div>

<div class="next">》</div>

</div>

<div id="test"></div>

<script>

var esico = document.getElementById('icolist').getElementsByTagName('li');

var eicolist = document.querySelector('#icolist');

var eimglist = document.querySelector('#imglist');

var etest = document.querySelector('#test');

var eprev = document.querySelector('.prev');

var enext = document.querySelector('.next');

var left = 0;

var timer;

esico[2].style.backgroundColor = 'red';

run();

// alert(Math.floor(3190/800));

function run(){

if (left <= -3200) {

left = 0;

}

var m = Math.floor(-left/800) ;

imglist.style.marginLeft = left + 'px';

var n = (left % 800 == 0) ? n = 1200 : n = 6;

left -= 10;

icochange(m);

timer = setTimeout(run,n);

}

function icochange(m){

for (let index = 0; index < esico.length; index++) {

esico[index].style.backgroundColor = '';

}

if (m < esico.length) {

esico[m].style.backgroundColor = 'red';

}

}

function imgchange(n){

let lt = - (n  * 800)

imglist.style.marginLeft = lt + 'px';

left = lt;

}

eprev.onclick = function(){

let prevgo = Math.floor(-left/800)-1;

if (prevgo == -1) {

prevgo =3;

}

imgchange(prevgo);

icochange(prevgo);

}

enext.onclick = function(){

let nextgo = Math.floor(-left/800)+1;

if (nextgo == 4) {

nextgo =0;

}

imgchange(nextgo);

icochange(nextgo);

}

eicolist.onclick = function(){

var tg = event.target;

let ico = tg.innerHTML - 1;

imgchange(ico);

icochange(ico);

}

eimglist.onmouseover = function(){

clearTimeout(timer);

}

eimglist.onmouseout = function(){

run();

}



</script>

</body>

</html>
   </div>
<!--轮播图-->

<div>

</div>
<p>
    杨癫疯  卷毛狗  杨土狗 杨智障  杨傻逼，我告诉你一个秘密，其实我天天超你妈，我一天跟你妈干3次，分别是:
</p>
<p>
    ①在早上 7:30 你上学之后直接干30分钟 然后我再去学校
</p>
<p>
    ②在中午 1:20 的时候 你去上学了以后 我直接去你家跟你妈干30分钟，干到 1:50 我再去学校
</p>
​③在晚上凌晨 2:30 的时候，你已经睡觉了，我直接悄悄地去你家 然后跟你妈在厕所里面偷偷的干，这第3次的时候是我最开心的时候，因为可以足足干2小时，干完以后我就回家睡觉了
​对了，你能不能爱文明一点 上个学期的时候 一双鞋子穿了半个学期，爱文明点吧，你妈都那么爱文明 射的时候都叫我射在B里面 不要射在其它地方



<p>
    (特此声明:我没有针对某人  请不要对号入座，谢谢)
</p>

</body>
</html>
<style>
    body {
        background-color:#d0e4fe;
    }
    h1 {
        color:orange;
        text-align:center;
    }
    p {
        font-family:"Times New Roman";
        font-size:20px;
    }
    </style>
