# 静電容量式レインセンサ検出基板

## 概要
静電容量式のレインセンサに付着した水滴を検出する基板です。
この基板だけで雨の検出はできませんので、別売の[静電容量式レインセンサ基板](https://naoto64.github.io/Capacitive-Rain-Sensor/)を使用します。

レインセンサに雨粒が落ちると静電容量が大きくなります。この基板ではセンサの
静電容量を監視して、降雨の有無を外部に信号を出力します。
出力機能は5ビットDACからのアナログ出力と、デジタル出力を備えています。
この回路はセンサに雨粒がついているかどうかで降雨の判断をしています。
雨が上がった場合でも、雨粒が付着している場合は降雨ありとして出力します。

## 購入
この製品は以下のサイトから購入できます。  
[スイッチサイエンス - 静電容量式レインセンサ検出基板](https://www.switch-science.com/products/9363/)

#### お問い合わせフォーム
[製品に関するお問い合わせ](https://forms.gle/Fn5E3byABXJ8P5sbA)
## 静電容量式センサの特徴
電極式のレインセンサでは、電極に電流が流れるため、電極が腐食してしまう場合がありますが、この静電容量式レインセンサは、
電流が流れないため電極が腐食しません。
また、電極式のセンサは電極の電圧を読み取るだけでよいため制御が簡単ですが、静電容量式の場合は検出回路が必要になります。
この基板は、アナログ出力とデジタル出力のシンプルな構成ですので、簡単にご使用いただけます。

## 使用方法
![使用方法](https://raw.githubusercontent.com/naoto64/Capacitive-Rain-Detector/main/docs/usage.png)

## 基板イメージ図
![基板イメージ図](https://raw.githubusercontent.com/naoto64/Capacitive-Rain-Detector/main/docs/rain-capacitance-sensor.jpg)

## 基板寸法図
![基板イメージ図](https://raw.githubusercontent.com/naoto64/Capacitive-Rain-Detector/main/docs/board-dimension-diagram.png)

## 基板回路図
![基板回路図](https://raw.githubusercontent.com/naoto64/Capacitive-Rain-Detector/main/docs/rain-capacitance-sensor-schematic.png)
