# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] — 2026-05-24

### Added
- 初版リリース
- 司令塔1 + オフェンス3 + ディフェンス3 の7部署構成
  - 🎯 秘書（しおり）
  - ⚔️ 物件開拓＆リサーチ（ハンター）
  - ⚔️ 融資（バンカー）
  - ⚔️ 戦略・参謀（軍師）
  - 🛡️ 賃貸管理（番頭）
  - 🛡️ 経理（帳簿番）
  - 🛡️ 法務（奉行）
- ルート `CLAUDE.md`（オーナープロフィール記入欄つき）
- `.claude/rules/departments.md` — 各部署の詳細・口調・判断軸
- `.claude/settings.json` — 推奨セキュリティルール
- サンプルデータ
  - `property/portfolio/sample-apartment.md`
  - `banking/banks/sample-shinkin.md`
  - `legal/contracts/sample-rental-contract.md`
- 各部署のテンプレート（`_template.md`）
- `.gitignore`（個人情報・OS固有ファイル除外）
