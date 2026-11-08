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

# 
