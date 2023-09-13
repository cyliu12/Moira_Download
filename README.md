# Moira_Download
提供Windows可執行的Moira七政四餘排盤軟體檔案

2023/9/12
Moira.msi
  原作者發布的最後一版，Moira 1.50 Final。要搭配x32的JRE使用。
source.zip
  原作者發布的source，原本的網站連結已失效，這是我留下來的備份。
How to build - Moira - 七政四餘星盤 天星擇日 占星盤 - Moira.pdf
  原作者寫的build指引，原本的網站連結已失效，這是列印下來的備份。
Moira.6410.0001.zip ~ z04 
  我重新Build的x64版本，需搭配x64的JRE 1.8以上使用。請下戴zip~z04。
  這個壓縮檔包含了較多的ephe星曆(到公元前都有)，所以比較肥大。
  之後若有更新，就只發布Moira.exe跟Moira.jar就可以了。
  這是用Launch4j打包的，無法釘選到開始或工作列。
  完整的版號是Moira 1.50.6410.0001。
  1.50是繼承原作最後一版，如果在立命推移部份有修改，會在這裡進版，以利區別。
  6410，64代表x64，10代表Windows 10相容。(Windows 11也可以執行，但是按鈕箭頭不見，醜。)
  與星命本質無關的修改會在0001這裡進版。目前做的修正如下
    1. 設定值原本存在windows registry，現在存在資料夾下的.prefs檔，刪掉這個檔就能恢復預設。
    2. 說明->關於->可以在視窗抬頭看到完整版號。

  已知問題(與原版的差異)
    1. 檢視-> 鄭氏四十星案與星度指南例的選項不見了。
    *已解決。原因是source裡面不含example跟help，所以鄭氏四十星案與星度指南例的選項不見操作說明變成找不到頁面。
      安裝原作者發布的版本後就可以取得example跟help，把這兩個資料夾放到Moira的資料夾下即可。

  Moira Example & Help.zip  正確顯示鄭氏四十星案、星度指南例、與操作說明所需的檔案。

  Moira 1.50.6410.0002.zip  改善工具列顯示，在2K及4K解析度下，工具列會顯示較大的圖示。
    雙擊工具列左側空白處可重整工具列圖示。
    將解壓縮後的檔案覆製至其他版本的Moira資料夾下，覆蓋己存在的檔案，即可更新版本。
    需要JRE 1.8以上

  Moira 1.50.6411.0002.zip  改善工具列顯示，在2K及4K解析度下，工具列會顯示較大的圖示。
    雙擊工具列左側空白處可重整工具列圖示。
    將解壓縮後的檔案覆製至其他版本的Moira資料夾下，覆蓋己存在的檔案，即可更新版本。
    需要Eclipse Adoptium jre-17.0.8.101-hotspot或以上。(OpenJDK)
