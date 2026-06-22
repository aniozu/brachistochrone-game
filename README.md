# 最速降下曲線ゲーム / Brachistochrone Curve Game

<img width="474" height="271" alt="image" src="https://github.com/user-attachments/assets/f1fc795f-f4ed-4cea-9027-8d8c0e3b4786" />

## 遊ぶ / Play

* 日本語版: https://aniozu.github.io/brachistochrone-game/
* English version: https://aniozu.github.io/brachistochrone-game/index_en.html

---

**最速降下曲線ゲーム**は、スタートとゴールを結ぶ曲線を自分で描き、重力のもとでどれだけ速く到達できるかを試すブラウザゲームです。

数学で知られる「最速降下曲線（brachistochrone curve）」をテーマにしています。最速の曲線はサイクロイドですが、このゲームではその答えをただ見るのではなく、自分で曲線を描いて近づけていくことを楽しめます。

---

## 概要

このゲームでは、画面上の `START` と `GOAL` を線で結びます。
描いた曲線に沿ってボールが動き、理論的なサイクロイド曲線とタイムを比較してスコアが表示されます。

モードは2種類あります。

* **NORMAL**
  1問ずつ自由に遊ぶモードです。GOALの位置を動かしながら、いろいろな配置で曲線を試せます。

* **RANKING**
  ランダムな5問に連続で挑戦し、合計スコアを競うモードです。結果をハイスコアランキングに登録できます。

---

## 遊び方

1. タイトル画面で `NORMAL` または `RANKING` を選びます。
2. `START` から `GOAL` まで、マウスまたは指で曲線を描きます。
3. 線を離すと、描いた曲線とサイクロイド曲線のボールが同時に動きます。
4. 到達時間に応じてスコアが表示されます。
5. RANKINGモードでは5問の合計スコアを競います。

高いスコアを出すには、まっすぐな線ではなく、最初に大きく下がってからゴールへ向かうような曲線を考えるのがコツです。

---

## スコアについて

各ステージのスコアは、理論的なサイクロイド曲線のタイムと、プレイヤーが描いた曲線のタイムを比較して計算されます。

サイクロイドに近いほど高得点になります。
RANKINGモードでは5ステージの合計点がランキングに登録されます。

---

## 注意

このゲームは **v0.1 beta** です。
表示や操作感、スコア計算、ランキング機能は今後変更される可能性があります。

このゲームの物理シミュレーションは、簡略化されたモデルに基づいています。
ボールは描かれた曲線に沿って運動するものとして扱っており、実際の物理で起こり得る「球がレールから離れる」「跳ねる」「摩擦や回転の影響を受ける」といった現象は考慮していません。

そのため、このゲームは厳密な物理シミュレーターではなく、最速降下曲線の性質を直感的に楽しむための教育的・ゲーム的なデモです。

ランキングはカジュアルな記録用です。
不正と思われる記録や明らかに異常な記録は、予告なく削除される場合があります。

ブラウザ、端末、画面サイズによって表示が多少異なることがあります。
スマートフォンでは横向きでのプレイをおすすめします。

---

## ライセンス

このプロジェクトは MIT License のもとで公開されています。
教育目的での利用・改変・再配布を歓迎します。

---

# Brachistochrone Curve Game

## Play

* Japanese version: https://aniozu.github.io/brachistochrone-game/
* English version: https://aniozu.github.io/brachistochrone-game/index_en.html

---

**Brachistochrone Curve Game** is a browser game where you draw a curve from a start point to a goal and see how fast a ball can travel along it under gravity.

The game is based on the famous mathematical problem of the **brachistochrone curve**. The fastest path is a cycloid, but instead of simply showing the answer, this game lets you draw your own curve and try to get close to it.

---

## Overview

In this game, you connect `START` and `GOAL` by drawing a curve.
A ball then moves along your curve, and its time is compared with the theoretical cycloid curve. Your score is based on how close your path is to the fastest one.

There are two modes.

* **NORMAL**
  A free-play mode where you can try one stage at a time. You can move the goal and experiment with different layouts.

* **RANKING**
  A score-attack mode with 5 random stages. Your total score can be submitted to the high-score ranking.

---

## How to Play

1. Choose `NORMAL` or `RANKING` on the title screen.
2. Draw a curve from `START` to `GOAL` using your mouse or finger.
3. Release to start the motion.
4. Your curve and the cycloid curve will be animated together.
5. A score is shown based on the travel time.
6. In RANKING mode, your total score over 5 stages can be submitted.

A useful hint: the fastest path is not usually a straight line.
Try drawing a curve that drops steeply at first and then rises toward the goal.

---

## Scoring

Each stage score is calculated by comparing the travel time of your curve with that of the theoretical cycloid curve.

The closer your curve is to the cycloid, the higher your score will be.
In RANKING mode, the total score from 5 stages is submitted to the ranking.

---

## Notes

This game is currently **v0.1 beta**.
The layout, controls, scoring system, and ranking feature may change in future versions.

The physics simulation in this game is based on a simplified model.
The ball is treated as if it always follows the drawn curve. Physical effects such as the ball leaving the rail, bouncing, friction, rolling motion, or rotational inertia are not taken into account.

Therefore, this game is not intended to be a fully accurate physics simulator. It is an educational and game-like demonstration for exploring the idea of the brachistochrone curve intuitively.

The ranking is intended for casual play.
Suspicious or clearly invalid scores may be removed without notice.

The display may vary depending on browser, device, and screen size.
On smartphones, landscape orientation is recommended.

---

## License

This project is licensed under the MIT License.
Educational use, modification, and redistribution are welcome.
