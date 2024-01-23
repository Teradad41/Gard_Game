# Blackjack

## 🌱 概要
MVC に従って開発したトランプゲームのブラックジャック

## 🏠 URL
https://develop--gorgeous-custard-38daf5.netlify.app

## ✨ デモ
https://github.com/Teradad41/blackjack/assets/107381511/0318b3e3-ebcf-4ee1-9fa5-51d212b8be6a

## 📝 説明
ルールは標準的なブラックジャックのルールに従います。

ゲームでは、各プレイヤーはハウスと 1 対 1 で勝負します。

プレイヤーには以下の選択肢があります。

- Surrender：最初に配られた 2 枚のカードで負けを認めることができます。賭けた金額の半分が返ってきます。最初の 2 枚のカードが配られた後にしか行えません。

- Stand：カードの追加をやめて、現在の手札で勝負します。

- Hit：手札に 1 枚のカードを追加します。合計点数が 21 を超えてしまうとバスト（bust）となり、プレイヤーの負けとなります。
  
- Double：ベット額を 2 倍にして、もう 1 枚だけカードを引くことができます。最初の 2 枚のカードが配られた後にしか行えません。

最終的に、プレイヤーの手札とハウスの手札を比較し、21 を超えずにより 21 に近いスコアを持つ方を勝ちとします。

通常の勝利の場合、返金額は掛け金の 2 倍です。
ブラックジャックの場合、返金額は掛け金の 2.5 倍です。

## 💾 使用技術
<table>
<tr>
  <th>カテゴリ</th>
  <th>技術スタック</th>
</tr>
<tr>
  <td rowspan=5>フロントエンド</td>
  <td>HTML</td>
</tr>
<tr>
  <td>CSS</td>
</tr>
<tr>
  <td>フレームワーク : TailWind CSS</td>
</tr>
<tr>
  <td>TypeScript</td>
</tr>
<tr>
  <td>JavaScript</td>
</tr>
<td rowspan=4>その他</td>
  <td>ソースコード管理：Git, GitHub</td>
</tr>
<tr>
  <td>パッケージ管理：npm</td>
</tr>
<tr>
  <td>モジュールバンドラー：webpack</td>
</tr>
<tr>
  <td>コードフォーマッター：Prettier</td>
</tr>
</table>

## 📜 作成の経緯
- 拡張やリファクタリングが容易な、ソフトウェア設計のモデルである MVC を理解する
- 開発者としてステップアップするために JavaScript から TypeScript に移行しプロジェクトを完成させる
- OOP コースで学習した内容をもとに、トランプゲームのモデリングを行う
- フロントエンドのデザイン力の向上

## 💻 学んだこと
- MVC モデルの構成とそれぞれが果たす役割
- OOP (クラス、カプセル化）
- webpack や npm scripts などの環境構築
- TailWind CSS でのスタイリング

## ⭐️ こだわった点
- model の部分はブラックジャック用ではあるが、各メソッドを簡潔に記述した
- await を使った非同期処理を用いてゲームの流れをリアルに再現した
- view の部分で DOM を宣言的に操作することでリファクタリングしやすい状態にした
- TailWind CSS を用いてカジノを意識したデザイン・ UI を再現した

2024.1.18 <br/>
このプロジェクトを行ったのは 7 ヶ月前で、当時は OOP を学習して得た知識を使い MVC モデルのアプリを完成させました。

しかし、今コードを見返してみると MVC それぞれの責任の分離が曖昧で、拡張性もあまりないように感じました。

この原因として、以下の２つの理由が挙げられると思います。
1. MVC モデルでの開発が初めてだったので、理解したことの実践が難しかった
2. ブラックジャックを完成させようとして、抽象的にトランプゲームを捉えてモデリングを行わなかった

今は、もう一度複数のトランプゲームをプレイできるアプリを制作しています。

そのプロジェクトでは、ここで得た経験をもとに複数のゲームに対応できるようにモデリングを行い、以前より拡張・リファクタリングがしやすいような設計ができていると思います。
→ https://github.com/Recursion-group-A/card-game

## 📮 今後実装したいこと
- [ ] リファクタリング
- [ ] 他のゲームの追加
      
## 📑 参考
- [TailWind CSS](https://tailwindcss.com)
- [webpack](https://webpack.js.org)
