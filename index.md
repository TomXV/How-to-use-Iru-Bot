# ヘルプ/Help
---
このBot(イルーくん)のPrefixは`!iru `です!
This bot's prefix is !iru
### English version is at bottom
---
# CURRENTLY IN UPDATE
## 日本語 (JP)
### 設定コマンドの説明
|コマンド|Alias(通称:別の書き方)|説明|例文|
|-|-|-|-|
|voice|voices|ユーザーの声の設定ができます!|(ややこしいので詳しい説明は下に!)|
|show|showvoices, showvoice, koe|ユーザーの声の設定が見れます!|!iru setting show|
|showsetting|showsettings|今いる鯖の設定が見られます!|!iru setting showsettings|
|name|username|読み上げ時にユーザー名を読み上げる設定ができます!|!iru setting name|
|botread|br, bn, botname, readbot, rb|イルーくんの文章を読み上げる設定ができます!|!iru setting botread|
|mention|mentions|メンションの読み上げの設定ができます！|!iru setting mention|
|readotherbot|readotherbots|イルーくん以外のBotの文章の読み上げができます!(ただし, おすすめしません!)|!iru setting readotherbot|
|length|ln, wordlength, limit, wordlimit, wl|読み上げる文字数の設定ができます! (100文字-2000文字)|!iru setting length 250|
|emoji|emojis, reademoji|絵文字の読み上げができます!|!iru setting emoji|
|deleteallword|dal|サーバーに登録したカスタム読み (辞書) を全部消します! (取り扱い注意!)|!iru setting deleteallword|
|deletebotmessage|dbm|イルーくんが自動で自身のメッセージを消すか判断します!|!iru setting deletebotmessage|
|language|lang|他の言語に変える事ができます! (今は: 日本語と英語のみ)|!iru setting language|
|prefix|changeprefix, cp|サーバー固有のPrefixの設定ができます!|(ややこしいので説明は下に!)|
|resetsettings|defaultsettings, defaultsetting, resetsetting|Botの設定を初期化します!|!iru setting resetsettings|
|adduserblacklist|aubl|指定したユーザーをBotの使用から制限します!|!iru setting adduserblacklist @Airun|
|addroleblacklist|arbl|指定したロールをBotの使用から制限します!|!iru setting addroleblacklist @examplerole|
|removeuserblacklist|rubl, dubl|指定したユーザーをBotの使用の制限を解禁します!|!iru setting removeuserblacklist @Airun|
|removeroleblacklist|rrbl, drbl|指定したロールをBotの使用の制限を解禁します!|!iru setting removeroleblacklist @examplerole|
|settings|setting|サーバー、ユーザに関する細かい設定を行えるコマンドです!|!iru settings|
|troubleshoot|ts|読み上げが動かなくなった時の対処法が書かれてるコマンドです!|!iru troubleshoot|
|voicelist|vl|対応してる声優さんのリストの確認するコマンドです!|!iru voicelist|
|hello|join, start, s, connect|イルーくんをボイスチャットに呼ぶことができます!|!iru hello|
|bye|leave, disconnect, end, e|イルーくんをボイスチャットから切ることができます!|!iru bye|
|reboot|rb|イルーくんを読み上げなくなった時、トラブル、単に読み上げの停止などに使うコマンドです!|!iru reboot|
|move|m|イルーくんを今ユーザーがいるボイスチャンネルに呼ぶことができるコマンドです!|!iru move|
|send||イルーくんを指定したボイスチャンネルに送ることができます!|!iru send General|
|addword|aw|サーバー特有の読み方を登録できるコマンドです!|!iru addword foo ふぅー|
|deleteword|dw|サーバー特有の読み方を削除できるコマンドです!|!iru deleteword baba ばば|
|addchannel|ac|読み上げたいメッセージチャンネルを登録できます!|!iru addchannel general|
|deletechannel|dc|読み上げたくないメッセージチャンネルを足すよ!|!iru deletechannel general|
|||||
|コツ:|1: 文字やチャンネルにスペース、もしくは特殊記号が入ってる場合はクォーテーションマーク(コレ→"")で囲うと動きます!|2: メッセージが遅れてくるのは当然の事です。むやみにコマンドを送らず、早くても30秒から1分は待ちましょう。|3: 「習うより慣れろ」です! どうかBotを堪能して、楽しんでください!|

---

## Voiceコマンドの使い方:
ボイスコマンドはユーザーが指定したボイスに変更することができます!設定できる項目が多いので注意しながら設定してください!

### 注意:
* イントネーションとフィルターを `0` と `0.5` として登録してください! (高度利用者向けの設定です!下手すると壊れます!)
* `!iru vl`で使えるボイスの確認する事をオススメします！

|例|コマンド|
|-|-|
|声(日本語):「woman」声(英語):「bdl」 速度:「1.5」イントネーション:「0」フィルター:「0.5」 音程「0」|`!iru settings voice woman 1.5 0 0.5 0 bdl`|
|声(日本語):「man」声(英語):「slp」 速度:「1.25」イントネーション:「0」フィルター:「0.5」 音程「5」|`!iru settings voice man 1.25 0 0.5 5 slp`|
|声(日本語):「mei_angry」声(英語):「lnh」 速度:「1.75」イントネーション:「0」フィルター:「0.5」 音程「-2」|`!iru settings voice mei_angry 1.75 0 0.5 -2 lnh`|

### ボイス設定の項目で設定できる範囲:
|項目|範囲|
|-|-|
|声(日本語)|`!iru vl` で確認を!|
|声(英語)|`!iru vl` で確認を!|
|速度|`0.5` から `15.0` の間に設定してください!|
|イントネーション|`0.0` から `1.0` の間に設定してください!|
|フィルター|`0.0` から `1.0` の間に設定してください!|
|音程|`-30.0` から `30.0` の間に設定してください!|

---

## Prefixコマンドの使い方:
サーバー固有のPrefixの設定ができます!もし書きやすいコマンドなどがあれば、これで変えてください!

### 注意:
* スペースは自動で消される仕組みになっています。本当にスペースが必要ならコマンドの項目の一つを `1` に変えてください!

|例|コマンド|
|-|-|
|「readout!」|`!iru settings prefix 0 readout!`|
|「??」|`!iru settings prefix 0 ??`|
|「!yomi 」|`!iru settings prefix 1 !yomi`|

### Prefix設定の項目で設定できる範囲:
|項目|範囲|
|-|-|
|Prefixの後にスペースの有無|`0` か `1` で! (`0` がオフで `1` がオンです!)|
|新Prefix|ご自由に!(ただし、スペースは認識されないのでそれだけはご注意を.)|

---
## English (EN/US)
### Explanation to the commands

|Command|Alias|Explanation|Sample|
|-|-|-|-|
|settings|setting|This can edit the detailed setting for the user or the server!|!iru settings|
|troubleshoot|ts|This will show the checklist when the bot stops working!|!iru troubleshoot|
|voicelist|vl|This command will list out the available voices!|!iru voicelist|
|hello|join, start, s, connect|This will call Iru to the voicechat!|!iru hello|
|bye|leave, disconnect, end, e|This will disconnect Iru from the voicechat!|!iru bye|
|reboot|rb|If Iru is having troubles reading messages, not reading messages, or stop reading the current message: use this command!|!iru reboot|
|move|m|This will move Iru to the current voicechat!|!iru move|
|send||This will send Iru to the selected voicechat!|!iru send General|
|addword|aw|This will add the serever's unique pronunciations to the word!|!iru addword ふぅー foo|
|deleteword|dw|This will delete the server's unique pronunciations to the word!|!iru deleteword ばば baba|
|addchannel|ac|This will add the message channels that is need to be read out!|!iru addchannel general|
|deletechannel|dc|This will add the message channels that does not need to be read out!|!iru deletechannel general|
|||||
|Tips:|1: For words or channels which includes space, or has a special symbol, please surround it with the quotation marks to make it work (Like: "oh dear")!|2: It is quite common for to have some lags, so do not spam the commands! Instead, please wait at least 30 seconds to 1 minute for bot to process the commands. |3: "Practice makes perfect!" Please use to the bot frequently, and have fun with the bot!|