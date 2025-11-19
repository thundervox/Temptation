## ∀wesome DIY/Homebrew Cellular Phone

仕様や比較表、諸元表など用意するのが手間なので解説は後回しです。それと制作しても日本国内では電波法の兼ね合いから使用できませんので参考資料です。今の段階でできることは、できるだけ多くのプロジェクトを発掘してソフトウェアや回路図などを参考にする程度です。あしからず。

ある程度の規模になりましたら分割予定です。

## 携帯電話・スマートフォン(オープンソース製品)
1. (準備中)
2.  (準備中)
3.   [Raspberry Piで自作の携帯電話を作る - element14 presents](https://youtu.be/jjX7nS3kIao?si=ZytBZaNiKcO9VbMd)
4.   (準備中)
6.    [mikroPhone](https://mikrophone.net/)
7.    (準備中)
8. (準備中)
9.    [Rephone](https://wiki.seeedstudio.com/ja/RePhone/)
10. (準備中)
11.    [Precursor](https://www.crowdsupply.com/sutajio-kosagi/precursor)
12. (準備中)
13.  [Openmoko](https://www.openmoko.org/wiki/Main_Page)
14.   [WiPhone](https://www.wiphone.io/)
15.    [SIP Phone based on Olimex ESP32-ADF, MOD-LCD2.8RTP boards.](https://github.com/OLIMEX/sip_phone_example)
16.[Project paxo](https://github.com/paxo-phone/)
17.  [ZeroPhone](https://github.com/ZeroPhone)

### Android/Linux ベースのシステム
* FairPhone
* [Librem5](https://puri.sm/products/librem-5/)
* [PinePhone](https://pine64.org/devices/pinephone/)
* [Volla](https://github.com/hellovolla)

### Arduino ベースのシステム
* [Seeed-Studio/ArduinoPhone: ArduinoPhone, a phone with Seeeduino, and GPRS Shield , and TFT Touch Shield!!!](https://github.com/Seeed-Studio/ArduinoPhone)
* [CircuitMess Ringo - an educational DIY mobile phone](https://github.com/CircuitMess/CircuitMess-Ringo)
* [Rotary Un-Smartphone](https://skysedge.com/telecom/RUSP/index.html)

### Python ベースのシステム
* [evanman83/OURS-project: Step-by-step instructions to build a smartphone that is open-source, upgradeable, repairable, and Big Tech free.](https://github.com/evanman83/OURS-project)
* [libresmartphone/libresmartphone: This page contains the software used in the open hardware smartphone (libresmartphone)](https://github.com/libresmartphone/libresmartphone) †

### Raspberry Pi ベースのシステム
* [OSM‑Phone](https://github.com/DansDesigns/OSM-Phone)
* [Spirit - Smartphone based on the Raspberry Pi CM 5.](https://github.com/V3lectronics/SPIRIT)

## 独自OS/ベアメタルのシステム
* [mudita/MuditaOS: Mobile operating system based on FreeRTOS™ optimized for E Ink displays - developed for Mudita Pure minimalist phone](https://github.com/mudita/MuditaOS)


---
1. クローズドソースの商用ハードウェアであってもホームアプリなど一部独自の基本ソフトウェアがオープンソースの場合でもオープンソースとして扱います。
2. 今のところ詳細不明のため Brax Technologies Brax3 は除外しておきます。気になる方は Youtube の Rob Braxman Tech のチャンネルを視聴のこと。
3. †がついているものは、このプロジェクトでリバースエンジニアリングやコードリーディング、またはハードウェアの試作など作業対象外です。ご了承ください。

## オペレーティングシステム
* [XNU kernel](https://github.com/apple-oss-distributions/xnu)

* [MuditaOS - Open Source E Ink mobile operating system | Mudita](https://mudita.com/products/phones/mudita-pure/muditaos/)

## 通信モジュール
* [LTE通信モジュール　MM-M61D | セイコーソリューションズ](https://www.seiko-sol.co.jp/products/mm-m61d/)
* [Quectel | End-to-end IoT solutions provider](https://www.quectel.com/) LTE EG25-G など。BG96 LTE は2025/10時点で[秋月電子](https://akizukidenshi.com/catalog/g/g118232/)でも購入可能
* [SIMCom Wireless Solutions - Wireless Modules and Solutions Supplier](https://www.simcom.com/)
* [4GPi](https://github.com/mechatrax/4gpi)
* [Pitalk 4G HAT](https://github.com/sbcshop/Pitalk_4G_HAT_Hardware) - オープンソースの Raspberry Pi 用の HAT モジュール (Quectel EG25-G 搭載) で音声通話対応。
* [openCom LTE](https://git.liberatedsystems.co.uk/jacob.eva/opencom-lte)

## 分解・修理
* [Pure disassembly pictures - Other - Mudita Forum](https://forum.mudita.com/t/pure-disassembly-pictures/4814)
* [Punkt MP02 Teardown - iFixit](https://www.ifixit.com/Teardown/Punkt+MP02+Teardown/164257)

## 周辺機器
### 固定電話風ヘッドセット

* [タカラ、携帯電話用の黒電話型パロディ受話器](https://k-tai.watch.impress.co.jp/cda/article/news_toppage/193.html)
* [なじむ、受話器が手になじむぞ――「アルミ製スタンド付き受話器型ヘッドセット」：“固定電話”感覚で通話できる - ITmedia PC USER](https://www.google.com/amp/s/www.itmedia.co.jp/pcuser/amp/1304/25/news155.html)
* [[News] スマートフォンが固定電話のように使える！通話しながら、Webの閲覧やアプリの操作ができる受話器付きスタンド 2製品を発売](https://www.elecom.co.jp/news/201107/mpa-ps001/index.html)
* iClooly PhoneStand Plus

一部を除き、あまり需要はないようですが。受話器型ハンドセットは受話器部分のものは手に入りますが、受話器台付きのものは中古でも入手困難です。もっとも、古すぎて今のスマートフォンでは動かすのは変換アダプタ(CTIA/OMTP→Bluetooth/USB)などを介するので少し手間ですが。

Buletoothハンドセットの場合、機種や通話アプリ、あるいはスマートフォンの対応スタックによっては音声遅延が起こることがあります。気になさる場合は有線ハンドセットとUSB変換アダプタを選択するといいでしょう。

### 固定電話→Bluetooth変換アダプタ
キーワード: Landline phone to Bluetooth

* [浜谷製作所 携帯電話－固定電話アダプタ｜携帯電話回線を固定電話回線に変換 iTalkS](https://ttrmkr.sakura.ne.jp/KeitaiAdapter/keitaiADPT.htm)
* [Cell2Jack](https://www.cell2jack.com/)
* Xtreme Technologies XLink BT HD X-BT2
* Sprint Phone Connect 3
* [Blue POT](https://github.com/danjulio/blue_pot)
* [Using a Raspberry Pi, Asterisk and a Bluetooth dongle to route phone calls through a mobile phone · Random kit](https://jtanx.github.io/2016/02/24/using-asterisk-to-route-calls-through-mobile/)
* weeBell Pot: [Hardware](https://github.com/danjulio/weeBell_hardware) / [Bluetooth (Firmware)](https://github.com/danjulio/weeBell_bluetooth)

日本国内で合法的に使えるのは iTalkS と ATA(Analog Telephony Adapter, IP電話アダプタ) + ルーターと PBX + Raspberry Piを使った方法のみです。

Blue POTはオープンソースハードウェアですので自作も可能ですが、使われているBluetoothモジュール(Microchip BM64)の技適認証に関する情報がないため個人で制作して合法的に使えるかは不明です。BM64は評価ボートでしか個人で入手できませんが、後継製品であるBM83(要設計変更)したら技適認証済みですし秋月電子ならモジュール単品で購入できるようです。→ [Bluetoothオーディオモジュール BM83: 通信・無線モジュール・アンテナ 秋月電子通商-電子部品・ネット通販](https://akizukidenshi.com/catalog/g/g130004/)

weeBell POT もオープンソースハードウェアですがアーキテクチャが異なります。

Raspberry Pi (国内正規流通品のみ) を使う方法でしたら合法的に使えますが機材の調達や設定などに少し手間がかかります (そして持ち歩けない)。記事が公開されたのは2016年なのでかなり古いだけでなく、設定も煩雑であるためある程度PCに詳しいパワーユーザーならお勧めしますが、何でもかんでも人に聞かないとできないライトユーザーにはお勧めできません。

### 携帯電基地局

ソフトウェア無線、2G以前(JTACS)の基地局エミュレータなどがあるようです。恐らく適切な無線局の免許がない者が使うと違法行為となりますのでご注意ください。

* [Open Source Mobile Communications](https://osmocom.org/)

