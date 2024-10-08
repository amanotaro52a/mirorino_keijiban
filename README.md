■サービス名
緑の掲示板

■サービス概要
野菜、花、果樹など、ご家庭で育てている植物を、成長段階ごとに画像、説明文を載せて行き、最終的には一つの観察日記ができる様になります。できた観察日記はcookpadの様に投稿することが出来て、様々な植物の観察日記を閲覧できるサービスです。

■ このサービスへの思い・作りたい理由
大学時代は農学部に所属、家では家庭菜園を趣味として野菜や花を育てていました。その時市販で売られている育て方の本と実際に育てている環境とでは生育状況に遅れや生じたりすることも多々あります。そこでこのサービスを利用することで、同じ環境や条件での育成日記を見つけることで課題の改善することができる他、変わった育成方法も見つけることが可能で、家庭菜園の幅が広くなるのではないかと考え今回作ってみようと思いました。

■ ユーザー層について
主婦・一人暮らし・家庭菜園が好きな人理由：本サービスを農家向けた栽培方法の閲覧サービスにしてしまうと、土地や肥料等の生育費用がかかり、参考にできるユーザーが限られてしまうからです。

■サービスの利用イメージ
RUNTEQの質問フォームの様に最初に
→タイトル、育てる植物(種子の情報も含む)、育てる方法(例：路地で栽培か、プランターで栽培か)、必要な資材や肥料を書き込んで、投稿ボタンを押したら、あとは生育状況をコメントのように投稿する形で育成終了まで掲載し続ける形です。

■ ユーザーの獲得について
家庭菜園を行なっている人達をターゲットにユーザーを獲得できたらと考えています。普段から家庭菜園を趣味として行なっている人にとって、情報源の供給の多くは、同じ趣味を持つ近所の伝手が多いです。その伝手を利用して本サービスのユーザーをじっくり獲得しようと考えています。また、コミュニティーを全世界に広げるという観点で、様々な環境下での育成方法を共有することができ、幅広く知識を習得することができます

■ サービスの差別化ポイント・推しポイント
・今回作ろうとしているサービスに似たもの
タイトル：農業屋
コンテンツ名：家庭菜園でつながるみんなの菜園日記
URL: https://nogyoya.jp/fc/post/
・差別化・推しポイント
一言文章を書いて終わりにする形ではなく、育て方の手順を作る事が出来、画像付きで説明文やコメントを記述して、投稿することが可能。これにより、一目で見て成長の段階を追うことができ、育てる植物のイメージを把握することが可能です。また育てながら投稿したいというユーザーに対応できるように未完成でも下書きとして保存できるところも備えています。

参考：[![Image from Gyazo](https://i.gyazo.com/7f2f5e44ca7131f3ec58c24b669b4def.jpg)](https://gyazo.com/7f2f5e44ca7131f3ec58c24b669b4def)
　　　( https://cookpad.com/recipe/post/help　) より抜粋

→添付した図面の５番の機能が育て方の手順のイメージです。


■ 機能候補

基本機能：
トップページ
検索・一覧表示
詳細
会員登録・ログイン
コンテンツ投稿

高度な機能：マルチ検索・オートコンプリート画像アップロード機能ステップ入力・確認画面

フリーワードで検索できる機能を設けたいです。

■使用予定の技術スタック (予定)
・開発環境: Docker
・データベース: PostgreSQL
・サーバサイド: Ruby on Rails 7系
　　Ruby ruby 3.1.4p223 Rails 7.0.4
・インフラ: Heroku


■ 機能の実装方針予定
見積中。

###　画面遷移図
Figma：https://www.figma.com/design/FmEMws8ZvGzCD46H9HXjiW/Untitled?node-id=31-58&m=dev&t=3i0uKaflZp34jjKP-1

### ER図
[![Image from Gyazo](https://i.gyazo.com/b294de92f321c07878162366cdff507e.png)](https://gyazo.com/b294de92f321c07878162366cdff507e)