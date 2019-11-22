#  手順1: Twilioアカウントの作成
## はじめに
この手順では、Twilioアカウントを作成します。既にアカウントを作成し、コンソールにアクセスできている場合は、[手順2](./01-02-PurchasePhoneNumber.md)へ進んでください。
## 1-1. アカウントの作成を開始
[Twilioホームページ](https://www.twilio.com/)をブラウザーで開き、[Sign Up](https://www.twilio.com/try-twilio) をクリックします。

![Twilioホームページ](../assets/01-WebSite-SignUp.png "Twilioホームページ")

First Name（名）、Last Name（姓）、Email、パスワード(14文字以上)を入力し、サービス提供条件ならびにブライバシーポリシーを確認したのち、__Start your free trial__ をクリックします。

![サインアップ](../assets/01-SignUp.png "サインアップ")

## 1-2. Emailアドレス、電話番号の確認、コンソールのセットアップ
登録したEmailに確認メールが送られます。メール本文の __Confirm Your Email__ をクリックし、アカウントを有効化させます。

![確認Email](../assets/01-ConfirmationEmail.png "確認Email")

リンクをクリックすると、続けて電話番号の確認が行われます。トライアルを開始するためには、SMSを受信可能な電話番号が必要になります。

![電話番号確認](../assets/01-PhoneVerification.png "電話番号を確認")

よく使用するプログラミング言語を選択できます。いくつか選択肢が出てきますが、ここではNoを選択し続けて __Skip to dashboard__ ボタンを押しても構いません。

![Preferences](../assets/01-Preferences.png "Preferences")

これでサインアップは完了です。

## 1-3. コンソールへのアクセス
Twilioのさまざまなサービスの利用状況の確認や設定はコンソールから行う事ができます。
コンソールには、[Twilioホームページ](https://www.twilio.com/)をブラウザーで開き、[LOG IN](https://www.twilio.com/login) をクリックするか、[コンソール](https://www.twilio.com/console)に直接移動します。

特に名前を設定していなければ、「__My first Twilio project Dashboard__」が表示されています。このコンソールでは、プロジェクトに紐づいているクレジットの合計を確認できます。

![Twilioコンソール](../assets/01-Console.png "Twilioコンソール")

また、個別のプログラムからTwilioのサービスを利用できるACCOUNT SID、AUTH TOKENを確認できます。

## 1-4. トライアルアカウントを利用した場合の制限
トライアルアカウントを利用する場合は、以下のような __制限__ があります。

- トライアルアカウントで取得できる電話番号は１つのみです。複数の番号を取得する場合は、アカウントをアップグレードする必要があります。
- トライアルアカウントから送信、架電できる番号はあらかじめ認証された [verified numbers](https://www.twilio.com/console/phone-numbers/verified) のみです。
- SMSや電話の冒頭にトライアルアカウントを利用している旨を伝えるメッセージ（英語）が流れます。

その他の制限については関連リソースをご覧ください。

## 関連リソース

- [無料のTwilioトライアルアカウントの使用方法](https://jp.twilio.com/docs/usage/tutorials/how-to-use-your-free-trial-account)


## 次の手順
[手順2: Flexプロジェクトの作成](./01-02-CreateFlexProject.md)