# tribute-page
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
body{
    font-family: 'Times New Roman', Times, serif;
    color: aliceblue;
    background-color:black;

}
.container{
    max-width: 90rem;
    margin: 2rem;
    padding: 0px 2rem;

}
.header{
    padding: 2rem;
    margin: 1rem 0px;
    text-align: center;
}
header > .title{
    margin-bottom:1rem ;
    font-size: 50px;
}
.tribute{
    display: grid;
    grid-template-columns: 2fr 1fr;
    max-width: 78rem;
    margin: 0px auto;
    background: azure;
    color: black;
    align-items: center;
    padding: 0px 0px 0px 1rem ;


}

.tribute blockquote{
    text-align: center;
    font-size: 3rem;
   
}
.tribute img{
    max-width: auto;

}
.bio > h2{
    margin-bottom: 1rem;
    font-size: 3rem;
    line-height: 1.2;
} 
.bio > p{
    font-size: 1.2rem;
    line-height: 1.4;

}
.bio > hr{
    margin-top: 2rem;
}
