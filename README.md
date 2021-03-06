# DLight - Inline evaluation plugin

English follows Japanese

## これは何？

![Sample](http://i.imgur.com/WhYTpAH.gif)

## インストール

"DLight.dproj"を開き、プロジェクトマネージャの"DLight.bpl"上で右クリックし、インストールを選択して下さい。

## 更新履歴

- Ver.0.0.7
  - ローカル変数名の重複でクラッシュするバグを修正
  - 型名の表示に関するバグを修正

- Ver.0.0.6
  - TObject型引数(Senderなど)の真の型名と値を表示するようにした

- Ver.0.0.5
  - 設定を環境設定に統合(thx @uschuster)
  - Starter版でもローカル変数を表示できるようにした

- Ver.0.0.4
  - ツールメニューに色設定を追加

- Ver.0.0.3
  - マルチバイト文字の横幅が適切に計算できないなかったのを修正

- Ver.0.0.2
  - 10 Seattleに対応
  - 10.1 Berlin Starter Editionに対応(監視式のみ)
  - 特定条件下でのデッドロックと特定プラットフォーム下のデバッガでしか動かない問題を修正

- Ver.0.0.1
  - 初回リリース

## 注意点

現状では拙作の16進数表示プラグイン（内のデバッガビジュアライザ）と相性が悪いです。
確認した範囲ではエラー等は出ていませんが、値の表示がおかしくなる場合があります。

## ライセンス

このプラグインは明示してある場合を除き、MITライセンスです。
詳しくはLICENSEファイルをお読み下さい。

このプラグインは[Delphi Detours Library](https://github.com/MahdiSafsafi/delphi-detours-library)を使用しています。
Delphi Detours LibraryはMozilla Public License Version 1.1で提供されています。

## Installation

1. Open "DLight.dproj"
2. Right click "DLight.bpl" on project manager
3. Choose "Install" menu

## History

- Ver.0.0.7
  - Fixed crashes on duplicate local variables (thx @loLiK-CZ)
  - Fixed type name bug

- Ver.0.0.6
  - Display real type name and value of TObject type parameters (e.g. Sender)

- Ver.0.0.5
  - Integrated the options into environment options (thx @uschuster)
  - Added local variable support for Starter edition

- Ver.0.0.4
  - Added color options to Tools menu

- Ver.0.0.3
  - Fixed wrong multibyte string width calculation

- Ver.0.0.2
  - Added support for 10 Seattle
  - Added Support for 10.1 Berlin Starter Edition (Only watch expressions)
  - Fixed some bugs

- Ver.0.0.1
  - First release

## License

This plugin is released under the MIT License, see LICENSE file.

[Delphi Detours Library](https://github.com/MahdiSafsafi/delphi-detours-library) is licensed under Mozilla Public License Version 1.1.

# Misc.
Delphinus-Support
