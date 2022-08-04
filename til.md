
### 2022/08/04
・Dockerのインストール  
　ここからインストーラをダウンロードして実行  
 https://www.docker.com/products/docker-desktop/  
 インストール完了後、再起動  
   
 再起動したらこんな警告が。  
![image](https://user-images.githubusercontent.com/102006535/182847531-6a5e9459-6884-43ed-aa70-9bdfbadd0e77.png)  
  
ここを参考にWSL2の有効化を行う  
手順4を実行してLinux カーネル更新プログラム パッケージをダウンロード・インストールする
https://docs.microsoft.com/ja-jp/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package  
そして「Restart」をクリック  
  
PowerShellを起動したらアップデートを求められたので、ついでにアップデート  
![image](https://user-images.githubusercontent.com/102006535/182848449-aaf1d631-b210-4e4e-8e98-79ce043c7569.png)  
  
PowerShellで下記コマンドを実行  
`winget search Microsoft.PowerShell`
  
その後、下記コマンドを実行  
`winget install --id Microsoft.Powershell --source winget`  
`winget install --id Microsoft.Powershell.Preview --source winget`

・ProgateでHTML CSS学習
　学習レッスン HTML & CSS 初級編の1~18まで

### 2022/08/03　
開発環境の構築？
・VS Codeのインストール
・Edge上のお気に入りの整理ｗ
・ブログの撤収(-\1,100/month)

