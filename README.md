# conea-slide-template

## feature

### テキスト・画像ブロック

- テキストと画像を並べて表示できます。

```md
# 画像と文字を配置
<!-- _class: text-img -->

<div>
   <p>
      ここにテキストを入力します。<br>
      このテキストは左側に表示されます。<br>
      さらにテキストを追加することもできます。
   </p>
   <img src="./img/44qotpj40fgscindbycco5tlhcai.png" style="width: 400px;">
</div>
```

![](img/スクリーンショット%202023-11-22%2021.53.35.png)

### その他
- ページネーション自動付与
- katex埋め込み

## usage

### install

```sh
git clone https://github.com/conea0/slides.git
cd slides
npm i
```

### プレビュー

```sh
npm run dev
```

### ビルド

#### pdf

```sh
npm run pdf
```

#### pptx

```sh
npm run pptx
```

## License

MIT

## Author

Conea-Developers

