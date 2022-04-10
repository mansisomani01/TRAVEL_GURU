# TRAVEL_GURU
body{
    font-family: 'Montserrat', sans-serif;
    height: 1.7;
}

/* ########## HTML element styling  ########## */

html{
    /* font-size: 10px; */
    font-size: 62.5%;
}

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

ul li{
    list-style: none;    
}

a{
    font-size: 1.6rem;
    text-decoration: none;
}

p,li{
    font-size: 1.6rem;
    margin-bottom: 0.5em;
    letter-spacing: 0.15em;
}

h1,h2,h3{
    margin-bottom: 0.5em;
    font-weight: 500;
    letter-spacing: 0.15em;
}

/* #####################   utility classes   ################### */

.container{
    max-width: 1200px;
    width: 90%;
    margin: 0 auto;
}

.lg-heading{
    font-size: 3.0rem;
}

.md-heading{
    font-size: 2.2rem;
}

.text-red{
    color: #e63946;
}

.text-light{
    color: #f4f4f4;
}

.text-black{
    color: #333333;
}

.text-gray{
    color: #555555;
}

.bg-dark{
    background-color: #263238;
    color: #f4f4f4;
}

.button{
    display: inline-block;
    padding: 0.5em 1.5em;
    font-weight: 500;
    text-transform: uppercase;
    margin: 0.5em 0;
}

.button-primary{
    background-color: #fff;
    border-radius: 10em;
}

.button-secondary{
    background-color: #fff;
    border-radius: 1.5em;
    border: 2px solid #e63946;
    color: #e63946;
}

.button-primary:hover{
    background-color: mistyrose;
}

.button-secondary:hover{
    background-color: mistyrose;
}




/* #####################  header styling  ################### */

.header{
    position: relative;
    height: 95vh;
    background-position: center;
    background: linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)), url(../img/pexels-pixabay-417054.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}

.header .logo{
    color: #f4f4f4 ;
}
.header .navbar a{
    color: #f4f4f4;
}

.navbar{
    /* border: 2px solid magenta; */
    padding: 1rem;
}

.navbar .logo{
    float: left;
}

.navbar .nav-items{
    float: right;
    margin-top: 1rem;
    }

.navbar a{
    padding-bottom: 0.3rem;
    color: #f4f4f4;
}

.navbar a:hover{
    border-bottom: 1px solid white;
}

/* .header-content a:hover{
    background-color: mistyrose;
} */


.navbar .nav-item{
    display:inline-block;
    /* border-bottom: 2px solid white; */
    padding: 1rem;
}

.navbar::after{
    content: '';
    display: block;
    clear: both;
}

/* ##################  header content styling  ################## */

.header-content{
    position: absolute;
    text-align: center;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}

.header-content h1{
    font-size: 700;
}

.header-content p{
    text-transform: uppercase;
}

/* ###########################  SHOWCASE SECTION STYLING  ####################### */

.showcase{
    background-color: #ddd;
    padding: 10rem 0;
}

.row{
    height: 300px;
    background-color: white;
    box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.308);
}

.row1{
    margin-bottom: 10rem;
}

.row1 .img-box, .row2 .text-box{
    float: left;
    width: 50%;
}

.row2 .img-box, .row1 .text-box{
    float: right;
    width: 50%;
}

.row .img-box{
    height: 100%;
}

.row .text-box{
    height: 100%;
    padding: 3rem;
}

.row .img-box img{
    display: inline-block;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.row::after{
    content: '';
    display: block;
    clear: both;
}

h2.lg-heading{
    text-transform: uppercase;
}

/* .showcase .container a:hover{
    background-color: mistyrose;
} */

/* .showcase .container a{
    padding-bottom: 0.3rem;
} */

/* #########################  FEATURES SECTION STYLING  #####################  */

.features{
    padding: 10rem 0;
}

.box-wrapper{
    box-shadow : 5px 5px 20px 0px rgba(0, 0, 0, 0.308);
}

.box{
    width: 33.333333%;
    float: left;
    padding: 2rem;
    text-align: center;
}

.box-wrapper::after{
    content: "";
    display: block;
    clear: both;
}

.box-1,.box-3{
    background-color: #263238;
    color: white;
}

.box-2{
    background-color: rgb(250, 77, 120);
    color: white;
}


/* #####################  footer styling  ################### */


.footer{
    background-color: #263238;
    padding: 2rem;
    text-align: center;
}

.footer p{
    color: white;
}

.social-media-links img{
    margin: 2rem;
}


/* #######################  about page styling   ##################  */

.about{
    padding: 5rem 0;
}

/* .about-heading{
    border-bottom: 5px solid rgb(245, 35, 70);
} */

.about-heading::after{
    content: "";
    display: block;
    border-bottom: 5px solid rgb(245, 35, 70) ;
    width: 100%;
}

/* ############################  ABOUT WRAPPER STYLING  ################## */

.about-wrapper{
    text-align: center;
    margin-top: 3rem;
    color: #555555;
}

.about-wrapper .left{
    float: left;
    width: 50%;
}

.about-wrapper .right{
    float: right;
    width: 50%;
}

.about-heading::after{
    content: "";
    display: block;
    clear: both;

}

.about-wrapper li::before{
    content: "\2713";
    color: #e63946 ;
    font-weight: bold;
    padding-right: 1rem;
}

/* #########################  ABOUT COUNT STYLING ######################### */

.counts{
    margin-top: 4rem;
}

.count-item{
    /* display: inline-block; */
    text-align: center;
    float: left;
    width: 25%;
}

.count-item span{
    font-size: 3rem;
    color: #e63946;
    font-weight: 700;
}

.counts::after{
    content: "";
    display: block;
    clear: both;

}

.count-item p{
    font-size: 700;
    color: #555555;
    font-size: 1.8rem;
}

/* ##############################  BANNER STYLING  ########################## */

.banner{
    background-color: #e63946 ;
    border-radius: 0.2rem;
    padding: 1rem;
    margin-top: 3rem;
    color: #f4f4f4;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.568);
}

.banner::after{
    content: "";
    display: block;
    clear: both;
}

.banner-line{
    font-size: 2rem;
    font-weight: 700;
    margin-top: 1.6rem;
}

.banner-contact{
    display: inline-block;
    font-size: 3rem;
    font-weight: 700;
    text-align: center;
    text-transform: uppercase;
    border: 4px solid #f4f4f4;
    padding: 0.3em 2.5em;
    color: #f4f4f4;
    letter-spacing: 0.5rem;
}

.banner-left{
    padding-left: 2rem;
    float: left;
    width: 60%;
}

.banner-right{
    float: right;
    width: 40%;
    text-align: right;
}


/* ############################  CONTACT PAGE STYLING  ######################### */

.contact-page{
    padding: 5rem 0;
    background-color: #f7f7f7;
}

.form-wrapper::after{
    content: "";
    display: block;
    clear: both;
}

.form-wrapper .company-address{
    float: left;
    width: 49%;
    height: 680px;
    background-color: white;
    padding: 1rem;
}

.form-wrapper .address-group{
    margin-bottom: 3rem;
}

.form-wrapper .company-address img{
   width: 90%;
   height: 300px;
   object-fit: cover;
   object-position: left;
    /* size: 0.5px; */
}

.form-wrapper .company-address svg{
    display: inline-block;
    margin-right: 1rem;
    padding-left: 1rem;
    padding-top: 1rem;
}

.form-wrapper .company-address h2{
    display: inline-block;
    margin-right: 1rem;
    text-transform: uppercase;
}

.form-wrapper .company-address p{
    margin-left: 1rem;
}




/* ###########################  FORM STYLING  ############################   */

/* .company-address img{
    width: 95%;
} */

.form-wrapper .form{
    font-size: 1.6rem;
    float: right;
    width: 49%;
    height: 680px;
    background-color: white;
    padding: 1rem;
}

.form h1{
    border-bottom:5px solid #e63946;
}

.form-wrapper .form label{
    display: block;
}

.form-wrapper .form input{
    padding: 0.5rem;
    width: 100%;
}

.form-wrapper .form .form-group{
    margin-bottom: 1.2rem;
}

.form-wrapper .form label::after{
    content: "*";
    color: #e63946;
}

.form-wrapper .form textarea{
    width: 100%;
    height: 250px;
    padding: 1rem;
}

.form-button{
    display: block;
    margin: 0 auto;
    padding: 0.5em 3em;
    text-transform: uppercase;
    background-color: #e63946;
    color: #fff;
    outline: none;
    border: none;
    cursor: pointer;
}


/* ################################  MEDIA QUERIES  ##################################  */

@media (max-width: 500px){
    html{
        /* font-size: 8px; */
        font-size: 50%;
    }

    .navbar .nav-items, .navbar .logo{
        float: none;
        display: block;
        width: 100%;
        text-align: center;
    }

    .row{
        height: auto;
        width: 100%;
    }

    .row .img-box,
    .row .text-box{
        width: 100%;
        float: none;
        text-align: center;
    }

    .features .box{
        box-shadow : 5px 5px 20px 0px rgba(0, 0, 0, 0.308);
        width: 100%;
        float: none;
        text-align: center;
    }

    .features .box-1,
    .features .box-2{
        margin-bottom: 7rem;
    }

    .box-wrapper{
        box-shadow :none;
    }

     .banner-left,
    .banner-right{
        float: none;
        width: 100%;
        text-align: center;
    }

    .form-wrapper .company-address{
        float: none;
        width: 100%;
        height: auto;
        margin-bottom: 5rem;
    }

    .form-wrapper .form{
        float: none;
        width: 100%;
        height: auto;
    }
}

@media (min-width: 501px) and (max-width: 768px){
    html{
        font-size: 8px;
    }

    p{
        font-size: 1.8rem;
    }

    .navbar .nav-items, .navbar .logo{
        float: none;
        display: block;
        width: 100%;
        text-align: center;
    }

    .row{
        height: auto;
        width: 100%;
    }

    .row .img-box,
    .row .text-box{
        width: 100%;
        float: none;
        text-align: center;
    }

    .features .box{
        box-shadow : 5px 5px 20px 0px rgba(0, 0, 0, 0.308);
        width: 100%;
        float: none;
        text-align: center;
    }

    .features .box-1,
    .features .box-2{
        margin-bottom: 7rem;
    }

    .box-wrapper{
        box-shadow :none;
    }

     .banner-left,
    .banner-right{
        float: none;
        width: 100%;
        text-align: center;
    }

    .form-wrapper .company-address{
        float: none;
        width: 100%;
        height: auto;
        margin-bottom: 5rem;
    }

    .form-wrapper .form{
        float: none;
        width: 100%;
        height: auto;
    }
}

@media (min-width: 769) and (max-width: 1200){
    html{
        font-size: 9px;
    }

    /* ############ it is additional according to the need  ############## */
    .row .text-box h2{
        font-size: 2.2rem;
        font-weight: 500;
    }
    /* #################################################################### */

    .navbar .nav-items, .navbar .logo{
        float: none;
        display: block;
        width: 100%;
        text-align: center;
    }

    .row{
        height: auto;
        width: 100%;
    }

    .row .img-box,
    .row .text-box{
        width: 100%;
        float: none;
        text-align: center;
    }

    .features .box{
        box-shadow : 5px 5px 20px 0px rgba(0, 0, 0, 0.308);
        width: 100%;
        float: none;
        text-align: center;
    }

    .features .box-1,
    .features .box-2{
        margin-bottom: 7rem;
    }

    .box-wrapper{
        box-shadow :none;
    }

     .banner-left,
    .banner-right{
        float: none;
        width: 100%;
        text-align: center;
    }

    .form-wrapper .company-address{
        float: none;
        width: 100%;
        height: auto;
        margin-bottom: 5rem;
    }

    .form-wrapper .form{
        float: none;
        width: 100%;
        height: auto;
    }
}

@media(orientation: landscape) and (max-height: 500px){
    .header{
        height: 90vmax;
    }
   
}
