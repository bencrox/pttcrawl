### 風向分析簡例

 - 在 pttbbs 找政治討論的風向，草劃一個簡單的爬文分析工具。
 - 不要太認真，這只是半天內示範東西可以怎做的。

## 功能區塊

 - 目標導入
 - 爬文
 - 緩存 (沒有做！)
 - 拆詞
 - 綜合分析

## 安裝執行

 - 安裝 nodejs , 參考 https://nodejs.org/
 - git clone https://github.com/bencrox/pttcrawl
 - npm install
 - ./pttcrawl politics 1
 - politics 是看板名， 1 代表只取 1 頁，不要太貪心啊！

## 結果
 - 印出來的是 json 

## 詞庫

 - 使用《結巴》中文分詞組件，參考 https://github.com/fxsjy/jieba
 - ./dict.txt 
 - 字詞 詞頻 分類