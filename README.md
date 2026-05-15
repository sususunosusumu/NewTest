# きょうのよていボード v2

## 変更点

- 絵カードのイラストを大きく表示
- カード一覧を `index.html` から分離
- `cards/cards.json` でカード名と画像ファイルを管理

## カードを追加する方法

### 1. cardsフォルダに画像を入れる

例：

```text
cards/hair_cut.png
```

### 2. cards/cards.json に追加する

```json
{
  "id": "hair_cut",
  "label": "かみをきる",
  "image": "hair_cut.png"
}
```

## 注意

- `id` は英数字とアンダーバー推奨
- `image` は cards フォルダ内のファイル名
- GitHub Pages上で動かす前提
- ローカルで `index.html` を直接開くと、ブラウザ制限で `cards.json` を読めない場合があります
