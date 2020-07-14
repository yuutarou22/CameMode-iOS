# CameMode-iOS
CameModeのiOS版アプリです。

## 初期ファイルに関して
- AppDelegate.swift
  - アプリ全体のライフサイクルを管理するクラス。
- SceneDelegate.swift
  - iPadOSから画面分割し、同一アプリを同時に複数起動できるようになる機能に準じたもの。
  - 必須では無い。Info.plistで変更可能。
- ViewController.swift
  - Viewの管理者
  - 主な処理はここに記述する
- Launch.storyboard
  - スプラッシュのレイアウトファイル
- Main.storyboard
  - 起動時のレイアウトファイル
- Info.plist
  - 実行ファイル(ipa)のために必要な構成情報をまとめたファイル
