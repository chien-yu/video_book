# Initial page

## How do I learn video

現在大家想到video，可能會先聯想到Netflix或是Youtube，我想討論的就是在這些平台背後的技術，從後台如何準備影片資源，到這些資源如何在網路上傳送和被接收。

### 準備資源

這個部分其實很多重點在壓縮技術的codec，這裡有很棒的介紹[https://github.com/leandromoreira/digital\_video\_introduction](https://github.com/leandromoreira/digital_video_introduction)

重點就是在如何把巨大的video資料用比較小的空間存起來，但是又不會失去太重要的訊息，所以可以讓我們在播放時一樣看到高畫質。

以上這個只稱作raw stream，要能在網路上流通，我們還需要把它放進container之中，其實最重要的目的是增加額外的metadata讓我們使用者可以更輕鬆和更彈性的播放影片。為什麼需要container，我們需要怎樣的container，哪些container format比較熱門，這些都可以是不錯的主題。

在streaming上，如何讓網際網路更順暢地流通這些檔案也是一門藝術，一切就是從切割檔案開始，這裡也衍伸出不同的方式，有的適合live直播，其他的能幹嘛？可能要整理一下Quora的資料了。

最近也看到一篇關於web player的文章：[https://medium.com/canal-tech/how-video-streaming-works-on-the-web-an-introduction-7919739f7e1](https://medium.com/canal-tech/how-video-streaming-works-on-the-web-an-introduction-7919739f7e1)

這是我一開始看的一篇設定文，[https://medium.com/@ponychen/%E5%9C%A8-osx-%E4%B8%8A%E9%80%8F%E9%81%8E-homebrew-%E5%AE%89%E8%A3%9D-nginx-%E8%88%87%E5%95%9F%E7%94%A8-hls-%E5%8A%9F%E8%83%BD-9b5f02130f2](https://medium.com/@ponychen/%E5%9C%A8-osx-%E4%B8%8A%E9%80%8F%E9%81%8E-homebrew-%E5%AE%89%E8%A3%9D-nginx-%E8%88%87%E5%95%9F%E7%94%A8-hls-%E5%8A%9F%E8%83%BD-9b5f02130f2)

這次來介紹一個project，可以從如何下載常用網站的影音開始。

{% embed url="http://ytdl-org.github.io/youtube-dl/" %}

裡面支援的網站還有華視新聞，不過現在好像不能對華視的youtube影片下載了有個bug。

