KAGParserPlus  
=============  
  
吉里吉里/KAGの拡張プラグイン  
  
■これはなに？  
　吉里吉里2/吉里吉里ZのKAGを少し便利にするものです。  
　※吉里吉里2で使用する場合は開発版が必要です。  
  
■機能  
　・タグの属性名を省略した場合に default 属性を付けます  
　・if, elsif, emb, jump, return, macro, erasemacro, call に default 属性の処理を追加  
　　例）[jump target="*ラベル"] → [jump "*ラベル"] という感じに書けます  
　・v0.9.2より属性名を省略した場合、属性名=true になりました  
　　※省略した属性名が default の場合は default=true になります（互換性のため）  
  
■使い方  
　吉里吉里のpluginフォルダにKAGParserPlus.dllをコピーし、startup.tjs 等に Plugins.link("KAGParserPlus.dll");を追加します。  
  
■ライセンス  
　吉里吉里本体のライセンスに基づきます  
  
■連絡先  
　不具合等はくつきくれむ(twitter @krmk2k)までお願いします。  
  
■謝辞  
　このソフトウェアは開発版であり、不具合が起きる場合があります。  
　このソフトウェアは吉里吉里ZのKAGParserのコードを使用しています。  
　W.Dee氏、Takenori Imoto氏をはじめ、吉里吉里の開発に関わったすべて方々に感謝します。  
  
