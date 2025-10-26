
仕様や比較表、諸元表など用意するのが手間なので解説は後回しです。それと制作しても日本国内では電波法の兼ね合いから使用できませんので参考資料です。今の段階でできることは、できるだけ多くのプロジェクトを発掘してソフトウェアや回路図などを参考にする程度です。あしからず。

## 携帯電話・スマートフォン(オープンソース製品)
* [evanman83/OURS-project: Step-by-step instructions to build a smartphone that is open-source, upgradeable, repairable, and Big Tech free.](https://github.com/evanman83/OURS-project)
* [libresmartphone/libresmartphone: This page contains the software used in the open hardware smartphone (libresmartphone)](https://github.com/libresmartphone/libresmartphone)
* [mudita/MuditaOS: Mobile operating system based on FreeRTOS™ optimized for E Ink displays - developed for Mudita Pure minimalist phone](https://github.com/mudita/MuditaOS)
* [Volla](https://github.com/hellovolla)
* [mikroPhone](https://mikrophone.net/)
* [Rotary Un-Smartphone](https://skysedge.com/telecom/RUSP/index.html)
* [Librem5](https://puri.sm/products/librem-5/)
* [Rephone](https://wiki.seeedstudio.com/ja/RePhone/)
* [Precursor](https://www.crowdsupply.com/sutajio-kosagi/precursor)
* [PinePhone](https://pine64.org/devices/pinephone/)
* [Openmoko](https://www.openmoko.org/wiki/Main_Page)
* [WiPhone](https://www.wiphone.io/)
* [SIP Phone based on Olimex ESP32-ADF, MOD-LCD2.8RTP boards.](https://github.com/OLIMEX/sip_phone_example)
* [OSM‑Phone](https://github.com/DansDesigns/OSM-Phone)
* [Spirit - Smartphone based on the Raspberry Pi CM 5.](https://github.com/V3lectronics/SPIRIT)

* 今のところ詳細不明のため Brax Technologies Brax3 は除外しておきます。気になる方は Youtube の Rob Braxman Tech のチャンネルを視聴のこと。


## 通信モジュール
* [LTE通信モジュール　MM-M61D | セイコーソリューションズ](https://www.seiko-sol.co.jp/products/mm-m61d/)
* [Quectel | End-to-end IoT solutions provider](https://www.quectel.com/) LTE EG25-G など。BG96 LTE は2025/10時点で[秋月電子](https://akizukidenshi.com/catalog/g/g118232/)でも購入可能
* [SIMCom Wireless Solutions - Wireless Modules and Solutions Supplier](https://www.simcom.com/)
* [4GPi](https://github.com/mechatrax/4gpi)
* [Pitalk 4G HAT](https://github.com/sbcshop/Pitalk_4G_HAT_Hardware) - オープンソースの Raspberry Pi 用の HAT モジュール (Quectel EG25-G 搭載) で音声通話対応。

基本的に国内仕様のもので個人が手にいれられるものはデータ通信専用でほとんどが中国メーカー製です(しかも正規代理店経由以外で買うと技適認証まわりが偽造されているなど怪しいものがある恐れ)。試作用にSoftbank Simplyなど安価なガラホから剥がそうにしても通信モジュール単体ではなく恐らくSoCなので目的が違うでしょう。まあ、音声通話に関しては特許がらみなどで少し厄介なようです。Librem 5やOpenmokoの回路図を調べるとわかる通り音声通話に対応しているかどうかはチップの仕様(データ側が4Gでも音声側が3Gしか対応していないものは使えません)に加えてアナログ音声出入力用の端子があり音声回路(例えばアンプ回路、オーディオチップなどのDSP IC、スピーカーやマイク)とMPU(通信モジュールの制御用)に接続されているか否かですが。無ければクラウドPBXなど必要になるでしょう。

## 分解・修理
* [Pure disassembly pictures - Other - Mudita Forum](https://forum.mudita.com/t/pure-disassembly-pictures/4814)
* [Punkt MP02 Teardown - iFixit](https://www.ifixit.com/Teardown/Punkt+MP02+Teardown/164257)

## 周辺機器
### 固定電話風ヘッドセット

* [タカラ、携帯電話用の黒電話型パロディ受話器](https://k-tai.watch.impress.co.jp/cda/article/news_toppage/193.html)
* [なじむ、受話器が手になじむぞ――「アルミ製スタンド付き受話器型ヘッドセット」：“固定電話”感覚で通話できる - ITmedia PC USER](https://www.google.com/amp/s/www.itmedia.co.jp/pcuser/amp/1304/25/news155.html)
* [[News] スマートフォンが固定電話のように使える！通話しながら、Webの閲覧やアプリの操作ができる受話器付きスタンド 2製品を発売](https://www.elecom.co.jp/news/201107/mpa-ps001/index.html)
* iClooly PhoneStand Plus

一部を除き、あまり需要はないようですが、受話器型ハンドセットは受話器部分のものは手に入りますが、受話器台付きのものは中古でも入手困難です。もっとも、古すぎて今のスマートフォンでは動かすのは変換アダプタ(CTIA/OMTP→Bluetooth/USB)などを介するので少し手間ですが。

