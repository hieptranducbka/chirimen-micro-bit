<p align="right">Language: <a href="https://chirimen.org/chirimen-micro-bit/">Japanese</a>, <a href="https://translate.google.co.jp/translate?sl=ja&tl=en&u=https%3A%2F%2Fchirimen.org%2Fchirimen-micro-bit%2F">English (Google Translation)</a></p>

![CHIRIMEN with micro:bit](imgs/CHIRIMEN_MICROBIT.png "CHIRIMEN with micro:bit")

# CHIRIMEN with micro:bit

## 概要
[micro:bit](https://microbit.org/)を利用した[CHIRIMEN環境](https://chirimen.org/#about)の実装を公開しています。CHIRIMENとはボードコンピュータの端子につないだセンサやアクチュエータを使用した(ブラウザ上で動作する)ウェブアプリを動作させる環境です。[WebGPIO](https://github.com/browserobo/WebGPIO)と[WebI2C](https://github.com/browserobo/WebI2C)が使えるようになります。
micro:bitではウェブラウザは(多分)動きませんが、Bluetoothを介して、PC等のウェブブラウザ(ChromeなどwebBluetoothをサポートしたもの)とmicro:bitを接続することで、CHIRIMEN環境を構築します。
また、CHIRIMEN with micro:bitでは、WebGPIO,WebI2Cに加え、micro:bitが内蔵しているセンサーやLEDをウェブアプリで使うことができる機能が追加されています。

## Web Page
このリポジトリは以下のURLからウェブサイトとしてアクセスできます。
- https://chirimen.org/chirimen-micro-bit/

## スタートアップガイド
[TBD](TBD)

## Examples
以下のページに使用例を掲載します。
- [Examples](https://chirimen.org/chirimen-micro-bit/examples/)

### 注記
この実装は、webGPIOだけを実装した[webGPIO-etc-on-microbit-via-webBluetooth](https://github.com/chirimen-oh/webGPIO-etc-on-microbit-via-webBluetooth)を前身として持ちます。しかしmicro:bitのリソース上の制限から、この実装はそれとまったく異なるものになっています。

