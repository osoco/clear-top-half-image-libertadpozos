**HTML** 
 <div class="container">
    <img class="img" src="./assets/alan_kay.jpg">
</div>

**CSS**
.white-square{
    height:200px;
    width: 250px;
    background-color:white;
    position: absolute;
}

**JS**
function clearTopHalf(){
    const whiteSquare = document.createElement("div");
    imgContainer.appendChild(whiteSquare);
    whiteSquare.setAttribute("class", "white-square");
}
clearTopHalf();
