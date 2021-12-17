# Basic-Pandas

Pandas のexample リポジトリ。


## リポジトリ構成
```
.
├── Dockerfile
├── README.md
├── example
├── requirements.txt
└── src
```

## 環境詳細

- Python : 3.9.9


## 事前準備

- Docker インストール


## 環境構築

* Dockderfile があるホスト側のフォルダへ移動（例：Desktop/Basic-Pandas）
```
cd Desktop/Basic-Pandas
```

* Docker による環境構築（フォルダをマウント：Desktop/Basic-Pandas）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている


## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
