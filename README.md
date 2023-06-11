# webcalendar
今回の作成ではXMLHttpRequestを使いローカルファイルを開いたためCORSポリシーに違反する形になりました
なので、祝日のcsvを読み込む際にchromeではショートカットを作成し、プロパティのリンク先を
~~ chrome.exe" --allow-file-access-from-files
に変えて開く必要があります。
