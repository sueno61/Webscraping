# ネイティブ環境（not docker）でwebscraping using python

## Python ライブラリ
- pandas, Pillow
- selenium
- requests, BeautifulSoup4

## ウェブスクレイピングのためのインストール（macOS）
- brew install chromedriver

### chromeのバージョンに合わせ`chromedriver`をインストールする
   
（ubuntuの場合）  
1. chromeのバージョン確認
2. ドライバーのインストール
- ダウンロード
```
$ cd /tmp/
$ curl -O https://chromedriver.storage.googleapis.com/99.0.4844.51/chromedriver_linux64.zip
```
- 解凍
```
$ unzip chromedriver_linux64.zip
$ ls -l
```
- 移動（インストール）
```
$ sudo mv chromedriver /usr/local/bin/
```
- 動作確認
```
$ which chromedriver
```
- あとかたづけ
```
$ rm chromedriver_linux64.zip
```