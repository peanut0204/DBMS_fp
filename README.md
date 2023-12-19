# Good Book Sharing Web App

> frontend: React, Tailwind

> backend: Flask, Python

## Project Overview
『好書sharing』是一個致力於提升閱讀體驗的線上平台。它不同於其他書籍推薦，充滿華麗外表卻空洞內容的情況。在這裡，我們讓熱愛閱讀的每位用戶能夠與其他書迷分享心得、評價書籍，確保每一個意見都來自真實閱讀感受。不僅可以給書籍評分，還能寫下詳盡的書評。即使找不到心儀的書籍，也能夠向平台推薦。更棒的是，使用者可以透過追蹤品味相似的書迷，擴大找到優質書籍的機會。總之，『好書sharing』為熱愛閱讀的人們提供了一個真實、實用的書籍推薦平台。

## To set up database
Create ```db_password.txt``` and write your password in the file.

Change database name in ```app.py```
```
dbname = <your database name>
```

## To start the Website



### Go to frontend

```
cd frontend
```
install dependencies
```
npm i
```
start the application

```
npm start
```

the website runs on http://localhost:3000/

---

### Go to backend

```
cd backend
```
create venv

```
py -m venv venv   # for Windows
python3 -m venv venv   # for macOS
```

activate venv

```
.\venv\Scripts\activate.ps1   # for Windows
source venv/bin/activate   # for macOS
```
install requirements

```
pip install -r requirements.txt
```

run flask

```
python app.py
```

and the server would runs on port http://127.0.0.1:5000/

<i>The CORS policy is dealt by using vite proxy</i>

## Example
進入「好書 Sharing」平台時，一開始是登入畫面。
![Login Page](./screenshot/1_login.png)
按下註冊按鈕，在註冊畫面進行註冊。
![Register Page](./screenshot/2_register.png)
接下來登入後會自動導向至 My Page，即可開始探索「好書 Sharing」平台。
![My Page](./screenshot/3_myPage.png)
以「搜尋書籍」的功能為例，可以在上方的選單列進入 Search Book 畫面，開始找書。
![Search Book Page](./screenshot/4_searchBook.png)
