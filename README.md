# photos*{
    margin:0px;
    padding: 0px;
    
}
.header{
    width: 100%;  
}
.wrapper{
    width: 970px;
    margin: 30px auto 40px;
}
.main {
    display: block;
    float: left;
    width: 670px;
}

.sidemenu {
    float: right;
    width: 275px;
}

.footer {
    width: 100%;
}
.clearfix::after{
    content:'';
    display: block;
    clear: both;
}

.header,.main,.sidemenu,.footer{
    border: 2px solid #aaa;
    background-color: #ccc;
}
.header,.footer{
    height: 100px;
}
.main,.sidemenu{
    height: 500px;
}
html{
    font-size: 62.5%;
}
body{
    color: #80c5cb;
    font-size: 1.2rem;
    font-family: '微軟正黑體';
}
*,*::before,*::after{
    box-sizing: border-box;
}
