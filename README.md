# Django-my-blog
2023/01作成、Djangoを用いて開発した個人ブログの練習プロジェクトです。
# 概要
Django3.0に基づいてfbv開発モデルで開発したもので、Djangoの実行に必要なツール以外、他のライブラリは使用しない。コンテンツの分類と管理、新規登録、ログイン、パスワード忘れ、プロフィール編集などの機能を実装した。ウェブにサイドバーも設計し、機能を一括集める。このサービスは主にusers、blog二つのアプリケーションが構成する。blogはブログのモジュールとviewメソッドと含む。mysiteはプロジェクトのdirで、mediaはメディアファイルアップロードdirで、staticは開発に必要な様式のdirで、utilsはツールのdirである。
# 実行手順：  
1.必要なライブラリとフレームワークのバージョンをまず**requirememts.txt**で確認してください。   
2.全体をダウンロードした後zipファイルを解凍し、manage.pyが所在するdirにアクセスする。  
3.ターミナルで**python -m venv venv**のコマンドでVenv環境を作る。**.\venv\Scripts\activate**でその環境を起動する。  
4.**pip install django**、**pip install pillow**でdjangoとpillowをインストールする。  
5.**python manage.py migrate**で全ての設定をデータベースに遷移する。  
6.**python manage.py createsuperuser**で管理員アカウントを作る、管理員アカウントがあると、プロフィールとブログの内容を編集できる。スキップしても構わぬ。  
7.**python manage.py runserver**、サーバーを起動する。
8.ターミナルでURLをクリックするとアプリケーションのウェブページにアクセスできる。


