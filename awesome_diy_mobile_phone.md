
仕様や比較表など用意するのが手間なので解説は後回しです。
それと制作しても日本国内では電波法の兼ね合いから使用できませんので参考資料です。あしからず。

## 携帯電話・スマートフォン(オープンソース製品)
* [evanman83/OURS-project: Step-by-step instructions to build a smartphone that is open-source, upgradeable, repairable, and Big Tech free.](https://github.com/evanman83/OURS-project)
* [libresmartphone/libresmartphone: This page contains the software used in the open hardware smartphone (libresmartphone)](https://github.com/libresmartphone/libresmartphone)
* [mudita/MuditaOS: Mobile operating system based on FreeRTOS™ optimized for E Ink displays - developed for Mudita Pure minimalist phone](https://github.com/mudita/MuditaOS)
* [mikroPhone](https://mikrophone.net/)
* [Rotary Un-Smartphone](https://skysedge.com/telecom/RUSP/index.html)
* [Librem5](https://puri.sm/products/librem-5/)
* [Precursor](https://www.crowdsupply.com/sutajio-kosagi/precursor)
* [PinePhone](https://pine64.org/devices/pinephone/)
* [Openmoko](https://www.openmoko.org/wiki/Main_Page)
* [WiPhone](https://www.wiphone.io/)
* [SIP Phone based on Olimex ESP32-ADF, MOD-LCD2.8RTP boards.](https://github.com/OLIMEX/sip_phone_example)
* []()
* []()

## 通信モジュール


* [LTE通信モジュール　MM-M61D | セイコーソリューションズ](https://www.seiko-sol.co.jp/products/mm-m61d/)
* [Quectel | End-to-end IoT solutions provider](https://www.quectel.com/) LTE EG25-G など。BG96 LTE は2025/10時点で[秋月電子](https://akizukidenshi.com/catalog/g/g118232/)でも購入可能
* [SIMCom Wireless Solutions - Wireless Modules and Solutions Supplier](https://www.simcom.com/)
* 

基本的に国内仕様のもので個人が手にいれられるものはデータ通信専用でほとんどが中国メーカー製です(しかも正規代理店経由以外で買うと技適認証まわりが偽造されているなど怪しいものがある恐れ)。試作用にSoftbank Simplyなど安価なガラホから剥がそうにしても通信モジュール単体ではなく恐らくSoCなので目的が違うでしょう。まあ、音声通話に関しては特許がらみなどで少し厄介なようです。Librem 5やOpenmokoの回路図を調べるとわかる通り音声通話に対応しているかどうかはチップにアナログ音声出入力用の端子があり音声回路(例えばアンプ回路、DSP、スピーカーやマイク)とMPU(通信モジュールの制御用)に接続されているか否かですが。無ければクラウドPBXなど必要になるでしょう。

## 分解・修理
* [Pure disassembly pictures - Other - Mudita Forum](https://forum.mudita.com/t/pure-disassembly-pictures/4814)
* [Punkt MP02 Teardown - iFixit](https://www.ifixit.com/Teardown/Punkt+MP02+Teardown/164257)
