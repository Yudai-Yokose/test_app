## サービス名
### Fishingram

## サービス概要
- このアプリは、釣り人の釣果記録を支援することを目的としています。
- シンプルな機能と直感的な操作性で、手軽に釣果を記録していく事ができます。
- 自分だけの釣果記録を作り上げていく感覚を提供することで、釣行と記録のサイクルに繋げます。

## このサービスへの思い・作りたい理由
- 私自身、趣味としてルアーフィッシングに興じており、魚が釣れた際、その時の天候や潮位などを写真とともに細かく記録しています。
- 釣り人にとって、魚が釣れた時の状況を記録することは、経験値の蓄積や再現性といった観点から、非常に重要であるためです。
- 釣果の記録ができるサービスは数多く存在しますが、SNS機能やコミュニティ機能に特化しているものが多く、多機能である反面、
  単に記録をとりたい私の様なユーザーにとっては、若干オーバースペックなサービスとなっています。
- また、友人や現場の釣り人から「釣果の記録を紙でとっているから管理が大変」といった声や、「既存の釣果記録サービスは操作が複雑で、
  使い方が分からない」といった声を多く聞きました。
- 以上のことから、ニッチなジャンルではありますが、より手軽に、誰にでも使える、釣果記録サービスを作りたいと考え、本アプリを企画しました。

## 想定ユーザー層
- 現役世代の釣り人（30代〜60代）
- シニア世代の釣り人（60代〜）

## ユーザーの獲得
- 仕事や家庭の合間を縫って釣行に出かける現役世代のユーザーには、時間的制約がある場合が多いため、手軽な操作性で、キャッチアップを図ります。
  本世代のユーザーは他サービスとの併用も考えられることから、UIデザインや機能等、厳しい視点で見られる事を想定しています。
- シニア世代のユーザーはデジタルデバイスに苦手意識のあるユーザーが多いため、シンプルな機能と操作性で、キャッチアップを図ります。
- ユーザー登録をせずとも、他人の釣果記録は閲覧可能とします。ただし、釣果記録の登録等にはユーザー認証が必要という体系を取ることで、
  ユーザー登録へと促します。

## 主な特徴
- 釣果の記録機能<br>
記録機能までの入り口をできるだけ近くすることで、記録へのハードルを低下させます。
- 日記機能<br>
釣行を振り返る日記機能を設け、自分だけの記録を作り上げていく感覚を提供します。
- 緩やかなSNS機能<br>
他人の記録へのコメントやいいね機能を通して、ユーザー同士の交流に繋げます。
- シンプルな機能と操作性<br>
サービスを絞ることで、ユーザーフレンドリーなUIを提供し、継続利用に繋げます。

## 利用方法
- 釣行現場での利用を想定しているため、スマートフォンでの利用を主に想定しています。
- 基本的に家の外での利用となるため、手軽に入力できる UI を提供します。

## サービスの差別化ポイント・推しポイント
- 釣果の記録ができるサービスは数多くありますが、いずれもSNS機能やコミュニティ機能などに特化しています。
- そのため、釣果の記録を取ることに特化させることで、シンプルな機能と操作性を実現し、他サービスとの差別化を図ります。
- また、釣果の記録に加えて、振り返りができる日記機能がついているサービスは他になく、この点も差別化できるポイントと考えています。

## 機能候補（MVPリリース時）
- 釣果記録機能<br>
画像、潮汐（大潮、小潮等）、潮位（満潮、干潮等）、釣れたレンジ（表層、ボトム付近等）、魚のサイズ（20cm以下、20~30cm等）、位置情報（登録任意）を記録します。
- 位置情報機能<br>
魚が釣れた場所の位置情報を登録できる機能を実装します。Google Maps Platformを使用します。
- Googleアカウントでのユーザー認証機能<br>
現役世代キャッチアップのため、サインアップをより手軽にします。
- Xアカウントでのユーザー認証機能<br>
同上。どちらもシェアが高く、現役世代であればいずれか一つのアカウントを持っている事を想定しています。
- deviseでのユーザー認証機能<br>
シニア世代キャッチアップのため、スタンダードなサインアップも提供します。
- 日記機能<br>
日付、天候、釣果数、テキストを記録します。
- 他人の釣果へのコメント・いいね機能<br>
緩やかなSNS機能を設け、ユーザー同士の交流に繋げます。

## 機能候補（本リリース時）
- Xへの釣果シェア機能<br>
釣果をSNSでシェアしたいユーザー向けに実装予定です。

## 主な使用技術
|カテゴリー|使用技術| 
|:--|:--|
|サーバーサイド|Ruby 3.2.0 <br> Rails 7.1.3.4|
|データベース|MySQL|
|認証|Devise|
|描画関係|HTML <br> TailwindCSS <br> daisyUI <br> JavaScript <br> HotWire|
|デプロイ|heroc|
|開発環境|Docker|
|CI/CD|GitHub Actions|
|API|Maps JavaScript API|

## 画面遷移図


## ER図
