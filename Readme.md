.card{
height: 298px;
width: 180px;
margin: 18px;
}
.cardDiv>div{
height: 400px;
background-repeat:no-repeat;
}

.mainflex{
display: flex;
flex-flow: row wrap;
}
.flexbox{
display: flex;
flex-flow: row wrap;
width: 85%;
}
.flexbox2{
display: flex;
flex-flow: row wrap;
}
.carousel-inner {
height: 340px;
}

.carousel-item img {
height: 290px;
}
.posterDiv{
width: 15%;
}
.poster{
height: 350px;
width: 100%;
}
.dropbtn {
padding: 16px;
font-size: 16px;
border: none;
}

.dropdown {
position: relative;
display: inline-block;
}

.dropdown-content {
display: none;
position: absolute;
background-color: #f1f1f1;
min-width: 160px;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
}

.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
}

.dropdown-content a:hover {background-color: #ddd;}
.dropdown:hover .dropdown-content {display: block;}
.dropdown:hover .dropbtn {color: blue;}
@media only screen and (max-width: 580px) {
.card{
width: 100%;
}
.flexbox{
flex-flow: column wrap;
width: 100%;
}
.flexbox2{
display: flex;
flex-flow: column wrap;
}
.mainflex{
display: flex;
flex-flow: column wrap;
}
.poster{
height: 300px;
width: 100%;
}
.posterDiv{
width: 100%;
}

        .flip{
            flex-wrap: wrap;
        }

}
