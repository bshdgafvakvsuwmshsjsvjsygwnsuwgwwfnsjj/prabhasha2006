<svg fill="none" viewBox="0 0 600 600" width="600" height="600" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">

<div xmlns="http://www.w3.org/1999/xhtml">
    <style>
      .container {
        display: flex;
        width: 100%;
        height: 500px;
        background-color: #0d1117;
        color: white;
        padding: 20px;
        align-items: center;
        justify-content: center;
        flex-direction: column;
      }
      .header {
        width: 100%;
        height: 40px;
	    background-image: linear-gradient(to right, #BE00FF,#27e8b1e8);
        display: flex;
        align-items: center;
        justify-content: left;
        padding: 20px;
      }
      .header-txt {
        font-family: Arial, Helvetica, sans-serif;
        color: white;
        animation: headerTxt 2s infinite linear;
      }
      @keyframes headerTxt {
        0% {
            margin-left: 0px;
        }
        50% {
            margin-left: 20px;
            letter-spacing: 2px;
        }
        100% {
            margin-left: 0px;
        }
      }
      .text1 {
        padding: 20px;
        border-radius: 10px;
        font-family: Arial, Helvetica, sans-serif;
        font-size: 20px;
        animation: borders 3s infinite linear;
        transition: .3s;
      }
        @keyframes borders {
            0% {
                border-top: 1px solid #0099ff;
                border-right: 1px solid #aaa;
                border-bottom: 1px solid #aaa;
                border-left: 1px solid #aaa;
                box-shadow: 00 -5px 10px #0099ff;
            }
            40% {
                border-top: 1px solid #aaa;
                border-right: 1px solid #0099ff;
                border-bottom: 1px solid #aaa;
                border-left: 1px solid #aaa;
                box-shadow: 7px 2px 10px #BE00FF;
            }
            70% {
                border-top: 1px solid #aaa;
                border-right: 1px solid #aaa;
                border-bottom: 1px solid #0099ff;
                border-left: 1px solid #aaa;
                box-shadow: 00 5px 10px #0099ff;
            }
            90% {
                border-top: 1px solid #aaa;
                border-right: 1px solid #aaa;
                border-bottom: 1px solid #aaa;
                border-left: 1px solid #0099ff;
                box-shadow: -7px -5px 10px #BE00FF;
            }
            100% {
                border-top: 1px solid #aaa;
                border-right: 1px solid #aaa;
                border-bottom: 1px solid #aaa;
                border-left: 1px solid #0099ff;
                box-shadow: 00 -5px 10px #0099ff;
            }
        }
      /*bg*/
      .background {
            height: 6000px;
            width: 100%;
            position: fixed;
            z-index: 1;
        }
        .background-field {
            height: 100%;
            width: 100%;
            position: relative;
        }
        .background .bg0 {
            height: 100%;
            width: 100%;
            position: absolute;
        }
        .background .bg4 {
            display: flex;
            flex-direction: column;
            opacity: .5;
        }
        .background .bg4 .bg4-i1 {
            height: 23vh;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .background .bg4 .bg4-i1 .bg4-i1-o {
            height: 6px;
            width: 150px;
            background-image: linear-gradient(to right, rgba(0, 0, 0, 0),#00ff95e0,#24ffa4e0);
            border-right: 2px solid white;
            border-radius: 5px;
        }
        .background .bg4 .bg4-i1 .bg4-i1-1 {
            height: 6px;
            width: 150px;
            background-image: linear-gradient(to right, rgba(0, 0, 0, 0),#BE00FF,#BE00FF,#f6ebfa);
            border-radius: 5px;
        }
        .background .bg4 .bg4-i1 .bg4-i1-2 {
            height: 6px;
            width: 150px;
            background-image: linear-gradient(to left, rgba(0, 0, 0, 0),#27abe8);
            border-radius: 5px;
        }
    </style>
    <div class="header">
        <h2 class="header-txt">EveloCore</h2>
    </div>
    <div class="background">
        <div class="backgroupnd-field">
            <!-- <div class="bg0 bg1">
                <div id="bgBalls_1">
                    <img src="./media/Right radial effect.svg" id="bgBall_2">
                </div>
            </div>
            <div class="bg0 bg2">
                <div id="bgBalls_2">
                    <img src="./media/Left radial effect.svg" id="bgBall_1">
                </div>
            </div>
            <div class="bg0 bg3">
                <div class="bg3-i1" id="bgBall_4">
                    <img src="./media/solid vector.svg" id="vector_1">
                    <img src="./media/Outlined vector.svg" alt="">
                </div>
                <div class="bg3-i2">
                    <img src="./media/solid vector.svg" alt="">
                    <img src="./media/Outlined vector.svg" alt="">
                </div>
            </div> -->
            <div class="bg0 bg4">
                <div class="bg4-i1">
                    <marquee behavior="" direction="right">
                        <div class="bg4-i1-o"></div>
                    </marquee>
                </div>
                <div class="bg4-i1">
                    <marquee behavior="" scrollamount="10" direction="right">
                        <div class="bg4-i1-1"></div>
                    </marquee>
                </div>
                <div class="bg4-i1">
                    <marquee behavior="" scrollamount="5" direction="left">
                        <div class="bg4-i1-2"></div>
                    </marquee>
                </div>
            </div>
        </div>
    </div>
    <div class="container">
        <h1 class="text1">Hi there, my name is Kumuthu Prabhasha 👋</h1>
        <h1 class="text1">I am a software developer 💡</h1>
        <h1 class="text1">This is my official github account.</h1>
        <h1 class="text1">Thanks for viewing 🚀</h1>
    </div>
  </div>
    </foreignObject>
  </svg>
