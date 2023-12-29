# docsify

## 手動でdocs以下を作成
```bash
tree docs/
docs/
├── README.md
└── index.html
```

## コンテナ起動
```bash
docker run --rm -itp 3000:3000 --name=docsify -v $(pwd)/docs:/docs docsify
```

