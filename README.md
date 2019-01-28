# HTML5
https://www.jqueryscript.net/other/HTML5-Audio-Player-maudio.html
background: url(images/sun2.png) no-repeat;
    -moz-background-size: 100%; /* Firefox 3.6+ */
    -webkit-background-size: 100%; /* Safari 3.1+ и Chrome 4.0+ */
    -o-background-size: 100%; /* Opera 9.6+ */
    background-size: 100%; /* Современные браузеры */
    
    p { text-transform: lowercase; }

p:first-letter {
  text-transform: uppercase;
}
    
    @font-face {
    font-family: 'MyriadProBoldCondensed';
    src: url('/fonts/myriadpro-boldcond-webfont.eot#') format('eot'),
         url('/fonts/myriadpro-boldcond-webfont.woff') format('woff'),
         url('/fonts/myriadpro-boldcond-webfont.ttf') format('truetype'),
         url('/fonts/myriadpro-boldcond-webfont.svg#MyriadProBoldCondensed') format('svg');
    font-weight: normal;
    font-style: normal;
}

<meta name=viewport content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=yes"/>
@media only screen and (min-device-width: 900px){
#main{
width: 1000px;
    margin: 0 auto;
}
}
@media only screen and (max-device-width: 900px){
#main{
width: 100%;
    margin: 0 auto;
}
}
@media only screen and (max-device-width: 500px){
#main{
width: 100%;
    margin: 0 auto;
}
	#sitemail {
	display: none;
	}
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

