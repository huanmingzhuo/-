# CSWY
<!DOCTYPE html>
<!-- saved from url=(0042)https://arcxingye.github.io/r18/index.html -->
<html lang="zh"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
    <title>❤️站❤️长❤️推❤️荐❤️</title>
    <style type="text/css">
        p {
            margin: 0;
        }

        *,
        *::before,
        *::after {
            box-sizing: border-box;
        }

        .overlay,
        .scare {
            position: fixed;
            top: 0;
            left: 0;
            height: 100vh;
            width: 100vw;
        }

        p.overlay-title {
            font-size: 24px;
            font-weight: 900;
            color: black;
            line-height: 1;
            margin-bottom: 16px;
        }

        .overlay-button {
            display: inline-flex;
            align-items: center;
            height: 40px;
            padding-right: 24px;
            padding-left: 24px;
            font-size: 16px;
            font-weight: 500;
            line-height: 1;
            border-radius: 4px;
            margin: 4px;
            cursor: pointer;
        }

        .overlay-buttons-wrapper {
            margin: 24px -8px -8px;
        }

        #accept-button {
            background-color: rgb(255, 0, 0);
            color: white;
        }

        #decline-button {
            color: rgb(0, 0, 0);
            border: 2px solid rgb(0, 0, 0);
        }

        p.overlay-description {
            font-size: 16px;
            font-weight: 400;
            color: rgba(0, 0, 0, 0.5);
            line-height: 1.25;
            margin-bottom: 16px;
        }

        a.overlay-link {
            display: inline-block;
            text-decoration: none;
            font-size: 16px;
            font-weight: 500;
            color: rgb(255, 0, 0);
            line-height: 1;
            position: relative;
            margin-top: 16px;
        }

        a.overlay-link::before {
            position: absolute;
            content: "";
            height: calc(50% + 4px);
            width: calc(100% + 8px);
            bottom: -4px;
            left: -4px;
            background-color: rgba(132, 94, 194, 0.1);
        }

        .overlay-body {
            max-width: 512px;
            text-align: center;
            font-family: "Inter", sans-serif;
        }

        .overlay[hidden] {
            display: none;
        }

        .overlay {
            z-index: 2;
            display: flex;
            align-items: center;
            justify-content: center;
            background-image: url(https://iw233.cn/api/Random.php);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center 0;
        }

        .text-bg {
            background-color: rgba(255, 255, 255, 0.6);
            padding: 24px;
        }

        .scare {
            z-index: 1;
        }

        video#video {
            height: 100%;
            width: 100%;
            object-fit: cover;
        }

        video#video::-webkit-media-controls-enclosure {
            display: none !important;
        }
    </style>
<style type="text/css">
      @font-face {
          font-family: "element-icons";
          src: url('chrome-extension://moombeodfomdpjnpocobemoiaemednkg/fonts/element-icons.woff') format('woff'),
          url('chrome-extension://moombeodfomdpjnpocobemoiaemednkg/fonts/element-icons.ttf ') format('truetype'); /* chrome, firefox, opera, Safari, Android, iOS 4.2+*/
      }
  </style></head>

<body>
    <div id="overlay" class="overlay">
        <div class="text-bg">
            <div class="overlay-body">
                <p class="overlay-title">您是否已满180岁</p>
                <p class="overlay-description">以下内容可能不适合<b>未满180岁</b>的人群观看，我们需要确认您的年龄。</p>
                <p class="overlay-description">The following may not be suitable for people <b>under the age of
                        18</b> and we need to confirm your age.</p>
                        <p class="overlay-description">Следующее может не подойти <b>моложе 180 лет</b> массовый просмотр, нам нужно подтвердить ваш возраст.</p>
                <div class="overlay-buttons-wrapper">
                    <div id="accept-button" class="overlay-button">已满180岁</div>
                    <div id="decline-button" class="overlay-button">未满180岁</div>
                </div>
            </div>
        </div>
    </div>
    <div class="scare">
        <video id="video" class="video" src="https://cn-zjjh4-dx-v-05.bilivideo.com/upgcxcode/25/28/516332825/516332825-1-208.mp4?e=ig8euxZM2rNcNbhjnwdVhwdlhzT3hwdVhoNvNC8BqJIzNbfq9rVEuxTEnE8L5F6VnEsSTx0vkX8fqJeYTj_lta53NCM=&uipk=5&nbs=1&deadline=1646249820&gen=playurlv2&os=bcache&oi=3662573633&trid=00001cb43145a8cc43cf93af1276452a4c4bT&platform=html5&upsig=54e20ac56b6d58797b1d57512b8931d9&uparams=e,uipk,nbs,deadline,gen,os,oi,trid,platform&cdnid=6590&mid=0&bvc=vod&nettype=0&bw=368893&orderid=0,1&logo=80000000" loop="loop"></video>
        
    </div>
    <script type="text/javascript">
        const video = document.getElementById("video");
        const overlay = document.getElementById("overlay");
        const declineButton = document.getElementById("decline-button");
        const acceptButton = document.getElementById("accept-button");
        let hasClicked;
        window.onbeforeunload = function () {
            if (hasClicked) return true;
        };
        function buttonClick1(event) {
            event.preventDefault();
            if (!hasClicked) hasClicked = true;
            overlay.hidden = true;
            video.play();
            videoClick();
        }
        function buttonClick2(event) {
            window.location.href = 'https://space.bilibili.com/440830005?spm_id_from=333.1007.0.0'
        }
        function videoClick(event) {
            if (event) event.preventDefault();
            // if not fullscreen
            const { documentElement } = document;
            if (documentElement.requestFullscreen) documentElement.requestFullscreen();
            else if (documentElement.mozRequestFullScreen) documentElement.mozRequestFullScreen();
            else if (documentElement.webkitRequestFullscreen) documentElement.webkitRequestFullscreen();
            else if (documentElement.msRequestFullscreen) documentElement.msRequestFullscreen();
        }
        acceptButton.addEventListener("click", buttonClick1);
        declineButton.addEventListener("click", buttonClick2);
        video.addEventListener("click", videoClick);
    </script>
</body></html>
