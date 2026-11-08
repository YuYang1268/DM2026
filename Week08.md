# Python 106
# Topic: 排列組合與死亡機率 (Combinatorics & Probability)

## Challenge 1.1 (階乘計算): 使用 math.factorial 計算 6 的階乘並印出。

<img width="391" height="186" alt="image" src="https://github.com/user-attachments/assets/0be11ee3-555e-4118-9402-4e8a1e83c56d" />

## Challenge 1.2 (挑選炸彈): 盤面有 10 顆地雷，如果你要隨機選出 3 顆來解除，有多少種組合？用 math.comb 算出 $C(10, 3)$。

<img width="517" height="186" alt="image" src="https://github.com/user-attachments/assets/94bde1b0-632d-4598-914f-82be0273b8fc" />

## Challenge 1.3 (死亡機率): 盤面有 81 格，地雷 10 顆。印出「隨機點擊一格的死亡機率」，請用百分比表示並取小數點後一位。

<img width="565" height="136" alt="image" src="https://github.com/user-attachments/assets/3ce176b9-d06e-4243-8ef5-b3383c9fbe25" />

## Challenge 1.4 (二維計數): 給定矩陣 matrix = [[1, 0, 1], [0, 0, 0]]。寫一個迴圈，計算矩陣內總共有幾個 1。

<img width="510" height="232" alt="image" src="https://github.com/user-attachments/assets/3c1e37a2-d0b0-4433-bc06-8cb88dad6af7" />

## Challenge 1.5 (期望值算力): 某寶箱有 20% 機率獲得 100 元，80% 機率失去 10 元。算出並印出這個寶箱的期望值。

<img width="501" height="208" alt="image" src="https://github.com/user-attachments/assets/49597b3c-82e6-40b6-90e1-2b62a5538ad4" />

##  Challenge 2.1 (九宮格計數): 定義 logic = [["X", 0, "X"], [0, 0, 0], ["X", 0, "X"]]。直接透過索引查看 4 個角落，將所有 "X" 累加起來並印出總數。

<img width="612" height="445" alt="image" src="https://github.com/user-attachments/assets/908c1687-cb47-41ae-8568-33294ae705ee" />

## Challenge 2.2 (剩餘安全區機率): 盤面有 81 格，10 顆雷。你已經點開了 11 個安全的格子。請算出並印出「現在盲點一格的死亡機率 (百分比)」。

<img width="603" height="232" alt="image" src="https://github.com/user-attachments/assets/ab0d0cec-ba1e-415f-9edc-54fe979a5243" />

## Challenge 2.3 (鄰居檢查器): 假設某格子的 neighbors = [0, "X", "X", 0, 0] (為了簡化，直接給狀態串列)。寫迴圈算出裡面有幾個 "X"。

<img width="495" height="257" alt="image" src="https://github.com/user-attachments/assets/6ac47bba-fad0-43d8-9920-420fd5aa8d7b" />

## Challenge 2.4 (更新盤面): 宣告 board = [[0, 0], [0, "X"]]。使用巢狀迴圈走訪，如果發現 board[r][c] 是 0，就直接把它改成數字 1 (我們假裝已經算好了)，最後印出 board。

<img width="402" height="257" alt="image" src="https://github.com/user-attachments/assets/2f336c6e-cd17-41cc-85d4-078332ce5887" />

##  Challenge 2.5 (地雷密度評估): 撰寫一段程式，比較兩個格子的威脅度。A格周圍 8 個格子有 3 顆雷，B格周圍 5 個格子 (在邊緣) 有 2 顆雷。算出兩者的地雷密度 (百分比)，並印出哪一個比較危險。

<img width="792" height="417" alt="image" src="https://github.com/user-attachments/assets/3a124b7b-833f-4253-a877-c4df5c1560de" />

# 自習心得:
## 完成了本周的課程後, 我對排列, 組合和機率有了深入的了解. 排列的話, 例如說我班級上有10學生,需要讓四位學生排排坐, 並且在學生座位順序上也有要求, 這就成為排列. 而組合的話, 並不會在意順序先後, 運用上面的例子, 只要從10名學生中選出4名學生就行. 而概率家呢染指就是一件事情發生的可能性, 比如說從1到6隨機選一個數字, 這時候每一個數字被選中的概率就為6分之1. 如果從中隨機選兩個數字, 便是3分之1.

# 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。
## 我會傾向於用拍照這件事來講解排列, 比如三個人要拍照, 他們之間的站位順序會直接影響照片的結果, 誰在前誰在後, 都會導致照片的效果不同. 而在組合上, 假如我需要從三種水果種選擇兩種購買, 這時候我們只會看買了哪兩種水果, 不會在意到底先買了哪個, 後買了哪個. 概率的話, 比如一個箱子內有3顆紅球, 2顆白球, 這時候從箱子內隨即抓一顆球, 那抓到紅球的概率肯定是高於白球的, 因為紅球的數量就是比白球多.
