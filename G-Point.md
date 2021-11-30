# 広島学院文化祭ポイントシステム"G-Point"開発日記  
なんか一言

## 2.基本的な構造
gpoint/  
  ├ user_data/  
      (user_id).json  
      
  ├ club_data/  
      id2name.json  
      club_info.json  
      
  ├ backup/  
      (time).zip  
      
  ├ templates/
      nomal.html  
      select.html  
      free.html  
      
  ├ static/  
      ├ js/  
          nomal.js  
          select.js  
          free.js  
      ├ css/
          index.css
      ├ img/  
          fabicon.png
          
  main.py
  
  

## 4.  
APIの使用言語はPythonで、webフレームワークはFlaskです。本来はPHPを使用する予定でした。
しかし、私の学校の物理部(プログラム・電子工作などをしている部活)は9割以上Pythonを使用しているため、  
今後の引き継ぎなどを考慮してPythonを使用することにしました。

ユーザーデータなどの情報をどうやって保存するか、結論はJSON形式にしましたが今から考えれば、Mysqlなどにしておけばよかったと感じました。  
まぁJSONは見やすくて結果的に良かった気もしますが...  
30分に一回全ての
