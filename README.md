@import url("https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:ital@1&display=swap');

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

body.dark {
	background-image: url('https://i.ibb.co/DQMx1KZ/images.jpg');
}

body.light {
	background-image: url('https://raw.githubusercontent.com/mjvbz/mjvbz.github.io/master/public/images/bg.jpg');
}
	
#check {
    display: none;
}

.dark .container{
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.dark .card{
    position: relative;
    width: 400px;
    background-color: #000;
    border-radius: 5px;
    box-shadow: 0 5px 15px 1px rgba(0, 0, 0, 0.1);
    overflow: hidden;
}

.dark .card:before{
    content: '';
    position: absolute;
    width: 100%;
    height: 270px;
    top: 0;
    left: 0;
    background-color:#1F2833;
    clip-path: circle(400px at 50% -48.5%);
}

.dark .header{
    position: relative;
    height: 265px;
}

.dark .mail{
    position: absolute;
    top: 1rem;
    right: 2rem;
    font-size: 1.5rem;
    color: #7F00FF;
    opacity: .8;
    transition: .3s;
    z-index: 3;
    text-decoration: none;
}

.dark .mail:hover{
    opacity: 1;
}

.dark .hamburger-menu{
    position: absolute;
    width: 21px;
    height: 16px;
    top: 1.4rem;
    left: 1.9rem;
    z-index: 3;
    cursor: pointer;
    transition: .3s;
    opacity: .8;
}

.dark .hamburger-menu:hover{
    opacity: 1;
}

.dark .hamburger-menu .center{
    position: absolute;
    height: 2px;
    width: 70%;
    top: 50%;
    transform: translateY(-50%);
    background-color: #001626;
    border-radius: 1px;
}

.dark .hamburger-menu:before, .dark .hamburger-menu:after{
    content: '';
    position: absolute;
    width: 100%;
    height: 2px;
    border-radius: 1px;
    background-color: #000;
}

.dark .hamburger-menu:before{
    top: 0;
}

.dark .hamburger-menu:after{
    bottom: 0;
}

.dark .main{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.dark .main .image{
    position: relative;
    width: 110px;
    height: 110px;
    border-radius: 50%;
    background: url('https://avatars.githubusercontent.com/u/85196372?s=400&u=8740585aca0a7d17e89d638bdff27060458abe38&v=4') no-repeat center / cover;
    border: 4px solid #000;
    margin-bottom: 2px;
    overflow: hidden;
    cursor: pointer;
}

.dark .image .hover{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: #1F2833;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    transition: .5s;
    opacity: 0;
}

.dark .image:hover .hover{
    opacity: 1;
}

.dark .hover.active{
    opacity: 1;
}

.dark .name{
    font-family: 'Dancing Script', cursive;
    font-size: 1.6rem;
    color: #fff;
    font-weight: 500;
    line-height: 1;
    margin: 5px 0;
}

.dark .sub-name{
     font-family: 'poppins', sans-serif;
    font-size: 1.2rem;
    opacity: .8;
    color: #fff;
}

.dark .content{
    display: flex;
    padding: 1.7rem 2.5rem 2.6rem 2.5rem;
}

.dark .right{
    padding-top: 1.5rem;
    display: flex;
    flex-direction: column;
    text-align: right;
    align-items: flex-end;
    justify-content: space-between;
    margin-left: 2.1rem;
}

.dark .number{
    font-size: 2.1rem;
    font-weight: 200;
    color: #333;
    line-height: 1.2;
}

.dark .number-title{
    font-size: .55rem;
    color: #666;
    font-weight: 400;
    line-height: 1;
    letter-spacing: 1px;
    text-transform: uppercase;
}

.dark .title{
    position: relative;
    color: #7F00FF;
    font-weight: 500;
    font-size: 1.1rem;
    padding: 0 0 3px 0;
    margin-bottom: .9rem;
    display: inline-block;
}

.dark .title:after{
    content: '';
    position: absolute;
    height: 3px;
    width: 50%;
    background-color: #fff;
    bottom: 0;
    left: 0;
}

.dark .text{
    color: #fff;
    font-weight: 300;
    line-height: 1.7;
}

.dark .icons-container{
    padding: 1rem 0;
}

.dark .icon{
    color: #fff;
    font-size: 1.3rem;
    text-decoration: none;
    margin-right: 8px;
    transition: .3s;
}

.dark .icon:hover{
    color: #7F00FF;
}

.dark .buttons-wrap{
    display: flex;
    margin-top: 5px;
}

.dark .follow-wrap, .dark .share-wrap{
    flex: 4;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: .5s;
}

.dark .follow-wrap:hover, .dark .share-wrap:hover{
    flex: 5;
}

.dark .follow{
    padding: 9.6px 0;
    width: 100%;
    background: #7F00FF;
    color: #fff;
    text-align: center;
    text-decoration: none;
    font-size: .7rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    border-radius: 18.1px;
    margin-right: 3px;
}

.dark .share{
    padding: 7.6px 0;
    width: 100%;
    border: 2px solid #7F00FF;
    color: #7F00FF;
    text-decoration: none;
    text-align: center;
    font-size: .7rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    margin-left: 3px;
    border-radius: 18.1px;
}

.dark .close{
    position: absolute;
    top: 1rem;
    right: 1rem;
    width: 30px;
    height: 30px;
    cursor: pointer;
    transition: .3s;
}

.dark .close:hover{
    opacity: .5;
}

.dark .close:before, .dark .close:after{
    content: '';
    position: absolute;
    width: 100%;
    height: 3px;
    border-radius: 1.5px;
    top: 50%;
    left: 50%;
    background-color: #fff;
}

.dark .close:before{
    transform: translate(-50%, -50%) rotate(45deg);
}

.dark .close:after{
    transform: translate(-50%, -50%) rotate(135deg);
}

.dark .sidebar {
     position: absolute;
     top: 50px;
     left: 20px;
     z-index: 1000;
     width: 50%;
     display: none;
}

.dark .sidebar ul {
     position: absolute;
     background: #000;
     display: flex;
     flex-direction: column;
     width: 100%;
     align-items: center;
     list-style-type: none;
     border-radius: 5px;
}

.dark .sidebar ul li {
     margin: 8px;
}

.dark .sidebar ul li a{
     font-size: 17px;
     color: #535A5E;
     padding: 5px 10px;
     border-radius: 4px;
     color: #fff;
     text-decoration: none;
}

.light .container{
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.light .card{
    position: relative;
    width: 400px;
    background-color:whitesmoke;
    border-radius: 5px;
    box-shadow: 0 5px 15px 1px rgba(0, 0, 0, 0.1);
    overflow: hidden;
}

.light .card:before{
    content: '';
    position: absolute;
    width: 100%;
    height: 270px;
    top: 0;
    left: 0;
    background-color:#3a5069;
    clip-path: circle(400px at 50% -48.5%);
}

.light .header{
    position: relative;
    height: 265px;
}

.light .mail{
    position: absolute;
    top: 1rem;
    right: 2rem;
    font-size: 1.5rem;
    color: #fff;
    opacity: .8;
    transition: .3s;
    z-index: 3;
    text-decoration: none;
}

.light .mail:hover{
    opacity: 1;
}

.light .hamburger-menu{
    position: absolute;
    width: 21px;
    height: 16px;
    top: 1.4rem;
    left: 1.9rem;
    z-index: 3;
    cursor: pointer;
    transition: .3s;
    opacity: .8;
}

.light .hamburger-menu:hover{
    opacity: 1;
}

.light .hamburger-menu .center{
    position: absolute;
    height: 2px;
    width: 70%;
    top: 50%;
    transform: translateY(-50%);
    background-color: #fff;
    border-radius: 1px;
}

.light .hamburger-menu:before, .light .hamburger-menu:after{
    content: '';
    position: absolute;
    width: 100%;
    height: 2px;
    border-radius: 1px;
    background-color: #fff;
}

.light .hamburger-menu:before{
    top: 0;
}

.light .hamburger-menu:after{
    bottom: 0;
}

.light .main{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.light .main .image{
    position: relative;
    width: 110px;
    height: 110px;
    border-radius: 50%;
    background: url('https://user-images.githubusercontent.com/84258378/144585764-bd6e6c09-d63e-4445-ad3f-d1fb7bafbcbf.jpeg') no-repeat center / cover;
    border: 4px solid #a1b6b1;
    margin-bottom: 2px;
    overflow: hidden;
    cursor: pointer;
}

.light .image .hover{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: rgba(79, 172, 254, .7);
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    transition: .5s;
    opacity: 0;
}

.light .image:hover .hover{
    opacity: 1;
}

.light .hover.active{
    opacity: 1;
}

.light .name{
    font-size: 1.2rem;
    color: #fff;
    font-weight: 500;
    line-height: 1;
    margin: 5px 0;
}

.light .sub-name{
    font-family: 'Titillium Web', sans-serif;
    font-size: 1.2rem;
    opacity: .8;
    color: #fff;
}

.light .content{
    display: flex;
    padding: 1.7rem 2.5rem 2.6rem 2.5rem;
}

.light .right{
    padding-top: 1.5rem;
    display: flex;
    flex-direction: column;
    text-align: right;
    align-items: flex-end;
    justify-content: space-between;
    margin-left: 2.1rem;
}

.light .number{
    font-size: 2.1rem;
    font-weight: 200;
    color: #333;
    line-height: 1.2;
}

.light .number-title{
    font-size: .55rem;
    color: #666;
    font-weight: 400;
    line-height: 1;
    letter-spacing: 1px;
    text-transform: uppercase;
}

.light .title{
    position: relative;
    color: black;
    font-weight: 500;
    font-size: 1.1rem;
    padding: 0 0 3px 0;
    margin-bottom: .9rem;
    display: inline-block;
}

.light .title:after{
    content: '';
    position: absolute;
    height: 3px;
    width: 50%;
    background-color: #555;
    bottom: 0;
    left: 0;
}

.light .text{
    color:black;
    font-weight: 300;
    line-height: 1.7;
}

.light .icons-container{
    padding: 1rem 0;
}

.light .icon{
    color: #c4c4c4;
    font-size: 1.3rem;
    text-decoration: none;
    margin-right: 8px;
    transition: .3s;
    opacity:200;
}

.light .icon:hover{
    color: #3a5069;
}

.light .buttons-wrap{
    display: flex;
    margin-top: 5px;
}

.light .follow-wrap, .light .share-wrap{
    flex: 4;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: .5s;
}

.light .follow-wrap:hover, .light .share-wrap:hover{
    flex: 5;
}

.light .follow{
    padding: 9.6px 0;
    width: 100%;
    background: linear-gradient(to right, #4facfe 0%, #00f2fe 140%);
    color: #fff;
    text-align: center;
    text-decoration: none;
    font-size: .7rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    border-radius: 18.1px;
    margin-right: 3px;
}

.light .share{
    padding: 7.6px 0;
    width: 100%;
    border: 2px solid #4facfe;
    color: #93a4a8;
    text-decoration: none;
    text-align: center;
    font-size: .7rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    margin-left: 3px;
    border-radius: 18.1px;
}

.modal{
    position: fixed;
    width: 100%;
    height: 100vh;
    background-color: rgba(0, 0, 0, 0.8);
    z-index: -1;
    opacity: 0;
    transition: .5s;
}

.modal img{
    position: absolute;
    top: 25%;
    left: 50%;
    transform: translate(-50%, -50%) scale(.3);
    max-width: 100%;
    max-height: 100%;
    transition: .5s;
}

.modal.show{
    opacity: 1;
    z-index: 99;
}

.modal.show img{
    top: 50%;
    transform: translate(-50%, -50%) scale(1);
}

.light .close{
    position: absolute;
    top: 1rem;
    right: 1rem;
    width: 30px;
    height: 30px;
    cursor: pointer;
    transition: .3s;
}

.light .close:hover{
    opacity: .5;
}

.light .close:before, .light .close:after{
    content: '';
    position: absolute;
    width: 100%;
    height: 3px;
    border-radius: 1.5px;
    top: 50%;
    left: 50%;
    background-color: #fff;
}

.light .close:before{
    transform: translate(-50%, -50%) rotate(45deg);
}

.light .close:after{
    transform: translate(-50%, -50%) rotate(135deg);
}

.light .sidebar {
     position: absolute;
     top: 50px;
     left: 20px;
     z-index: 1000;
     width: 50%;
     display: none;
}

.light .sidebar ul {
     position: absolute;
     background: #fff;
     display: flex;
     flex-direction: column;
     width: 100%;
     align-items: center;
     list-style-type: none;
     border-radius: 5px;
}

.light .sidebar ul li {
     margin: 8px;
}

.light .sidebar ul li a{
     font-size: 17px;
     padding: 5px 10px;
     border-radius: 4px;
     color: #00f2fe;
     text-decoration: none;
}

@media (max-width: 410px){
    .content{
        flex-direction: column;
    }

    .right{
        flex-direction: row;
        text-align: center;
        justify-content: space-around;
        align-items: center;
        margin: 0;
    }
}

@media (max-width: 370px){
    .header{
        height: 230px;
    }

    .card:before{
        clip-path: circle(400px at 50% -74.5%);
        height: 230px;
    }

    .hamburger-menu{
        width: 16px;
        height: 12px;
        top: 1.1rem;
        left: 1.5rem;
    }

    .mail{
        font-size: 1.1rem;
        top: .75rem;
        right: 1.5rem;
    }

    .main .image{
        width: 90px;
        height: 90px;
        border-width: 3px;
    }

    .name, .sub-name{
        font-size: 1rem;
    }

    .content{
        padding: 1.2rem 1.8rem 1.8rem 1.8rem;
    }

    .number{
        font-size: 1.8rem;
    }

    .number-title{
        font-size: .4rem;
    }

    .right{
        padding-top: 1rem;
    }

    .title{
        font-size: .9rem;
        margin-bottom: .5rem;
    }

    .text{
        font-size: .8rem;
    }

    .icons-container{
        padding: .5rem 0;
    }

    .icon{
        font-size: 1.1rem;
    }

    .follow{
        padding: 7.6px 0;
        border-radius: 14.6px;
        font-size: .6rem;
    }

    .share{
        padding: 5.6px 0;
        border-radius: 14.6px;
        font-size: .6rem;
    }
}


.wrapper {
	 position: absolute;
      left: 0;
      top: 20px;
      transform: scale(.8);
      margin-left: -75px;
}
 .toggle {
	 position: relative;
	 display: inline-block;
	 width: 100px;
	 margin-left: 100px;
	 padding: 4px;
	 border-radius: 40px;
}
 .toggle:before, .toggle:after {
	 content: '';
	 display: table;
}
 .toggle:after {
	 clear: both;
}
 .toggle-bg {
	 position: absolute;
	 top: -4px;
	 left: -4px;
	 width: 100%;
	 height: 100%;
	 background-color: #c0e6f6;
	 border-radius: 40px;
	 border: 4px solid #81c0d5;
	 transition: all 0.1s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}
 .toggle-input {
	 position: absolute;
	 top: 0;
	 left: 0;
	 width: 100%;
	 height: 100%;
	 border: 1px solid red;
	 border-radius: 40px;
	 z-index: 2;
	 opacity: 0;
}
 .toggle-switch {
	 position: relative;
	 width: 40px;
	 height: 40px;
	 margin-left: 50px;
	 background-color: #f5eb42;
	 border: 4px solid #e4c74d;
	 border-radius: 50%;
	 transition: all 0.1s cubic-bezier(0.25, 0.46, 0.45, 0.94);
      transform: translate(-4px,-4px);
}
 .toggle-switch-figure {
	 position: absolute;
	 bottom: -14px;
	 left: -50px;
	 display: block;
	 width: 80px;
	 height: 30px;
	 border: 8px solid #d4d4d2;
	 border-radius: 20px;
	 background-color: #fff;
	 transform: scale(0.4);
	 transition: all 0.12s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}
 .toggle-switch-figure:after {
	 content: '';
	 display: block;
	 position: relative;
	 top: -65px;
	 right: -42px;
	 width: 15px;
	 height: 15px;
	 border: 8px solid #d4d4d2;
	 border-radius: 100%;
	 border-right-color: transparent;
	 border-bottom-color: transparent;
	 transform: rotateZ(70deg);
	 background-color: #fff;
}
 .toggle-switch-figure:before {
	 content: '';
	 display: block;
	 position: relative;
	 top: -25px;
	 right: -10px;
	 width: 30px;
	 height: 30px;
	 border: 8px solid #d4d4d2;
	 border-radius: 100%;
	 border-right-color: transparent;
	 border-bottom-color: transparent;
	 transform: rotateZ(30deg);
	 background-color: #fff;
}
 .toggle-switch-figureAlt {
	 content: '';
	 position: absolute;
	 top: 5px;
	 left: 2px;
	 width: 2px;
	 height: 2px;
	 background-color: #efeeda;
	 border-radius: 100%;
	 border: 4px solid #dee1c5;
	 box-shadow: 42px -7px 0 -3px #fcfcfc, 75px -10px 0 -3px #fcfcfc, 54px 4px 0 -4px #fcfcfc, 83px 7px 0 -2px #fcfcfc, 63px 18px 0 -4px #fcfcfc, 44px 28px 0 -2px #fcfcfc, 78px 23px 0 -3px #fcfcfc;
	 transition: all 0.12s cubic-bezier(0.25, 0.46, 0.45, 0.94);
	 transform: scale(0);
}
 .toggle-switch-figureAlt:before {
	 content: '';
	 position: absolute;
	 top: -6px;
	 left: 18px;
	 width: 7px;
	 height: 7px;
	 background-color: #efeeda;
	 border-radius: 100%;
	 border: 4px solid #dee1c5;
}
 .toggle-switch-figureAlt:after {
	 content: '';
	 position: absolute;
	 top: 19px;
	 left: 15px;
	 width: 2px;
	 height: 2px;
	 background-color: #efeeda;
	 border-radius: 100%;
	 border: 4px solid #dee1c5;
}
 .toggle-input:checked ~ .toggle-switch {
	 margin-left: 0;
	 border-color: #dee1c5;
	 background-color: #fffdf2;
}
 .toggle-input:checked ~ .toggle-bg {
	 background-color: #484848;
	 border-color: #202020;
}
 .toggle-input:checked ~ .toggle-switch .toggle-switch-figure {
	 margin-left: 40px;
	 opacity: 0;
	 transform: scale(0.1);
}
 .toggle-input:checked ~ .toggle-switch .toggle-switch-figureAlt {
	 transform: scale(1);
}

