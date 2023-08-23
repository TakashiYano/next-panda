<p align="left">
  <a href="https://panda-css.com/"><img src="./public/panda-css-icon.svg" height="50px;" /></a>
</p>

## Overview

- スタイリング
  - 複数のバリエーション
- RSC互換性
  - ビルド時に最新のCSSコードを生成
- デザイントークン
  - Design System の構築をサポート

## Impression

- CSS in JS として求められる機能は一通り揃っている印象
- Atomic CSS の恩恵を受けられるのは大きいメリット
- デザイントークンのサポートにより、Design System を構築する際に採用されるケースが多そう
- className に独自で付与する方法と JSX スタイルで記述する方法のどちらも利用できるので、チームの好みによって使い分けることができる
  - 元々使っていたフレームワークに応じて、体験が近い方を選択できる
- 型安全にするため、独自での記法になってしまう
  - できる限り純粋な CSS に近い形で書くのが好みな場合は適さず、CSS Modules などを利用したほうが望ましい