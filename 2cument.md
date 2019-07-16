body{
    line-height: 2em;
}


h1{
    color: blue;
    margin:5px 10px;
    padding-bottom: 10px;
}

.box{
    color: red;
    background-color: aliceblue;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16xp;
    font-weight: normal;
    border:5px blue solid;   
    border-right: 10px yellow dotted;
    border-right-width: 10px;
    border-bottom-style:dashed;
    border-radius: 35px;
    padding: 20px
    
}

.box h1{
    font-family: 'Times New Roman', Times, serif;
    font-weight: 800;
    font-style: italic;
    text-decoration: line-through;
    text-transform: uppercase; 
    letter-spacing: 1em;
    word-spacing: 2
    
}

/* id 是独一的，不能重复 */
/* clss 可以是多种的 */
.first {
    font-weight: bold;
  }
.container{
    width: 80%;
    margin:auto;
}


.list li{
    background-color: aqua;
    /* list-style-image: url('../img/16382.jpg') */
    list-style: square;
}
button{
    background-color: aqua;
    color: azure;
    padding: 10px,15px;
}

/* 鼠标放在按钮上面会触发的事件 */
button:hover{
    background-color:red;
}

/* 按下按钮会触发事件 */
button:active{
    background-color:yellow;
}

a {
    text-decoration: none;
    color: beige;
}
a:hover{
    color:red;
}
/* 访问过的不会显示 */
a:visited{
    color: beige;
}

.block{
    float: left;
    width: 33%;
    border: 3px blue  solid;
    box-sizing: border-box
    
}

#main-block{
    float: left;
    width: 70%;
    border: 3px blue  solid;
    box-sizing: border-box
    
}
#side-block{
    float: right;
    width: 30%;
    border: 3px blue  solid;
    box-sizing: border-box
    
}
.clearfix{
    clear: both;
}
.list2 li:nth-child(even) 
{
 background-color: aquamarine;
}
.list2 li:first-child{
 background-color:red ;
}

.potistion-box
{
    width: 500px;
    height: 500px;
    position: relative;
   border: 2px solid black;
}

.potistion-box h1{
    position: absolute;
    left: 20px;
}
#fixed{
    padding: 40px;
    position: fixed;
    right: 0;
    bottom: 20px;
}