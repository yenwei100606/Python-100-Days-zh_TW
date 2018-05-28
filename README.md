## Python - 100天從新手到大師

### Python應用領域和就業形勢分析

簡單的說，Python是一個“優雅”、“明確”、“簡單”的程式語言。

 - 學習曲線低，適合非專業人士
 - 開源系統，擁有強大的生態圈
 - 解釋型語言，完美的平臺可移植性
 - 支援面向物件和函數語言程式設計
 - 可擴充套件性，能呼叫C/C++程式碼
 - 程式碼規範程度高，可讀性強

目前幾個比較流行的領域，Python都有用武之地。

 - 雲基礎設施 - Python / Java / Go
 - DevOps - Python / Shell / Ruby / Go
 - 網路爬蟲 - Python / PHP / C++
 - 資料分析挖掘 - Python / R / Scala / Matlab
 - 機器學習 - Python / R / Java / Lisp

作為一名Python開發者，主要的就業領域包括：

- Python伺服器後臺開發 / 遊戲伺服器開發 / 資料介面開發工程師
- Python自動化運維工程師
- Python資料分析 / 資料視覺化 / 科學計算 / 大資料工程師
- Python爬蟲工程師
- Python聊天機器人開發 / 影象識別和視覺演算法 / 深度學習工程師

下圖顯示了主要城市Python招聘需求量及薪資待遇排行榜（截止到2018年5月）。

![Python招聘需求及薪資待遇Top 10](./res/python-top-10.png)

![](./res/python-bj-salary.png)

![](./res/python-cd-salary.png)

給初學者的幾個建議（老司機的忠告）：

- Make English as your working language.
- Practice makes perfect.
- All experience comes from mistakes.
- Don't be one of the leeches.
- Either stand out or kicked out.

### Day01~15 - [Python語言基礎](./Day01-15)

#### Day01 - [初識Python](./Day01-15/Day01/初識Python.md)

- Python簡介 - Python的歷史 / Python的優缺點 / Python的應用領域
- 搭建程式設計環境 - Windows環境 / Linux環境 / MacOS環境
- 從終端執行Python程式 - DOS命令 / Hello, world / print函式 / 執行程式
- 使用IDLE - 互動式環境(REPL) / 編寫多行程式碼 / 執行程式 / 退出IDLE
- 註釋 - 註釋的作用 / 單行註釋 / 多行註釋

#### Day02 - [語言元素](./Day01-15/Day02/語言元素.md)

- 程式和進位制 - 指令和程式 / 馮諾依曼機 / 二進位制和十進位制 / 八進位制和十六進位制
- 變數和型別 - 變數的命名 / 變數的使用 / input函式 / 檢查變數型別 / 型別轉換
- 數字和字串 - 整數 / 浮點數 / 複數 / 字串 / 字串基本操作 / 字元編碼
- 運算子 - 數學運算子 / 賦值運算子 / 比較運算子 / 邏輯運算子 / 身份運算子 / 運算子的優先順序
- 應用案例 - 華氏溫度轉換成攝氏溫度 / 輸入圓的半徑計算周長和麵積 / 輸入年份判斷是否是閏年

#### Day03 - [分支結構](./Day01-15/Day03/分支結構.md)

- 分支結構的應用場景 - 條件 / 縮排 / 程式碼塊 / 流程圖
- if語句 - 簡單的if / if-else結構 / if-elif-else結構 / 巢狀的if
- 應用案例 - 使用者身份驗證 / 英制單位與公制單位互換 / 擲骰子決定做什麼 / 百分制成績轉等級制 / 分段函式求值 / 輸入三條邊的長度如果能構成三角形就計算周長和麵積

#### Day04 - [迴圈結構](./Day01-15/Day04/迴圈結構.md)

- 迴圈結構的應用場景 - 條件 / 縮排 / 程式碼塊 / 流程圖
- while迴圈 - 基本結構 / break語句 / continue語句
- for迴圈 - 基本結構 / range型別 / 迴圈中的分支結構 / 巢狀的迴圈 / 提前結束程式 
- 應用案例 - 1~100求和 / 判斷素數 / 猜數字遊戲 / 列印九九表 / 列印三角形圖案 / 猴子吃桃 / 百錢百雞

#### Day05 - [總結和練習](./Day01-15/Day05/練習.md)

- 基礎練習 - 水仙花數 / 完美數 / 五人分魚 / Fibonacci數列 / 迴文素數 
- 綜合練習 - Craps賭博遊戲

#### Day06 - [函式和模組的使用](./Day01-15/Day06/函式和模組的使用.md)

- 函式的作用 - 程式碼的壞味道 / 用函式封裝功能模組
- 定義函式 - def語句 / 函式名 / 引數列表 / return語句 / 呼叫自定義函式
- 呼叫函式 - Python內建函式 /  匯入模組和函式
- 函式的引數 - 預設引數 / 可變引數 / 關鍵字引數(\*) / 命名關鍵字引數(\*)
- 函式的返回值 - 沒有返回值  / 返回單個值 / 返回多個值(\*)
- 作用域問題 - 區域性作用域 / 巢狀作用域 / 全域性作用域 / 內建作用域 / 和作用域相關的關鍵字
- 用模組管理函式 - 模組的概念 / 用自定義模組管理函式 / 命名衝突的時候會怎樣（同一個模組和不同的模組）

#### Day07 - [字串和常用資料結構](./Day01-15/Day07/字串和常用資料結構.md)

- 字串的使用 - 計算長度 / 下標運算 / 切片 / 常用方法
- 列表基本用法 - 定義列表 / 用下表訪問元素 / 下標越界 / 新增元素 / 刪除元素 / 修改元素 / 切片 / 迴圈遍歷
- 列表常用操作 - 連線 / 複製(複製元素和複製陣列) / 長度 / 排序 / 倒轉 / 查詢
- 生成列表 - 使用range建立數字列表 / 生成表示式 / 生成器
- 元組的使用 - 定義元組 / 使用元組中的值 / 修改元組變數 / 元組和列表轉換
- 集合基本用法 - 集合和列表的區別 /  建立集合 / 新增元素 / 刪除元素 /  清空
- 集合常用操作 - 交集 / 並集 / 差集 / 對稱差 / 子集 / 超集
- 字典的基本用法 - 字典的特點 / 建立字典 / 新增元素 / 刪除元素 / 取值 / 清空
- 字典常用操作 - keys()方法 / values()方法 / items()方法 / setdefault()方法
- 基礎練習 - 跑馬燈效果 / 列表找最大元素 / 統計考試成績的平均分 / Fibonacci數列 / 楊輝三角
- 綜合案例 - 雙色球選號 / 井字棋

#### Day08 - [面向物件程式設計基礎](./Day01-15/Day08/面向物件程式設計基礎.md)

- 類和物件 - 什麼是類 / 什麼是物件 / 面向物件其他相關概念
- 定義類 - 基本結構 / 屬性和方法 / 構造器 / 析構器 / \_\_str\_\_方法
- 使用物件 - 建立物件 / 給物件發訊息
- 面向物件的四大支柱 - 抽象 / 封裝 / 繼承 / 多型
- 基礎練習 - 定義學生類 / 定義時鐘類 / 定義圖形類 / 定義汽車類

#### Day09 - [面向物件進階](./Day01-15/Day09/面向物件進階.md)

- 屬性 - 類屬性 / 例項屬性 / 屬性訪問器 / 屬性修改器 / 屬性刪除器 / 使用\_\_slots\_\_
- 類中的方法 - 例項方法 / 類方法 / 靜態方法
- 運算子過載 - \_\_add\_\_ / \_\_sub\_\_ / \_\_or\_\_ /\_\_getitem\_\_ / \_\_setitem\_\_ / \_\_len\_\_ / \_\_repr\_\_ / \_\_gt\_\_ / \_\_lt\_\_ / \_\_le\_\_ / \_\_ge\_\_ / \_\_eq\_\_ / \_\_ne\_\_ / \_\_contains\_\_ 
- 類(的物件)之間的關係 - 關聯 / 繼承 / 依賴
- 繼承和多型 - 什麼是繼承 / 繼承的語法 / 呼叫父類方法 / 方法重寫 / 型別判定 / 多重繼承 / 菱形繼承(鑽石繼承)和C3演算法
- 綜合案例 - 工資結算系統 / 圖書自動折扣系統 / 自定義分數類

#### Day10 - [圖形使用者介面和遊戲開發](./Day01-15/Day10/圖形使用者介面和遊戲開發.md)

#### Day11 - [檔案和異常](./Day01-15/Day11/檔案和異常.md)

- 讀檔案 - 讀取整個檔案 / 逐行讀取 / 檔案路徑
- 寫檔案 - 覆蓋寫入 / 追加寫入 / 文字檔案 / 二進位制檔案
- 異常處理 - 異常機制的重要性 / try-except程式碼塊 / else程式碼塊 / finally程式碼塊 / 內建異常型別 / 異常棧 / raise語句
- 資料持久化 - CSV檔案概述 / csv模組的應用 / JSON資料格式 / json模組的應用
- 綜合案例 - 歌詞解析

#### Day12 - [字串和正則表示式](./Day01-15/Day12/字串和正則表示式.md)

- 字串高階操作 - 轉義字元 \ 原始字串 \ 多行字串 \ in和 not in運算子 \ is開頭的方法 \ join和split方法 \ strip相關方法 \ pyperclip模組 \ 不變字串和可變字串 \ StringIO的使用
- 正則表示式入門 - 正則表示式的作用 \ 元字元 \ 轉義 \ 量詞 \ 分組 \ 零寬斷言 \貪婪匹配與惰性匹配懶惰 \ 使用re模組實現正則表示式操作（匹配、搜尋、替換、捕獲）
- 使用正則表示式 - re模組 \ compile函式 \ group和groups方法 \ match方法 \ search方法 \ findall和finditer方法 \ sub和subn方法 \ split方法
- 應用案例 - 使用正則表示式驗證輸入的字串

#### Day13 - [程序和執行緒](./Day01-15/Day13/程序和執行緒入門.md)

- 程序和執行緒的概念 - 什麼是程序 / 什麼是執行緒 / 多執行緒的應用場景
- 使用程序 - fork函式 / multiprocessing模組 / 程序池 / 程序間通訊
- 使用執行緒 - thread模組 / threading模組 / Thread類 / Lock類

#### Day14 - [網路程式設計入門](./Day01-15/Day14/網路程式設計入門.md)

- 計算機網路基礎 - 計算機網路發展史 / “TCP-IP”模型 / IP地址 / 埠 / 協議 / 其他相關概念
- 網路應用架構 - “客戶端-伺服器”架構 / “瀏覽器-伺服器”架構
- Python網路程式設計 - 套接字的概念 / socket模組 /  socket函式 / 建立TCP伺服器 / 建立TCP客戶端 / 建立UDP伺服器 / 建立UDP客戶端 / SocketServer模組

#### Day15 - [網路應用開發](./Day01-15/Day15/網路應用開發.md)

- 訪問網路API - 網路API概述 / 訪問URL / requests模組 / 解析JSON格式資料
- 檔案傳輸 - FTP協議 / ftplib模組 / 互動式FTP應用
- 電子郵件 - SMTP協議 / POP3協議 / IMAP協議 / smtplib模組 / poplib模組 / imaplib模組
- 簡訊服務 - twilio模組 / 國內的簡訊服務

### Day16~Day20 - [Python語言進階 ](./Day16-20)



### Day21~30 - [Web前端](./Day21-30)

- 用HTML標籤承載頁面內容
- 用CSS渲染頁面
- 用JavaScript處理互動式行為
- jQuery入門和提高
- Bootstrap在Web專案中的應用

### Day31~35 - [Linux作業系統](./Day31-35)

- 作業系統發展史和Linux概述
- Linux基礎命令
- Linux中的實用程式
- Linux的檔案系統
- Vim編輯器的應用
- 環境變數和Shell程式設計
- 軟體的安裝和服務的配置
- 網路訪問和管理
- 其他相關內容

### Day36~40 - [資料庫基礎和進階](./Day36-40)

- [關係型資料庫MySQL](./Day36-40/關係型資料庫MySQL.md)
  - 關係型資料庫概述
  - MySQL的安裝和使用
  - SQL的使用
    - DDL
    - DML
    - DQL
    - DCL
  - 在Python中操作MySQL
  - MySQL高階知識
- [非關係型資料庫Redis](./Day36-40/非關係型資料庫Redis.md)
  - Redis的安裝和基本配置
  - Redis的常用命令和資料型別
  - Redis的主從複製和哨兵模式
  - Redis高階操作和叢集
  - 在Python中操作Redis

### Day41~55 - [Django](./Day41-55)

#### Day41 - [Django實戰(01) - 快速上手](./Day41-55/Django2實戰01.md)

#### Day42 - [Django實戰(02) - 深入模型](./Day41-55/Django2實戰02.md)

#### Day43 - [Django實戰(03) - 檢視和模板](./Day41-55/Django2實戰03.md)

#### Day44 - [Django實戰(04) - 表單的應用](./Day41-55/Django2實戰04.md)

#### Day45 - [Django實戰(05) - Cookie和會話](./Day41-55/Django2實戰05.md)

#### Day46 - [Django實戰(06) - 日誌和快取](./Day41-55/Django2實戰06.md)

#### Day47 - [Django實戰(07) - 檔案上傳和通用檢視](./Day41-55/Django2實戰07.md)

#### Day48 - [Django實戰(08) - 使用者/角色/許可權和中介軟體](./Day41-55/Django2實戰08.md)

#### Day49 - [Django實戰(09) - RESTful架構和應用(上)](./Day41-55/Django2實戰09.md)

#### Day50 - [Django實戰(10) - RESTful架構和應用(下)](./Day41-55/Django2實戰10.md)

#### Day51-55 - [Django專案實戰](./Day41-55/Django2專案實戰.md)

- 專案開發流程和相關工具
- 生成非HTML內容
- 專案部署和測試
- 專案效能調優
- Web應用安全保護


### Day56~65 - [Flask](./Day56-65)

#### Day56 - [Flask安裝和入門](./Day56-65/Flash安裝和入門.md) 

#### Day57 - [模板的使用](./Day56-65/模板的使用.md) 

#### Day58 - [表單的處理](./Day56-65/表單的處理.md) 

#### Day59 - [資料庫操作](./Day56-65/資料庫操作.md)

#### Day60 - [使用Flask進行專案開發](./Day56-65/使用Flask進行專案開發.md)  

#### Day61-65 - [Flask專案實戰](./Day56-65/Flask專案實戰.md)

- 效能和測試
- 專案部署

### Day66~75 - [爬蟲](./Day66-75)

#### Day66 - [爬蟲簡介和相關工具](./Day66-75/爬蟲簡介和相關工具.md)

#### Day67 - [資料採集和解析](./Day66-75/資料採集和解析.md)

#### Day68 - [快取資料](./Day66-75/快取資料.md)

#### Day69 - [併發下載](./Day66-75/併發下載.md)

#### Day70 - [解析動態內容](./Day66-75/解析動態內容.md)

#### Day71 - [表單互動和驗證碼處理](./Day66-75/表單互動和驗證碼處理.md)

#### Day72 - [爬蟲中的陷阱](./Day66-75/爬蟲中的陷阱.md)

#### Day73 - [Scrapy的應用(1)](./Day66-75/Scrapy的應用1.md)

#### Day74 - [Scrapy的應用(2)](./Day66-75/Scrapy的應用2.md)

#### Day75 - [Scrapy的應用(3)](./Day66-75/Scrapy的應用3.md)

### Day76~90 - [資料處理和機器學習](./Day76-90)



### Day91~100 - [團隊專案開發](./Day91-100)



