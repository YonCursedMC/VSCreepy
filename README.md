<img alt="GitHub Downloads (all releases)" src="https://img.shields.io/github/downloads/YonCursedMC/VSCreepy/total?style=for-the-badge">

# JP

## VSCreepy
Creepyバトル どちらが最初にダイヤモンドを手にする事ができるのか？！

### これは？
* ダイヤモンドを最初に「手に持つ」ことが目的の対戦型ゲームです。
* 怪奇現象で妨害しよう
* サーバー限定です
* 実質Creepy Minecraft Versionではありません。

### 注意事項
- このバージョンはMojang公式から実際に出されたものではなく、また公式に認定されたものでもありません。
- このバージョンをプレイして発生した損害に関しては製作者は一切の責任を負いません。
- 無断転載は禁止です。もし発見したら報告します。
- MCPのライセンスによりコードは公開しません。
- 点滅やドッキリ要素、ホラー音が多いです。やる際は十分注意してください。
- かなり重いです。やる際はそれなりのCPUやビデオボード、RAMを搭載したPCをご用意ください。
- 実況などで使う場合は、このバージョンのURLのクレジット表記をしてくれると嬉しいです。
- クラッシュすることがありますが仕様です。
- WindowsPC推奨です。Androidなどだと一部怪奇が起こらないかもしれません
- 結構な頻度でとんでもない挙動をすることがあります。自己責任で実行して下さい。

### プレイ方法(起動)
* クライアントの方は、MultiMC or PrismLauncher(PrismLauncher推薦)で起動します。
* [こちら](https://github.com/YonCursedMC/VSCreepy/releases)からダウンロードできます。「VSCreepy.zip」というものをダウンロードしてください。
* (サーバー管理者のみ) サーバーは、「VSCreepy_server.jar」というものをダウンロードしてください。起動方法は普通のサーバーと同じです。
* (サーバー管理者のみ) 勝利したらワールドリセットする必要がある(再起動する必要がある)ので注意です。(エラーが出てサーバーが停止します。)
* サーバーに入れたら、OPがチャットに```/startgame```と打ってください。

### プレイ方法(ルール、操作方法)
<img width="600" height="300" alt="GameGui" src="https://github.com/user-attachments/assets/423fc59c-f6d2-4887-8c93-da58e3577e63" />

* OPがチャットに```/startgame```とチャットに打つとゲームが始まります。
* チームの誰かが**ダイヤモンドを手に持つ**ことが目的です。(インベントリに入れるだけではだめです。持つことが目的です。)
* チームはランダムで、1チーム、2チームに分かれます。
* 1チームは-X座標、2チームは+X座標です。そちら以降はいけません。もし座標が不平等(隣が海だったり)であれば、ワールドを作成し直すと良いでしょう。
* 時間が立つとポイントが溜まります。40Tick(2秒)ごとに1たまります。
* 奇数などでチームメンバーが少ない場合は、少ないチームが+2になります。
```
鉱石採掘+5
動物討伐+3
mob討伐+5
呪いエンティティ討伐+10
ダメージを受ける+3
```
みたいな感じで貯める事もできます。
* ポイントはプレイヤーごとで、チーム共有ではありません。
* ポイントが100まで溜まったら、```/creepy```と打ちましょう。相手のチームに怪奇現象が起き妨害できます。
* 怪奇現象はランダムに起きます。何が起こるかはお楽しみです。
* 時間は1000固定です。その代わり、ベットを右クリックすることによりリスポーン地点を固定できます。
* OPが、```/stopgame```コマンドを打つとゲームを中断することができます。

<details>
<summary>怪奇現象の種類(ネタバレ注意)</summary>
  
  * Public Voidが出てくる、攻撃されるとキックされて消える
  * Binary444が出てくる、攻撃されると別の場所にテレポートしてしまい消える
  * That Whiteが出てきて、攻撃されるとアイテムをばらまかれる
  * 雷が大量に落ちる
  * 画面に文字が大量に出てくる
  * 床が抜ける
  * 勝手に移動する
  * LagMobが出てきて、攻撃されるとFPSが下がる
  * LongFixが出てきて、攻撃されると持ってるアイテムをすべて消される
  * LengthFlagが出てきて、攻撃されるとポイントが0になる
  * LongleggedAlexが出てきて、攻撃されるとPCがブルスクもどきを出してクラッシュする
  * LongleggedJebが出てきて、攻撃されると消すのがめんどくさいウィンドウが出てくる
  * Tikthinkが出てきて、攻撃されると大爆発する
  * 急に爆発する
  * 岩盤の十字架が出てくる
  * 看板が出てくる
  * 謎のソフトが起動する
  * ディスクが勝手に開く
  * プッシュ通知が出る
  * 電卓とかメモ帳とかが勝手に開く
  * GUIがバグり、変な音がなる
  * 動けなくなり、チャットが大量に出てくる
  * 岩盤部屋が出てきて、TheWatcherに...
  * HeroVoidが出てくる、攻撃されるとモーダルウィンドウが大量に出てきて消える
  * ウィンドウが小さくなり、突然震えだす
  * アイテムがシャッフルされる

</details>

わからないことや、バグなどがあればissueなどに書いてください。

### クレジット

#### テクスチャ
- Test_Alpha
- Tei
#### 効果音
- 音人 https://on-jin.com/
- pixabay https://pixabay.com/
- freesound? https://freesound.org
#### 利用ツール
- Intelij IDEA
- RetroMCP
- Gemini Nano Banana
- Perplexity
- Claude

# EN
## VSCreepy

### Creepy Battle

Who will be the first to get a diamond?!

---

### What is this?

* This is a competitive game where the goal is for **holding a diamond first**.
* Use paranormal phenomena to interfere with your opponents.
* Server-only.
* Not exactly the Creepy Minecraft Version.

---

### How to Play (Setup)

* Clients should launch the game using **MultiMC** or **PrismLauncher** (PrismLauncher recommended).
* Download from here: [https://github.com/YonCursedMC/VSCreepy/releases](https://github.com/YonCursedMC/VSCreepy/releases)
  → Download **“VSCreepy.zip”**
* (Server admins only) Download **“VSCreepy_server.jar”** The startup method is the same as for a regular server.
* (Server admins only) After a win, the world must be reset (server restart required).
  Note: The server will stop due to an error.
* Once everyone has joined the server, the OP should type ```/startgame``` in chat.

---

### Important Notes
- This version is not officially released by Mojang, nor is it officially certified.
- The creator assumes no responsibility for any damage caused by playing this version.
- Unauthorized reproduction is prohibited. We will report any instances of this being discovered.
- Due to the MCP license, the code will not be released.
- Contains many flashing lights, jump scares, and horror sounds. Please play with caution.
- This is quite resource-intensive. Please ensure you have a PC with a decent CPU, video card, and RAM before playing.
- If you use this in a live stream or similar, we would appreciate it if you credit the URL of this version.
- Crashes may occur, but this is by design.
- Windows PC is recommended. Some strange occurrences may not happen on Android, etc.
- This game may behave very frequently and unexpectedly. Please proceed at your own risk.

---

### How to Play (Rules & Controls)
<img width="600" height="300" alt="GameGui" src="https://github.com/user-attachments/assets/423fc59c-f6d2-4887-8c93-da58e3577e63" />

* When OP types ```/startgame``` in the chat, the game starts.
* The goal is for someone on the team to **hold a diamond in their hand**. (Simply putting it in the inventory is not enough. The goal is to hold it.)
* Teams are assigned randomly into Team 1 and Team 2.
* Team 1 stays on the **-X side**, Team 2 on the **+X side**.
  Do not cross beyond your side.
  If the terrain is unfair (e.g., ocean nearby), regenerate the world.
* Points accumulate over time:
  +1 point every 40 ticks (2 seconds)
* If the number of team members is small due to an odd number, etc., the smaller team gets +2.

You can also earn points like this:

```
+5 for Ore mining
+3 for killing animals
+5 for killing mobs
+10 for killing cursed entities
+3 for taking damage
```

* Points are **per player**, not shared with the team.
* When you reach 100 points, type `/creepy` to trigger a paranormal event on the opposing team.
* Events occur randomly—you won’t know what happens!
* Time is fixed at 1000. Alternatively, you can fix your respawn point by right-clicking on the bed.
* OP can interrupt the game by entering the `/stopgame` command.

---

<details>
<summary>Types of Paranormal Events (Spoilers)</summary>

* Public Void appears, and when attacked, it kicks and disappears
* Binary444 appears, and when attacked, it teleports to another location and disappears
* That White appears, and when attacked, it scatters items
* A massive amount of lightning strikes
* A massive amount of text appears on the screen
* The floor collapses
* It moves on its own
* LagMob appears, and when attacked, FPS drops
* LongFix appears, and when attacked, all held items disappear
* LengthFlag appears, and when attacked, points become 0
* LongleggedAlex appears, and when attacked, the PC displays a fake BSOD and crashes
* LongleggedJeb appears, and when attacked, an annoying window that's hard to close appears
* Tikthink appears, and when attacked, it causes a massive explosion
* Suddenly explodes
* A bedrock cross appears
* Signs appear
* A mysterious program launches
* The disk drive opens on its own
* Push notifications appear
* Calculator, notepad, etc., open on their own
* GUI glitches, strange sounds play
* Become unable to move, massive chat messages appear
* A bedrock room appears, leading to TheWatcher...
* HeroVoid appears, and when attacked, a massive number of modal windows appear and it disappears
* The window shrinks and suddenly starts shaking
* Items get shuffled

</details>

---

If you have any questions or find bugs, please report them in the Issues section.

---

### Credits

#### Textures
- Test_Alpha
- Tei
#### Sound Effects
- On-jin https://on-jin.com/
- pixabay https://pixabay.com/
- freesound? https://freesound.org
#### Tools Used
- Intelij IDEA
- RetroMCP
- Gemini Nano Banana
- Perplexity
- Claude
