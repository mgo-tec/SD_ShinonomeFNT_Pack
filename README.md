# SD_ShinonomeFNT_Pack
This is the Arduino & SD card library for reading Shinonome 16x16 font. (For ESP8266) 

Beta ver1.0

これはShift_JISコードからフリーの東雲フォント(16x16)をESP-WROOM-02(ESP8266)で読み込むためのライブラリです。  
SPI接続のSDカードからの読み込み専用です。  
UTF8toSjisライブラリをインクルードしているので、１行の関数のみでUTF-8文字列から16x16ドットの日本語漢字に変換できます。  

予め以下のファイルをSDカードにコピーしておく必要があります。  
（fontというフォルダを作成しておくと良いです。）  
※ファイル名は半角英数字8文字、拡張子3文字  

Utf8Sjis.tbl (UTF-8 Shift_JIS変換テーブル)  
shnmk16.bdf (全角東雲フォント)  
shnm8x16.bdf (半角東雲フォント, ファイル名の'r'をカットしたもの)  
  
【更新履歴】  
(1.0.1)  
whileループ内でyield()を追加しただけです。


Licence:

  MITライセンス

  東雲フォントは/efont/さんが保守開発を行い、ライセンスはPublic Domainです。


詳しくはブログ参照：

https://www.mgo-tec.com
