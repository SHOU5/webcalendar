# 開き方
開くには、index.htmlを実行します。
# syukujitu.csvを呼び出す際の注意
今回の作成ではXMLHttpRequestを使いローカルファイルを開いたためCORSポリシーに違反する形になりました。
なので、祝日のcsvを読み込む際にchromeではショートカットを作成し、プロパティのリンク先を  
~~ chrome.exe" --allow-file-access-from-files  
に変えて開く必要があります。  
![プロパティ](https://github.com/SHOU5/webcalendar/assets/135721465/05c92b74-0ea1-48ed-9b90-f486ab8f94fb)
