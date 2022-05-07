# week4_HW01

## 第四週：期中考：打造全端 (FULL STACK) 網站架構

### 建立環境

```
$ npm install express-generator -g
```

### 建立專案

#### 可以先用 `express -h` 來查詢

```
$ express --no-view myApp
```

#### 進入 myApp

```
$ cd myApp

$ npm install
```

#### 新增需要的資料夾：

**`connections`** - 資料庫連結  
**`controllers`** - 控制器  
**`Models`** - 模型  
**`servers`** - 訊息

#### 新增檔案

**`config.env`** - 連線資料  
**`example.env`** - 放連線資料的 key，value 則不放  
**`.gitignore`** - 不想上傳到 github 的資料夾或檔案可以設定在這裡

> exsample.env  
> 這個檔案是在交接給別人時要用的  
> 原本的 config.env 是自己用的不外露  
> 告訴別人原本的 env 檔裡面的結構有什麼?
