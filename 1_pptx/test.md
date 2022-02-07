---
marp: true
theme: ryosan
header: ""
headingDivider: 2
paginate: true
footer: footer
---

# 
<!-- _class: titlepage -->
<!-- Title -->
RYOSAN<br>SAMPLE_format


# 目次<!-- omit in toc -->
<!-- _class: toc -->
- [スライドのタイトルを # で入力しています](#スライドのタイトルを--で入力しています)
  - [はじめに](##はじめに)
  - [Markdownによる特殊記載](#markdownによる特殊記載)
  - [リスト](#リスト)
  - [テーブル](#テーブル)
  - [画像](#画像)
  - [画像(背景)](#画像背景)
  - [画像(背景として右半分に貼り付け)](#画像背景として右半分に貼り付け)
  - [画像(左側に 20% のサイズ指定)](#画像左側に-20-のサイズ指定)
  - [穴埋めページ](#穴埋めページ)

## はじめに
ooo

# Detailed design report
<br>
<br>

| Item | Contents |
|:-----------:|:------------:|
| Specification No | ADS-20TM_ADX-SOFT_D-IMPACT_SWA-a-00-10-a |
| Date | 2021/01/19 |
| System ECU | 20TM |

# Signature
<br>
<br>

| Approver | Investigator | Creator |
|:-----------:|:------------:|:------------:|
| 嶋津 | 粟野 | 山口 |

<!-- 
PDFに変換時の改行コード
-->

## Change request summary
<br>
<br>

| No. | Request occurrence date | Contents | Reason for change |
|:-----------|:------------|:------------|:------------|
| SUM-1205 | 2021/09/06 | パイロンの検出による工事判定とレーンチェンジ制限の追加 | 仕様追加 |
| SUM-1206 | 2021/09/06 | サーバへの送信内容変更 | 不具合修正 |

## Change and impact on functional safety
<br>
<br>

| No. | Request occurrence date | Contents | Reason for change |
|:-----------|:------------|:------------|:------------|
| 1 | 2022/01/24 | レーンチェンジ制限の影響あり | レーンチェンジ制限の追加により、機能安全の監視を追加する必要がある為 |

## Change history
<!--
 _class: text1
-->
<br>

| Document | Contents | Date | Creator |
|:-----------|:------------|:------------|:------------|
| a00-00-a | 新規作成 | 2022/01/18 | 山口 |
| a00-01-a | 修正内容1を参照 | 2022/01/18 | 山口 |
| a00-02-a | 修正内容2を参照 | 2022/01/18 | 山口 |

   <修正内容1>
   1. 誤記修正
       1. Change historyの誤記修正
       1. Signatureの誤記修正
   1. 番号付きリスト2

<修正内容2>
1. 誤記修正
1. 番号付きリスト2

**<span style="font-size: 80%; color: red;">赤くて小さい太文字</span>** です
**<span style="font-size: 200%; margin-left:200px; color: red;">赤くて大きい太文字</span>** です

## Appendix 1
<br>
<br>

<!-- 
_class: text2 
-->

a|b|c
---|---|---



これは<span style="font-size: 200%; margin-left:00px; color: red;">赤文字</span>です  

**<span style="font-size: 200%; color: Blue;">赤くて大きい太文字</span>**


## Appendix 2
<!--
 _class: t1
-->
<br>
<br>

テーブル結合はマークダウンでは出来ない!その為、必要であれば以下の用にHTML記法を使用する。
<table class="t1">
  <thead>
  <tr>
    <th>ヘッダー1</th>
    <th>ヘッダー2</th>
    <th>ヘッダー3</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>hoge1</td>
    <td colspan="2" rowspan="2">hoge2</td>
  </tr>
  <tr>
    <td>fuga1</td>
  </tr>
  <tr>
    <td>piyo1</td>
    <td>piyo2</td>
    <td>piyo3</td>
  </tr>
  </tbody>
</table>

## Appendix 3
<br>
<br>

スタイルを変更したい場合もHTMLでテーブルのクラスを指定する。
<table class="t2">
  <tr>
    <th>都道府県</th>
    <th>面積</th>
    <th>人口</th>
    <th>人口密度</th>
  </tr>
  <tr>
    <td>愛知県</td>
    <td>5,172km2</td>
    <td>7,526,911人</td>
    <td>1,455人/km2</td>
  </tr>
  <tr>
    <td>東京都</td>
    <td>2,193km2</td>
    <td>13,742,906人</td>
    <td>6,263人/km2</td>
  </tr>
  <tr>
    <td>大阪府</td>
    <td>1,905km2</td>
    <td>8,831,642人</td>
    <td>4,635人/km2</td>
  </tr>
</table>
