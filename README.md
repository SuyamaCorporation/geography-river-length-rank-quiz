# 世界の川 長さ ランキング クイズ

2本の川を比べてどちらが長いかを当てる Higher or Lower 形式のクイズです。

## 機能

- 世界主要河川50本収録（ナイル・アマゾン・長江・ミシシッピ・黄河・コンゴ等）
- Higher or Lower 形式: 川Aの長さを表示し、川Bが長いか短いか選択
- 連続正解数（ストリーク）のカウント
- 最高ストリーク記録（localStorage）
- 正解後に流域と発源地の解説カード表示

## 技術仕様

- 静的SPA（単一 index.html）
- Tailwind CSS CDN
- XSS対策: textContent で表示（innerHTML への直接挿入なし）
- localStorage: 最高ストリークの保存に使用
