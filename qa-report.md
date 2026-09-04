# QAレポート（自動生成: scripts/qa_check.py）

- 対象: `output/`（1ページ: index.html）
- 結果: **ERROR 0 / WARN 0 / INFO 3**

## ERROR（必ず直す）
- なし

## WARN（確認して判断）
- なし

## INFO（参考）
- `index.html`: JSON-LD OK: ['GeneralContractor']
- `robots.txt`: 全ページが noindex。検索避けの成果物として扱い、全拒否と Sitemap 無しを正常とみなす
- `robots.txt`: User-agent: * を全面ブロック（意図どおり）

※ ブラウザ実測（PC1440/SP320・360・390、scrollWidth<=clientWidth、固定CTA実測高、デザイン忠実度、アニメーション）は site-qa Skill の手順で別途確認する。