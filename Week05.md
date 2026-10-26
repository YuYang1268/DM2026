# Python 103
# Topic: THE MATRIX AWEKENING 資料矩陣的覺醒
## 📝 Challenge 1.1 (全 1 矩陣): 使用二維的 List Comprehension，產生一個 3x3 且全部填滿數字 1 的矩陣並印出。

<img width="635" height="211" alt="image" src="https://github.com/user-attachments/assets/16b8a925-8ab1-4b14-a0f2-b7e3945cade8" />

## 📝 Challenge 1.2 (狙擊右上角): 宣告一個 3x3 全為 0 的矩陣，將「右上角」的值修改為 99，並逐列印出。

<img width="695" height="256" alt="image" src="https://github.com/user-attachments/assets/e82bd40f-7d98-4a89-9e08-ddf8529abd2a" />

## 📝 Challenge 1.3 (面積總和): 給定矩陣 grid = [[1, 2], [3, 4]]，使用巢狀迴圈計算所有數字的總和 (1+2+3+4)。

<img width="990" height="277" alt="image" src="https://github.com/user-attachments/assets/e26cdb3d-2e05-45be-8746-3851c2603963" />

## 📝 Challenge 1.4 (尋找座標): 給定矩陣 grid = [[0, 0], [0, 5]]，寫程式用迴圈找出數字 5 的絕對座標 (r, c)。

<img width="1048" height="232" alt="image" src="https://github.com/user-attachments/assets/f13edfd1-1d2f-475a-9308-41c1aebdab11" />

## 📝 Challenge 1.5 (對角線繪圖): 建立一個 3x3 全為 0 的矩陣，利用迴圈與 if row == col:，將對角線上的 0 換成 8，並逐列印出。

<img width="1177" height="462" alt="image" src="https://github.com/user-attachments/assets/6f66f890-fb2c-41d5-b8a9-62ae5115e0c1" />

## 📝 Challenge 2.1 (客製化 5x5 地圖): 初始化一個 5x5 的 visible 矩陣，全塞滿 🟦。將四個角落修改為 🏝️，然後用 join() 印出。

<img width="1131" height="533" alt="image" src="https://github.com/user-attachments/assets/f85fc3e1-2f33-4243-9c61-2bc982d667bc" />

## 📝 Challenge 2.2 (十字瞄準線): 建立一個 5x5 的矩陣，預設全為 🔲。使用迴圈將第 2 列與第 2 行 (也就是正中間的十字) 替換為 🔴，並印出。

<img width="1237" height="486" alt="image" src="https://github.com/user-attachments/assets/0496d244-5da7-4ce0-8018-a48e2e483059" />

## 📝 Challenge 2.3 (真實與虛幻): 宣告 logic = [[0, "X"], ["X", 0]] 與 visible = [["🔲", "🔲"], ["🔲", "🔲"]]。寫一段程式，自動根據 logic 的值，如果發現是 "X" 就把 visible 對應座標改成 🚩，最後印出 visible。

<img width="1537" height="313" alt="image" src="https://github.com/user-attachments/assets/3f960f3a-39e4-47ed-9ebf-88f33cc371b8" />

## 📝 Challenge 2.4 (邊界巡邏): 建立一個 4x4 的全 0 矩陣。使用迴圈將矩陣的「最外圍邊界」(第 0 列、最後一列、第 0 行、最後一行) 全部改成 1，並逐列印出。

<img width="1337" height="462" alt="image" src="https://github.com/user-attachments/assets/6a3a60fe-b838-400e-9f4f-6f588e60ba57" />

## 📝 Challenge 2.5 (九宮格印鈔機): 定義中心座標 cx, cy = 1, 1。建立一個 3x3 的 🔲 矩陣。利用兩個迴圈 (dx 從 -1 到 1，dy 從 -1 到 1)，將 (cx+dx, cy+dy) 的位置全部塞入 💲，最後印出 (會是一個全滿的錢幣矩陣)。

<img width="1702" height="422" alt="image" src="https://github.com/user-attachments/assets/9abc1bee-c91c-4d3a-9321-63cb6bed23e6" />

# 自習心得:
##     自習完成Challenge 1的全部內容後, 已對矩陣的正確宣告方式, 矩陣內的內容置換, 巣狀迴圈對於矩陣的使用, 矩陣內的座標設立或定位有了深刻的了解。 而在完成Challenge 2的挑戰後, 對於矩陣的實際應用理解也有不小的幫助。 挑戰2中就是把挑戰1中的數字改成圖標字串, 並且將輸出渲染也潤色了不少, 看起來不會有雜亂的標點符號出現, 畫面也更簡潔。
