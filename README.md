## knowledge

===============

### Free Knowledge Management System


#### Live Demo
- https://support-project.org/knowledge/index
- Demo users
   - [id/password] user1 / user1
   - [id/password] user2 / user2
   - [id/password] user3 / user3


#### Project website
- https://support-project.org/knowledge_info/index


#### 概要
- Knowledgeは、フリーの情報共有サービスです。
- 社内などで閉じた情報の管理が出来ます。


#### 特徴
- Markdown記法で情報登録
- 記事のタイトル/本文を全文検索で目的の情報を探せます
- 情報の公開範囲を、「公開」「非公開（自分のみ）」の指定ができます
   - いずれ、指定したユーザに公開/グループに公開などを行えるようにします（予定）
- 情報に付けたタグで、情報の種別の管理を行えます
- 添付ファイルを登録できます
- 添付ファイルの中身でも検索できます
- サービスのファイル(war)を置くだけの簡単デプロイ


#### サービスのデプロイ方法
- Tomcat 7.0 以降をインストール
   - http://tomcat.apache.org/
   - Tomcat でなくても、Servlet3.0 以降に対応しているサーバーであれば動作すると思います
- knowledge.war をダウンロード
- Tomcatのwebappsディレクトリに、knowledge.warを置く
   - warが配備され使えるようになります


#### アプリケーションのデータ(バックアップ)
- Tomcatの起動ユーザの、ホームディレクトリに「.knowledge」というフォルダを作成し、その中にデータを格納します
   - データのバックアップは、このディレクトリをコピーしておくことで可能です
   - Linuxなどでは、Tomcat起動ユーザで上記のディレクトリにアクセス出来るように、権限を設定してください




