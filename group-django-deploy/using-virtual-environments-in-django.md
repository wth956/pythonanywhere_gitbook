# 設定環境與安裝套件

在這邊我們要安裝環境，如果不清楚虛擬環境**virtualenv** ，虛擬環境簡單來說，就是要保持自己的原本的系統乾淨，延續剛剛的終端機繼續作業，我們安裝可以參照下面步驟。

1. 首先，你要安裝你的虛擬環境的python版本\(自己的終端機python -V查看\)，python3.X是可以自己決定的，djangoalenv名字可以自己取。`mkvirtualenv --python=/usr/bin/python3.5 djangovenv`  
2. 


1.   ```text
   $ mkvirtualenv --python=/usr/bin/python3.5 mysite-virtualenv
   (mysite-virtualenv)$ pip install django
   # 或者你有requirements.txt:
   (mysite-virtualenv)$ pip install -r requirements.txt
   ```





