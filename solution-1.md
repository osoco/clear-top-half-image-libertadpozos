***HTML***
<img class="img" src="./assets/alan_kay.jpg">

***CSS***
.half{
    position: absolute;
    clip: rect(150px,250px,359px,0px);
}

***JS***
const imgEl= document.querySelector('.img');

function clearTopHalf(){
    imgEl.setAttribute("class", "half");
}
clearTopHalf();

