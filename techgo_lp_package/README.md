# TechGO LP 制作指示書パッケージ

Claude Code / Codex に渡す想定のファイル一式です。

## ファイル構成
- `claude_code_instruction.md`：実装指示書（最重要）
- `lp_copy.md`：LP本文ドラフト
- `evidence_and_sources.md`：出典・根拠メモ
- `figures_spec.md`：図表仕様
- `assets/*.svg`：LP内にそのまま置けるSVG図表

## 推奨の使い方
1. `claude_code_instruction.md` を Claude Code に貼る
2. 既存LPのディレクトリ構成に合わせて実装させる
3. SVGは `/public/images/techgo/` などに配置
4. CTAリンクは ASP のテックGOアフィリエイトリンクに差し替え
5. 出典URLは最終表示時にリンクまたは脚注として掲載
