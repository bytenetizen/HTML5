# HTML5
background: url(images/sun2.png) no-repeat;
    -moz-background-size: 100%; /* Firefox 3.6+ */
    -webkit-background-size: 100%; /* Safari 3.1+ и Chrome 4.0+ */
    -o-background-size: 100%; /* Opera 9.6+ */
    background-size: 100%; /* Современные браузеры */
    
    
    
    @font-face {
    font-family: 'MyriadProBoldCondensed';
    src: url('/fonts/myriadpro-boldcond-webfont.eot#') format('eot'),
         url('/fonts/myriadpro-boldcond-webfont.woff') format('woff'),
         url('/fonts/myriadpro-boldcond-webfont.ttf') format('truetype'),
         url('/fonts/myriadpro-boldcond-webfont.svg#MyriadProBoldCondensed') format('svg');
    font-weight: normal;
    font-style: normal;
}


@media (pointer:coarse) {
    .which-pointer::after {
        content: "You have a coarse pointer, are you on a touchscreen device?";    
    } 
}

@media (pointer:fine) {
    .which-pointer::after {
        content: "You have a fine pointer, are you using a mouse or trackpad?";    
    } 
}

@media (min-width: 40em) and (max-width: 59em) {
    .main {display: none;}
}


@media screen and (max-width: 992px) {

}


@media screen and (min-device-width: 1600px) {
    div {width: 1500px;}
   }
   @media screen and (device-width: 1280px) {
    div {width: 1100px;}
   }
   @media screen and (device-width: 1024px) {
    div {width: 980px;}
   }

