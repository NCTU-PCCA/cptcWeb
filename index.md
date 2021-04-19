## 最新資訊
+ 帳號更正：<font color='red'>郵件中的帳號 teamXXX 應改為 team2XXX，例：team001 應改為 team2001</font>
+ 比賽網頁：[https://nctu-pcca.github.io/cptcWeb/oj](https://nctu-pcca.github.io/cptcWeb/oj)
+ 計分板：[scoreboard.pdf](https://github.com/NCTU-PCCA/cptcData/blob/main/cptc001/scoreboard.pdf)

## 競賽資訊
1. **日期 Date** <br>
   2020 年 12 月 16 日 星期三
2. **地點 Place** <br>
   線上，網址：[https://nctu-pcca.github.io/cptcWeb/oj](https://nctu-pcca.github.io/cptcWeb/oj)
3. **競賽時間 Contest Time** <br>
   晚上六點至九點 (三小時)
4. **題組 Problem Set** <br>
   總題數五題，所有題目均為英文。
   賽後將提供中文題解資料。<br>
5. **報名 Registration** <br>
    報名網址：[https://forms.gle/511LXudLSd2HfVpy7](https://forms.gle/511LXudLSd2HfVpy7)
6. **報名期限 Registration Deadline**<br>
   2020 年 12 月 14 日 星期一

## 對象
+ **隊伍組成 Team Composition** <br>
  每隊由 1 至 3 名成員組成，每位成員至多參加一支隊伍。

## 規則
1. **不得使用機器可讀的資料 No machine-readable preparation**<br>
不得使用任何機器可讀的資料，如預先寫好存放於電腦中的程式碼。
但可以使用紙本資料，如教科書、字典、筆記以及列印好的紙本程式碼。
2. **僅與隊友接觸 Only contact teammates**<br>
在比賽過程中，參賽者只能與隊友討論。
競賽期間與教練或其他隊伍聯繫均屬違規行為。
3. **網路使用限制 Limited accesses**<br>
參賽者只能夠透過網路下載題目敘述、上傳解答程式碼、提問澄清疑點與查看計分板。
使用網路存取其他資訊均屬違規。
4. **限用一台電腦 One computer**<br>
每個隊伍僅可使用一台電腦撰寫程式與上傳程式碼。
於競賽期間除使用印表機列印題目與程式碼以及透過額外的螢幕閱讀題目之外，
不得使用任何其他電子裝置。
5. **禁止惡意行為 No malicious actions**<br>
不得做出任何意圖妨礙比賽進行及影響比賽公平性的惡意行為。

## 計分與排名
+ **計分與排名 Scoring & Ranking** <br>
競賽採標準 ICPC 賽制。
隊伍以解題數量多者排名較前，解題數量相同時，以總消耗時間少者排名較前。
答對的題目的消耗時間計算方式為比賽開始至解出題目所消耗的分鐘數。
如解出前有答錯，每答錯一次需要另加 20 分鐘。
總消耗時間為所有答對題目的消耗時間加總。未答對的題目不計消耗時間。

+ **平手判定 Tie-Breaker**<br>
解題數與消耗時間均相同時，以先答對最後一題者獲勝。

## 重要時程
+ **註冊截止日期：**<br>
2020 年 12 月 14 日<br>
+ **寄發隊伍帳號密碼：**<br>
2020 年 12 月 15 日寄發給參賽成員<br>

## 裁判系統環境

+ **Judge System**<br>
DOMjudge 7.3.0

+ **Hardware for Judgehost**<br>
Google Cloud Platform
1 vCPU
2GB RAM
20GB HDD

+ **OS**<br>
Linux 

+ **Distribution**<br>
Ubuntu 20.04

+ **Compilers / Interpreters**
    + C/C++: GNU Compiler Collections 9.3.0
    + Java: OpenJDK 11.0.8
    + Kotlin: 1.4.0 (on OpenJDK JRE 11.0.8)
    + Python 3: 3.8.2 (CPython)
    + Python 2: 2.7 (PyPy 7.3.1)

+ **Options for Compiler or Run-time Environment**
    + C++: `g++ -std=c++17 -x c++ -Wall -O2 -static -pipe`
    + C: `gcc -std=c18 -x c -Wall -O2 -static -pipe YOUR_SOURCE_CODE.c -lm`
    + Java (compile): `javac -encoding UTF-8` 
    + Java (run): `java -Dfile.encoding=UTF-8 -XX:+UseSerialGC`
    + Kotlin (compile): `kotlinc`
    + Kotlin (run): `kotlin -Dfile.encoding=UTF-8 -J-XX:+UseSerialG`

## 聯絡
- [cptc.contact@gmail.com](cptc.contact@gmail.com)
