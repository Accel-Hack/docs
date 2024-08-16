### 1. gitのインストール
[こちら](https://qiita.com/T-H9703EnAc/items/4fbe6593d42f9a844b1c) を参考にインストール

※記事と異なる点:default editorにVisual Code StudioではなくVimを使用
### 2. IntelliJのインストール
[こちら](https://sukkiri.jp/technologies/ides/intellij-idea/intellij-idea-win.html)を参考にインストール　<br>
学生でまだ無料ライセンスを取得していない人は[取得する](https://blog.jetbrains.com/ja/2019/08/22/2105/)
### 3. Docker Desktopのインストール
[こちら](https://docs.docker.jp/docker-for-windows/install.html)を参考にインストール

※UEFI(BIOS)でハードウェア仮想化を有効にすることが求められた場合
[こちら](https://thewindowsclub.blog/how-to-enable-hardware-virtualization-in-uefi-bios-on-windows-11/)を参考に設定ページを開き、
矢印キーを使って[Security]→[Visualisation]に移動する

その2つの項目をスペースキーを押して[DISABLED]から[ABLED]にする
### 4. (任意） Sourcetreeのインストール
コマンドラインでgitを扱える人は不要

※GitHubとSourcetreeとの連携方法

インストールしたのち[ファイル]→[新規/クローンを作成する...]を順に選択

ホスティングサービス:Github 優先するプロトコル:SSH 認証:Personal Access Token と選択

Personal Access Token を再読み込みを選択し、ユーザー名にGitHubアカウントのユーザー名、パスワードにPersonal Access Tokenを入力

