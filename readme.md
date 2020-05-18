### 作業内容
1. ~それぞれのチケット名でマイルストーン立てる~
2. マイルストーンごとに、issueを立てる
3. issueごとにブランチを切る  
   - [マイルストーンID]/[issue番号]_実施すること
   - ex) **%1/#1_add_main_component**
4. commit時は issue番号を含める
   - ex) **#1 add: main_component**
5. プルリク時に、説明文のところに
   ```
   close [issue番号]
   ex) close #1
   ```
   とすることで自動でissueを閉じてくれる。  
   `#1` がリンクになったらOK
