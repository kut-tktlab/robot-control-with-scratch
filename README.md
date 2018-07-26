# robot-contorl-with-scratch
## 概要
このプロジェクトはオープンキャンパスで、「スクラッチを用いたロボット制御」の展示を行う為に必要な情報をまとめたプロジェクトです。

## 使用物品
今回のプロジェクトで使用した部品の一覧は以下の通りです。
- キーボード
- マウス
- ディスプレイ
- [リモコンロボット製作セット(クローラータイプ)](http://www.tamiya.com/japan/products/70170/index.html) 1個
- [RaspberryPi3 Model B](http://akizukidenshi.com/catalog/g/gM-10414/) 1個
- [TA7291P](http://akizukidenshi.com/catalog/g/gI-02001/) 3個
- [抵抗 10KΩ](http://akizukidenshi.com/catalog/g/gR-25103/) ３本
- [ブレッドボード](http://akizukidenshi.com/catalog/g/gP-05294/) １個
- [ジャンパーワイヤ(オス-オス)](http://akizukidenshi.com/catalog/g/gC-05371/) ２本
- [JUMP WIRE Kit - MODEL SKS-390](https://www.amazon.co.jp/%E3%82%B5%E3%83%B3%E3%83%8F%E3%83%A4%E3%83%88-SKS-390-%E3%82%B8%E3%83%A3%E3%83%B3%E3%83%97%E3%83%AF%E3%82%A4%E3%83%A4%E3%82%AD%E3%83%83%E3%83%88/dp/B00J2QOV58) 黄色のジャンパ線　9本、ミノムシクリップ付き ジャンパ線４本
- ワニ口クリップ ２本


プロジェクトで使用した「TA7291P」と「ワニ口クリップ」はstmnが持ってきた物なので、研究室にあるか確認してください。

## 配線図
実際の配線図のサンプルを下記に表示します。GPIOのピン配置やGNDの配置などは自由に変えてもらっても構いません。この後のプログラムの説明は下記の配線を元に行いますので、ピン配置を行なった場合には読み替えてください。
***
配線図(タンク本体)
![配線図(タンク本体)](https://github.com/kut-tktlab/robot-contorl-with-scratch/blob/master/images/oc_tank_body.png)

***
配線図(アーム部分)
![配線図(アーム部分)](https://github.com/kut-tktlab/robot-contorl-with-scratch/blob/master/images/oc_tank_arm.png)


## 参考サイト
今回のプロジェクトで参考にしたサイト、参考になりそうなサイトをまとめました。わからないことがあった際には調べてみてください。
<!--
コメント内に書いてあるのはいらないかも
[NOOBS 1.9.2でインストールしたRaspbian (jessie) 上のScratchで日本語入力を可能にしてみた](https://neuralassembly.blogspot.com/2016/06/noobs-192raspbian-jessie-scratch.html)
 -->  
[GPIO IN SCRATCH 1.4](https://www.raspberrypi.org/documentation/usage/gpio/scratch1/README.md)  
[Raspberry Pi上のScratchでDCモーターを制御してみた](https://neuralassembly.blogspot.com/2016/06/raspberry-piscratchdc.html)  
[dotstudio, inc. PWM制御](https://dotstud.io/docs/pulse-width-modulation/)  
[TA7291P データシート](http://akizukidenshi.com/download/ta7291p.pdf)  
[うしこlog モータドライバの使い方](http://usicolog.nomaki.jp/engineering/avr_lineTracer/motorDriver.html)
