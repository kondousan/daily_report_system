# daily_report_system
従業員の日報と出退勤を管理するアプリケーションです。

# DEMO 
![169b6e1b64ad825762d453846175449e](https://user-images.githubusercontent.com/104038494/188616744-3eb71697-cda7-4acd-95d2-e1348b7d59e6.gif)

 
# Features
- 従業員を登録し、 日報の作成・閲覧ができます。
- 従業員の管理は管理者のみが行えます。
- 日報の投稿時に出勤時間と退勤時間の登録ができます。
 
# Requirement
* Java(Java11)
* DB(MySQL8.0.23)
* AP(Tomcat9)
* Eclipse 2020
* Java Servlet API(4.0.1)
* mysql-connector-java(8.0.23)
* Hibernate(5.4.28.Final)
* Lombok(1.18.16)
* taglibs-standard-impl(1.2.5)
* javax.servlet.jsp.jstl-api(1.2.1)

# Usage
GitHubからプロジェクトをclone（ダウンロード）します。
 
```
$ git clone https://github.com/kondousan/daily_report_system.git
```
- Eclipseにインポートします。
- Tomcatの構成済みのリソースに追加します。
- 以下のファイルの接続タブを表示します。

　　/daily_report_system/src/META-INF/persistence.xml
- URL・ユーザー・パスワードをお使いのMySQLの情報に変更し、保存します。 

# Author
* Iori Kondo
