# CLAUDE.md — nice LP コーディング案件

## プロジェクト概要
Figmaデザインカンプの忠実な再現コーディング。  
1ページLP（Desktop + Mobile レスポンシブ）。  
**Figmaデザインに対する独自解釈・追加装飾は一切禁止。Figmaの数値を忠実に再現すること。**

## 技術スタック
- HTML5 / CSS3 / Vanilla JS（最小限）
- Google Fonts: Poppins (400, 600, 700, 800)
- レスポンシブ: Desktop(1440px基準) → Mobile(375px基準)
- ブレイクポイント: 768px

## ファイル構成
```
nice-lp/
├── index.html
├── css/
│   └── style.css
├── images/        ← 画像素材格納
└── CLAUDE.md
```

## 品質基準
- Figmaの色コード・フォントサイズ・余白を±2px以内で再現
- Desktop/Mobile両方でデザイン通りの表示を確認
- 画像はWebP変換不要（練習案件のため）
- セマンティックHTML必須（header/main/section/footer）
