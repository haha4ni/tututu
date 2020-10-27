# 2D橫向卷軸遊戲開發
市面上有著許多開發2D遊戲的引擎，如RPG Maker、Gamemaker、Cocos2D與Unity，遊戲引擎整合了許多製作遊戲會用到的功能，使用者可以省去許多開發上的麻煩，快速開發出一款優秀的遊戲。但相信很多人對遊戲底層是如何處理深感興趣，本教學會一步一步詳細的說明，帶大家從無到有創造出一款遊戲。

此教學所使用語言為C++，作業系統是Windows。在開始之前，要先挑選出一個可以建立視窗與繪圖的函式庫，我們學習的重點不是底層的繪圖操作以及周邊設備的處理，因此挑選SDL(Simple DirectMedia Layer)來當框架，此函式庫處理了繪圖方面較複雜且枯燥的部分並提供簡單易懂的聲音、鍵盤、滑鼠、手把等函式支援，省去繁瑣動作之餘又有著最基本的支援，我們可以較專心且直觀的地來雕刻我們的遊戲。

這篇是我廢話最多的一篇，之後的教學都會盡量用最少的話給各位懶人觀看


# 導覽
教學會分三個部分平行進行，分別為Design Parttern、SDL個別教學以及遊戲開發教學。搭配遊戲開發進度來給予SDL教學以及少量的Design Parttern。  
S系列：SDL教學  
G系列：遊戲開發  
D系列：Design Parttern  

| SDL | Game |
| :---: | :---: |
| 環境架設 1 |  |
| 建立視窗 1 |  |
| 事件處理 3 |  |
| 鍵盤輸入 4 |  |
| 表面與紋理 2 5 7 |  |
| 圖片載入(擴充函式庫) 6 |  |
