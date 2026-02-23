<div align="center">

```
 ██╗██╗  ██╗██╗ ██████╗  █████╗ ███╗   ███╗██╗   ██████╗ ███████╗██╗   ██╗
 ██║██║ ██╔╝██║██╔════╝ ██╔══██╗████╗ ████║██║   ██╔══██╗██╔════╝██║   ██║
 ██║█████╔╝ ██║██║  ███╗███████║██╔████╔██║██║   ██║  ██║█████╗  ██║   ██║
 ██║██╔═██╗ ██║██║   ██║██╔══██║██║╚██╔╝██║██║   ██║  ██║██╔══╝  ╚██╗ ██╔╝
 ██║██║  ██╗██║╚██████╔╝██║  ██║██║ ╚═╝ ██║██║██╗██████╔╝███████╗ ╚████╔╝
 ╚═╝╚═╝  ╚═╝╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝╚═╝╚═════╝ ╚══════╝  ╚═══╝
```

# 🐮 ForgottenCow

<sub>ゲームとか、キャラクターとか、ロボットとか。作ってます。</sub>

<br>

<img src="https://img.shields.io/badge/STATUS-ONLINE-00ff41?style=flat-square&labelColor=0d1117"/>
&nbsp;
<img src="https://img.shields.io/badge/KEIO_SFC-Sociable_Robots_Lab-00d4ff?style=flat-square&labelColor=0d1117"/>

</div>

---

```bash
cow@sfc:~$ cat /etc/motd
```

> **忘れられた牛は、忘れられない"好き"を作りたい。**
> ただそれだけ。

ゲームとロボットの間にある「キャラクターが"そこにいる"感じ」を作りたくて、
絵・3D・UI・推論・実機まで、つながるところをつないでます。

[**Sociable Robots Lab**](https://sr.sfc.keio.ac.jp/www/en/) — 慶應SFC / ヒトと駆け引きをするモノたちの未来

---

```bash
cow@sfc:~$ cat /proc/loadout
```

<div align="center">

<img src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00ff41"/>
<img src="https://img.shields.io/badge/C%23-0d1117?style=for-the-badge&logo=csharp&logoColor=00ff41"/>
<img src="https://img.shields.io/badge/Unity-0d1117?style=for-the-badge&logo=unity&logoColor=00ff41"/>

<br>

<img src="https://img.shields.io/badge/Blender-0d1117?style=for-the-badge&logo=blender&logoColor=00d4ff"/>
<img src="https://img.shields.io/badge/Fusion_360-0d1117?style=for-the-badge&logo=autodesk&logoColor=00d4ff"/>
<img src="https://img.shields.io/badge/🎨_Clip_Studio_Paint-0d1117?style=for-the-badge"/>

<br>

<img src="https://img.shields.io/badge/After_Effects-0d1117?style=for-the-badge&logo=adobeaftereffects&logoColor=bf00ff"/>
<img src="https://img.shields.io/badge/Premiere_Pro-0d1117?style=for-the-badge&logo=adobepremierepro&logoColor=bf00ff"/>
<img src="https://img.shields.io/badge/Photoshop-0d1117?style=for-the-badge&logo=adobephotoshop&logoColor=bf00ff"/>

</div>

```
 ┌──────────────────────────────────────────────────────┐
 │  CODE    ███████████████████░░░░  Python / C#        │
 │  ENGINE  ██████████████████░░░░░  Unity              │
 │  3D      █████████████████░░░░░░  Blender / Fusion   │
 │  ART     ████████████████████░░░  Clip Studio Paint  │
 │  VIDEO   ███████████████░░░░░░░░  Adobe (AE/PR/PS)  │
 │  GRIT    ████████████████████████  測定不能          │
 └──────────────────────────────────────────────────────┘
```

---

```bash
cow@sfc:~$ ps aux --sort=-priority
```

### 🎮 CotoVerse &nbsp; <a href="https://apps.apple.com/jp/app/cotoverse/id6740241627"><img src="https://img.shields.io/badge/App_Store-DEPLOYED-00ff41?style=flat-square&logo=apple&logoColor=white&labelColor=0d1117"/></a>

3Dアニメキャラと会話できるアプリ。[**BlendAI**](https://apps.apple.com/jp/app/cotoverse/id6740241627) チームで開発。
UI/UXと機能企画を中心に触って、Unity Sentisでローカル推論も載せた。
端末の中にAIの脳を入れた。サーバーいらず。

### 🔥 IKIGAMI &nbsp; <img src="https://img.shields.io/badge/IN__DEV-bf00ff?style=flat-square&labelColor=0d1117"/>

"雰囲気"だけじゃなく、世界観をちゃんとルールにするRPGを作ってます。

<details>
<summary>&nbsp;いまの状況</summary>

```
[STATUS]  ██████████░░░░░░░░░░  鍛造中
[TODO]    ちゃんと形にする
```

</details>

### 🤖 ロボット &nbsp; <img src="https://img.shields.io/badge/ONGOING-00d4ff?style=flat-square&labelColor=0d1117"/>

ローカル推論 + センサー + 反応設計あたりを触ってる。
「賢い」より先に「ちゃんとそこにいる」が目標。

---

```bash
cow@sfc:~$ lspci | grep GPU
```

<div align="center">
  <img src="spark.png" width="600" alt="DGX Spark x2"/>
</div>

```yaml
Device:   NVIDIA DGX Spark ×2
Arch:     Grace Blackwell
Memory:   128GB Unified / unit
Purpose:  ロボットに脳を与える
Sticker: （そう、私はでびるコネクションファンです）
```

---

```bash
cow@sfc:~$ cat /var/log/blueprint.md
```

やりたいことの流れ。全部つながってる（つもり）。

```mermaid
flowchart LR
  A[キャラ / 好き] --> B[体験 / 触り心地]
  B --> C[脳 / ローカル推論]
  C --> D[認識 / 視覚・音声]
  D --> E[反応 / 振る舞い]
  E --> F[身体 / 表現]
  F --> G["存在感 / そこにいる"]
  C <--> H[計測 / latency・token/s・電力]
```

---

```bash
cow@sfc:~$ git log --oneline --graph
```

```
* ◇ 2030  かわいいロボットを社会に届ける
│
* ◇ 2027  小さくてもいいから、続く形にする
│
* ◇ 2026  プロトタイプを"人に見せられる形"にする
│
* ◇ 2025  IKIGAMIを形にする / ロボットの腕 / 描く  ← HEAD
│
* ◆ 2024  CotoVerse リリース / Sociable Robots Lab 加入
```

---

```bash
cow@sfc:~$ fortune
```

<div align="center">
<table>
  <tr>
    <td align="center">
      <sub><code>$ cat /dev/random_creature</code></sub><br>
      <img src="https://cataas.com/cat" width="220"/><br>
      <sub><code>[WARN] Expected cow. Got cat. Acceptable.</code></sub>
    </td>
  </tr>
</table>
</div>

---

<div align="center">

```bash
cow@sfc:~$ echo $PHILOSOPHY
```

**「便利」を届けて、気づいたら、なくてはならない存在になっている。**

<br>

[![Lab](https://img.shields.io/badge/◈_Sociable_Robots_Lab-00d4ff?style=flat-square&labelColor=0d1117)](https://sr.sfc.keio.ac.jp/www/en/)
&nbsp;&nbsp;
[![Mail](https://img.shields.io/badge/◈_cow@keio.jp-00ff41?style=flat-square&labelColor=0d1117)](mailto:cow@keio.jp)

```bash
cow@sfc:~$ exit
logout
Connection to forgottencow closed. 🐮
```

<br>

<sub>© モーモーホールディングス(株) / All moos reserved.</sub>

</div>
