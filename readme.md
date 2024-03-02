@media(max-width:430px){
    html{
        font-size: 100%;
    }
   body{
    height: 150vh;
    color: aliceblue;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),url(https://i.pinimg.com/originals/6b/11/cc/6b11cc2a5d568fb33a9b0614b8455315.gif);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
   }
   .container{
    max-width: 1200px;
    width: 100%;
    display: grid;
    grid-template-columns: repeat(autofit, minmaxa(200px, 1fr));
    gap: 2rem;
   }
   .card{
    width: 5vw;
    height:5vh;
    top: 10px;
    left: 20px;
    
}

.block{

    /* float: right; */
    top: 20px;
    right: 10px;
    width: 4vw;
    
}
.outside, .inside{
    height: 90vh;
    width: 10vw;
}

}