﻿# sphero_voice

## config.jsonに関して  

config.jsonは個人事に設定が違います。  
使用ポートに関してはBluetooth設定にあるCOMポートで確認できます。  
jsonに追加する場合、以下の書き方に従ってください。  
"spheroの色識別":"COMポート"  
config.jsonの作成はconfigsample.jsonを用いてください  
  
## 色識別について  

spheroの色識別は起動したさいに変わる3色の色に依存します。  
例えば、赤紫橙の順にループする場合。  
赤＝ＲＥＤ  
紫＝ＰＵＲＰＬＥ  
橙＝ＯＲＡＮＧＥ  
なので英語の頭文字のＲ、Ｐ、Ｏを連ねたＲＰＯが色識別になります  