***HTML***

<div class="container">
    <div class="white-square1"></div>
    <img class="img" src="./assets/alan_kay.jpg">
</div>


***CSS***

.container{
   display:inline-block;
   position:relative;
}
.white-square{
    height:200px;
    width: 250px;
    background-color:white;
    position: absolute;
}

****JS****
const whiteSquare1= document.querySelector('.white-square1')
function clearTopHalf1(){
    whiteSquare1.setAttribute("class", "white.square");
}
clearTopHalf1();
