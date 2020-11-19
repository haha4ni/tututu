# 2D橫向卷軸遊戲開發
市面上有著許多開發2D遊戲的引擎，如RPG Maker、Gamemaker、Cocos2D與Unity，遊戲引擎整合了許多製作遊戲會用到的功能，使用者可以省去許多開發上的麻煩，快速開發出一款優秀的遊戲。但相信很多人對遊戲底層是如何處理深感興趣，本教學會一步一步詳細的說明，帶大家從無到有創造出一款遊戲。

此教學所使用語言為C++，作業系統是Windows。在開始之前，要先挑選出一個可以建立視窗與繪圖的函式庫，我們學習的重點不是底層的繪圖操作以及周邊設備的處理，因此挑選SDL(Simple DirectMedia Layer)來當框架，此函式庫處理了繪圖方面較複雜且枯燥的部分並提供簡單易懂的聲音、鍵盤、滑鼠、手把等函式支援，省去繁瑣動作之餘又有著最基本的支援，我們可以較專心且直觀的地來雕刻我們的遊戲。

# SDL簡介


# 導覽
| SDL | Game | Design Parttern |
| :---: | :---: |  :---: |
| [環境架設](https://github.com/haha4ni/tututu/blob/main/000%20-%20%E4%BA%8B%E5%89%8D%E6%BA%96%E5%82%99.md)|  |
| [建立視窗](https://github.com/haha4ni/tututu/blob/main/001%20-%20%E5%BB%BA%E7%AB%8B%E8%A6%96%E7%AA%97.md) | 引擎主核心 | 單例模式 |
| [事件處理](https://github.com/haha4ni/tututu/blob/main/002%20-%20%E8%99%95%E7%90%86%E4%BA%8B%E4%BB%B6.md) |  |
| 鍵盤輸入 4 |  |
| 表面與紋理 2 5 7 |  |
| 圖片載入(擴充函式庫) 6 | 切換場景 | 狀態模式 |
| 計時器 | 邏輯更新與幀率 |
| 精靈圖(Sprite) | 創造角色 |
| 碰撞方塊 |  |
| 瓦片(Tile) |  |
| 地圖編輯器 | 創造地圖 |
