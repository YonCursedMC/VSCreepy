<img alt="GitHub Downloads (all releases)" src="https://img.shields.io/github/downloads/YonCursedMC/VSCreepy/total?style=for-the-badge">

---

# 🇯🇵

## VSCreepy

Creepyバトル — 最初にダイヤモンドを手に入れるのはどっちだ？！

---

## 概要

ダイヤモンドを最初に入手することを目指す、対戦型のMinecraftゲームです。
ただし普通のサバイバルでは終わりません。**怪奇現象による妨害**が発生します。

※ サーバー専用です
※ 通常のCreepy Minecraftとは別物です

---

## 注意事項

* これはMojang公式のものではありません（非公認）
* このバージョンによるトラブルについて、作者は責任を負いません
* 無断転載は禁止です（見つけた場合は対応します）
* MCPのライセンスにより、コードは非公開です
* 点滅・ホラー音・ドッキリ要素が多く含まれます
* 動作が重めです（高スペックPC推奨）
* クラッシュすることがあります（仕様です）
* Windows PC推奨（他環境では一部演出が動作しない可能性あり）
* 予期しない挙動が発生することがあります（自己責任でプレイしてください）
* 実況で使用する場合は、ダウンロードURLのクレジット表記をお願いします

---

## 起動方法

### クライアント

* MultiMC または PrismLauncher（推奨）を使用
* 以下からダウンロード
  [https://github.com/YonCursedMC/VSCreepy/releases](https://github.com/YonCursedMC/VSCreepy/releases)
  → 「VSCreepy.zip」を使用

### サーバー（管理者向け）

* 「VSCreepy_server.jar」をダウンロード
* 通常のMinecraftサーバーと同様に起動
* 勝利後はワールドリセット（再起動）が必要

---

## ゲーム開始コマンド

* クラシックモード
  `/startgame c` または `/startgame classic`

* タイムアタックモード（New）
  `/startgame`

* ゲーム中断
  `/stopgame`

---

## ゲームルール

### ■ Classicモード

チームの誰かが**ダイヤモンドをインベントリに入れた時点で勝利**。

---

### ■ Newモード（タイムアタック）

45分以内にどれだけダイヤモンドを集められるかを競います。

#### チーム

* ランダムで2チームに分かれる
* 1チーム：-X側 / 2チーム：+X側
* エリア外には進めない
* 地形が不公平な場合はワールド再生成推奨

#### ポイントシステム

* 2秒ごとに +1ポイント

* 行動によって加算：

  * 鉱石採掘 +5
  * 動物討伐 +3
  * モブ討伐 +5
  * 呪いエンティティ討伐 +10
  * ダメージを受ける +3

* ポイントは**個人単位（チーム共有なし）**

#### 特殊能力

* 100ポイントで `/creepy` を使用可能
* 相手チームにランダムな怪奇現象を発生させる

#### その他

* 時間は常に1000固定
* ベッド右クリックでリスポーン地点設定可能
* 人数差がある場合、少ないチームに+2補正

---

## 怪奇現象（一部）

※ネタバレ注意

* 雷が大量に落ちる
* 床が抜ける
* 強制移動
* 大爆発
* GUIバグ・異音
* アイテムシャッフル
* 特殊エンティティ出現（攻撃で様々な異常発生）
* PCへの影響っぽい演出（クラッシュ風など）

※何が起こるかはランダムです

---

## サポート

バグ報告・質問はIssueへお願いします。

---

## クレジット

**テクスチャ**

* Test_Alpha
* Tei

**効果音**

* 音人 [https://on-jin.com/](https://on-jin.com/)
* Pixabay [https://pixabay.com/](https://pixabay.com/)
* Freesound [https://freesound.org](https://freesound.org)

**使用ツール**

* IntelliJ IDEA
* RetroMCP
* Gemini Nano Banana
* Perplexity
* Claude

---

# 🇺🇸 English Version

## VSCreepy

Creepy Battle — Who will get the diamond first?!

---

## Overview

A competitive Minecraft game where the goal is simple:
**Be the first to obtain a diamond.**

But there’s a twist — **paranormal events will interfere with players.**

* Server-only
* Not a standard Creepy Minecraft version

---

## Disclaimer

* Not an official Mojang product
* The developer is not responsible for any damage or issues
* Redistribution is prohibited
* Source code is not 공개 (due to MCP license)
* Contains flashing, jump scares, and horror sounds
* Performance-heavy (high-spec PC recommended)
* Crashes may occur (intended behavior)
* Windows recommended (some effects may not work elsewhere)
* Unexpected behavior may occur — play at your own risk
* Please credit the download URL when using in videos/streams

---

## How to Launch

### Client

* Use MultiMC or PrismLauncher (recommended)
* Download from:
  [https://github.com/YonCursedMC/VSCreepy/releases](https://github.com/YonCursedMC/VSCreepy/releases)
  → Use `VSCreepy.zip`

### Server (Admin only)

* Download `VSCreepy_server.jar`
* Launch like a normal Minecraft server
* World reset (restart) is required after a match

---

## Commands

* Classic Mode
  `/startgame c` or `/startgame classic`

* New Mode (Time Attack)
  `/startgame`

* Stop Game
  `/stopgame`

---

## Game Modes

### ■ Classic Mode

First team to have a player **put a diamond in their inventory wins**.

---

### ■ New Mode (Time Attack)

Collect as many diamonds as possible within 45 minutes.

#### Teams

* Randomly split into 2 teams
* Team 1: -X side / Team 2: +X side
* Cannot cross boundaries
* If terrain is unfair, regenerate the world

#### Points

* +1 point every 2 seconds

* Additional points:

  * Mining ores +5
  * Killing animals +3
  * Killing mobs +5
  * Killing cursed entities +10
  * Taking damage +3

* Points are **individual (not shared)**

#### Ability

* At 100 points, use `/creepy`
* Triggers a random paranormal event on the enemy team

#### Other

* Time is fixed at 1000
* Right-click bed to set spawn point
* Smaller team gets +2 bonus

---

## Paranormal Events (Examples)

* Lightning storms
* Floor collapsing
* Forced movement
* Explosions
* GUI glitches & strange sounds
* Item shuffling
* Special entities causing unique effects
* Fake system crashes and weird behaviors

*Events are random.*

---

## Support

Report bugs or issues via GitHub Issues.

---

## Credits

**Textures**

* Test_Alpha
* Tei

**Sounds**

* On-Jin [https://on-jin.com/](https://on-jin.com/)
* Pixabay [https://pixabay.com/](https://pixabay.com/)
* Freesound [https://freesound.org](https://freesound.org)

**Tools**

* IntelliJ IDEA
* RetroMCP
* Gemini Nano Banana
* Perplexity
* Claude

---

Proofread with AI.
If the evaluation is bad, I will revert the text.
