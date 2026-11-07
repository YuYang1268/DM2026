# Python 104
# Topic: 絕對不重複的集合論 (Proofs & Sets)

##  Challenge 1.1 (過濾器): 宣告 data = [9, 9, 1, 2, 2, 2, 5]，利用集合將它去重複後，再次轉換回 list 並印出。

<img width="645" height="202" alt="image" src="https://github.com/user-attachments/assets/24eee1c4-d821-4fc8-94d4-f241d63611f5" />

## Challenge 1.2 (雙修學生): 宣告 math_class = {"Alice", "Bob", "Charlie"} 與 cs_class = {"Bob", "David", "Alice"}。找出同時修兩門課的學生並印出。

<img width="602" height="206" alt="image" src="https://github.com/user-attachments/assets/284362f9-43c6-49d9-830e-c10063332ee7" />

## Challenge 1.3 (獨家菜單): 餐廳A有 {"Pizza", "Burger", "Pasta"}，餐廳B有 {"Pasta", "Steak", "Salad"}。用對稱差集 (Symmetric Difference) 找出不是兩家都有的獨家菜色。

<img width="556" height="186" alt="image" src="https://github.com/user-attachments/assets/7d9a8662-ff21-430e-b372-e6fe4e1b14d2" />

##  Challenge 1.4 (十面骰子): 使用 while 迴圈與 random.randint(1, 10)，持續丟骰子直到收集滿 5 個不重複的數字為止，印出結果。

<img width="523" height="283" alt="image" src="https://github.com/user-attachments/assets/610c1200-6d32-459b-86be-76aa8f4fdc7e" />

## Challenge 1.5 (找出奇數): 建立集合 nums = {1, 2, 3, 4, 5, 6}。寫一個 for 迴圈，如果數字是奇數 (用 % 2 判斷)，就把它加入到新的集合 odds 中，最後印出。

<img width="391" height="252" alt="image" src="https://github.com/user-attachments/assets/f293e8a5-d924-4a9b-8abc-10c1793288d8" />

##  Challenge 2.1 (隨機五連星): 使用 while 迴圈與 set，產生 5 個不重複的隨機座標 (範圍 0 到 4)，並印出這個集合。

<img width="647" height="306" alt="image" src="https://github.com/user-attachments/assets/c689a68a-93ed-454a-958a-27f5e980a0fb" />

## Challenge 2.2 (檢查腳下): 宣告 mines = {(1,1), (3,3)}。寫一個 if-else，判斷玩家踩下的座標 (2,2) 是否在 mines 集合中。如果在，印出「踩到地雷！」；不在，印出「安全！」。

<img width="450" height="232" alt="image" src="https://github.com/user-attachments/assets/1dc18d90-e06f-4dd0-8908-1df300911c67" />

##  Challenge 2.3 (小型佈雷器): 建立一個 3x3 的 logic 矩陣(全填 0)。建立一個集合 mines = {(0,0), (2,2)}。用迴圈將集合內的座標，在 logic 矩陣中對應的位置改成 "X"，並逐列印出。

<img width="621" height="347" alt="image" src="https://github.com/user-attachments/assets/6e0201cc-b72d-4322-8b63-222292ce4346" />

##  Challenge 2.4 (計算安全區): 一個 3x3 的盤面總共有 9 個格子(Universal Set)。如果你的 mines 集合裡有 4 顆地雷，寫程式算出並印出「安全格的數量」 (提示：利用減法 9 - len(mines))。

<img width="485" height="226" alt="image" src="https://github.com/user-attachments/assets/83974640-86fc-47c9-aec8-0d1e259bcca0" />

## Challenge 2.5 (視覺化防護網): 延續 2.3 題的 mines 集合，建立一個 3x3 的迴圈，如果當下座標 (r, c) 在 mines 裡，就印出 💣，否則印出 🔲。印出一個 3x3 的美麗九宮格。

<img width="587" height="372" alt="image" src="https://github.com/user-attachments/assets/ea28fa38-dd9c-410b-a947-db86f41a5331" />

# 自習心得:
## 完成本周的學習課程後, 我對集合有了一些概念, 集合擁有不可重複的元素特性, 如果在程式中對一個集合添加相同的元素, 該集合內也只會有一個同種元素。此外, 也了解了集合與集合和之間元素的關係, 比如聯集就是將兩個集合的元素總合起來, 而交集就是兩個集合所擁有的共同元素的稱呼等等。在實際應用上, 集合也是製作踩地雷遊戲不可或缺的一部分, 例如利用迴圈在設定好的座標範圍內產生隨機的地雷座標後將這些座標放到同一個集合內, 即利用了集合的不可重複性避免地雷產生在相同的位置, 也確保了玩家在遊戲內的體驗和公平性。

# 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。
## 我會用班級上的同學以及名單作為例子去講解集合, 比如班級內的同學都屬於A1班這個班級, 而A1正是一個集合, 在A1班內每一個學生都是不重複的。在集合內只有存在或不存在的概念, 並沒有重複存在的概念, 並且在集合內也是沒有固定順序概念的, 例如上課時教室在C304, 同學們陸續進入教室, 我們也不會在意誰先到誰後到。接著, 老師再依據名單進行點名, 有到班上的同學自然是點名正常上課, 而沒有到的同學則會被記曠課, 並不會有重複到或者重複被記曠課的情況, 有來上課就是有, 沒來上課就是曠課。
