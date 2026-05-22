# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] — 2026-05-24

### Added

- 7エージェント構成の仮想組織テンプレート初版リリース
  - 司令塔：秘書（しおり）
  - オフェンス3：ハンター（物件）/ バンカー（融資）/ 軍師（戦略）
  - ディフェンス3：番頭（管理）/ 帳簿番（経理）/ 奉行（法務）
- ZIP解凍即起動設計（絶対パスなし・外部APIキー不要）
- 各部署 CLAUDE.md（役割／口調／ルール／フォルダ構成／判断軸の4セクション統一）
- サンプルデータ同梱（架空物件・架空銀行プロファイル）
- `.claude/settings.json` 推奨 deny ルールプリセット
- `.gitignore` 個人情報ファイル除外設定
