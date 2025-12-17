# KobitoKey_QWERTY

小人キー（KobitoKey）のZMKファームウェアリポジトリです。

## ブランチ構成と仕様

このプロジェクトは、**mainブランチ**と**developブランチ**の2つのブランチで管理されています。

### mainブランチ（安定版）

**用途**: 安定した動作が確認された最終版のファームウェア

**主な仕様**:
- ZMK v0.3ベース
- 左側トラックボール: 常時スクロール機能
- 右側トラックボール: 常時ポインティング機能
- 基本的なレイヤー構成（Layer 0-4）
- 安定性を重視した設定

**推奨用途**:
- 日常的な使用
- 安定した動作が必要な場合
- 本番環境での使用

### developブランチ（開発版）

**用途**: 新機能の開発とテスト用のファームウェア

**主な仕様**:
- ZMK mainブランチベース（最新機能）
- 左側トラックボール: 常時スクロール機能（左右のみ反転）
- 右側トラックボール: 
  - デフォルト: ポインティング機能
  - Layer 3時: スクロール機能（上下左右反転）
- 最新のZMK機能を活用した設定
- トラックボールの感度調整や角度調整が最適化済み

**推奨用途**:
- 新機能のテスト
- 最新機能の試用
- 開発・実験的な使用

**注意事項**:
- developブランチは開発中であるため、動作が不安定な場合があります
- 本番環境での使用は推奨しません

## レイヤー構成

Layer 0 QWERTY
<img width="1280" height="690" alt="Image" src="https://github.com/user-attachments/assets/ef0797b7-a63f-4632-912d-9b5d0115769f" />

Layer 1 NUMBER & ARROW
<img width="1280" height="690" alt="Image" src="https://github.com/user-attachments/assets/d6347b3c-a238-4278-bacd-e58195774d0e" />

Layer 2 Bluetooth & FUNCTION
<img width="1280" height="690" alt="Image" src="https://github.com/user-attachments/assets/f1f7cc93-fbd8-4a98-84ea-c8c36ad3952d" />

Layer 3 AUTO MOUSE
<img width="1280" height="690" alt="Image" src="https://github.com/user-attachments/assets/2efe5275-e460-41bc-ae45-0c0665435268" />
