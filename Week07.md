# Python 105
# Topic: 函數與八方關係 (Relations & Functions)

##  Challenge 1.1 (平方函數): 定義一個函數 square(x)，回傳 x 的平方。呼叫 square(6) 並印出結果。

<img width="383" height="157" alt="image" src="https://github.com/user-attachments/assets/b7ebfae5-e0db-4e08-a469-61a4b83d9a16" />

## Challenge 1.2 (偶數過濾器): 定義一個函數 is_even(n)，如果 n 是偶數回傳 True，否則 False。測試數字 7。

<img width="381" height="226" alt="image" src="https://github.com/user-attachments/assets/423fa1c4-fd99-4a4a-b134-623899dc3bad" />

## Challenge 1.3 (上限函數): 寫一個函數 clamp_top(val, limit)。如果 val 大於 limit 就回傳 limit，否則回傳 val。測試 clamp_top(15, 10)。

<img width="497" height="232" alt="image" src="https://github.com/user-attachments/assets/19add1ac-c411-4838-8aa5-c1b9e1bfaa08" />

## Challenge 1.4 (點的位移): 寫一個函數 move_point(x, y, dx, dy)，回傳加上偏移量後的新座標 tuple。測試 move_point(5, 5, -1, 1)。

<img width="592" height="158" alt="image" src="https://github.com/user-attachments/assets/e626a999-c434-4ad9-b1f6-d7740026597a" />

## Challenge 1.5 (絕對距離): 定義函數 distance(x1, x2)，回傳 abs(x1 - x2)。計算 2 與 9 的距離。

<img width="452" height="166" alt="image" src="https://github.com/user-attachments/assets/b5d4c919-e7b4-4862-9afe-e2066094b5e7" />

## Challenge 2.1 (單一邊界測試): 呼叫 is_valid_cell(0, 8) 與 is_valid_cell(9, 0) 並印出結果。

<img width="618" height="222" alt="image" src="https://github.com/user-attachments/assets/6a372d64-88e7-440a-b55b-244611db5a12" />
<img width="467" height="137" alt="image" src="https://github.com/user-attachments/assets/9a95775e-c6b3-4bb6-ba50-5c5caf8c7c16" />

## Challenge 2.2 (邊緣鄰居數): 呼叫 get_neighbors(0, 4) (位於最上方邊緣但不在角落)，印出它有幾個合法鄰居。

<img width="567" height="268" alt="image" src="https://github.com/user-attachments/assets/c5d04cd2-c904-41a5-b885-20fa0e7991c1" />
<img width="585" height="90" alt="image" src="https://github.com/user-attachments/assets/ae1e4cb2-351d-4796-b4ae-6e6e2a79b0d9" />

## Challenge 2.3 (掃描結果格式化): 取得 get_neighbors(8, 8) 的結果，使用 for 迴圈將每個 Tuple 一行一行地印出來。

<img width="567" height="268" alt="image" src="https://github.com/user-attachments/assets/c5d04cd2-c904-41a5-b885-20fa0e7991c1" />
<img width="702" height="237" alt="image" src="https://github.com/user-attachments/assets/a35afa7f-e5b4-4e8e-82c7-e92b5bfb7eac" />

## Challenge 2.4 (十字雷達修改): 複製 get_neighbors 的概念，但這次只檢查上下左右 (十字型)，不檢查斜角。測試 (4,4)。
## if dr != 0 and dc != 0: continue 表示不需要印斜對點
## if dr == 0 and dc == 0: continue 表示不需要印中間點
<img width="577" height="352" alt="image" src="https://github.com/user-attachments/assets/8b5f045f-5b02-4ca2-a124-4fd521de4ca8" />

## Challenge 2.5 (大範圍雷達): 複製 get_neighbors 的概念，將偏移量從 [-1, 0, 1] 擴大為 [-2, -1, 0, 1, 2] (5x5 範圍)。印出 (4,4) 會得到幾個合法鄰居。

<img width="683" height="322" alt="image" src="https://github.com/user-attachments/assets/5d934940-c378-471f-8893-ab2174931a54" />

# 自習心得:
## 完成本周課程後, 我對函數有了一定的了解, 函數在程式中就是一段寫好的代碼, 當我們需要這段代碼時, 只需將它呼叫出來, 而並不需要再寫一段相同的代碼, 並且也可以在函式內設定一個變數, 再根據變數去返回不同的結果. 使用函數不僅可以達成一些簡單的數學運算, 在重複運行或列印方面也是一個簡便的辦法, 無須重複寫相同的程式, 便能夠將變數輸入寫好的函數就能返回結果, 在觀感上也不會造成太冗長且重複性高的感覺. 接下來, 在踩地雷遊戲中, 一個格子的八方關係也是極其重要的, 如果在一個9X9的範圍格子內, 在靠邊的格子就不會有八個鄰居格子, 而是根據情況只會有3或5個鄰居格子, 當然在程式上要設定好範圍, 檢查邊界避免超出格子範圍導致產生bug.

# 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。
## 我會用販賣機的例子去講解函數, 販賣機就好比一個設定好的函數, 我可以根據投入的金額多少, 以及選擇的飲料, 去產生不同的結果. 投入的金額和選擇就好比我們所輸入的變數, 而販賣機內的飲料好比一個個結果, 我們只是將金額和選擇輸入, 而販賣機則會運作並給出對應的飲料. 八方關係直接用踩地雷遊戲講解, 假如隨即點選一個格子, 格子上出現3的數字, 表示在以你所點選的格子的範圍8個格子內有三個地雷, 5個安全格子, 這就是以你點選的格子為中心點的九宮格內, 它與其他八個格子之間的關係.
