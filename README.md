# 機器學習

# 需求-功能(乒乓
## 外掛名稱：乒乓 AI

遊戲名稱：PAIA來一場乒乓球對戰
遊戲規則：左右控制板子移動，反彈球並讓對手接不到球則得分。
遊戲操作(外掛輸入)：控制板子動作，分為板子往左、板子往右以及不動。

外掛功能：
訓練：接收到狀態後，依照訓練中模型的權重選擇一輸入，並根據
　　　  此次輸入的反饋來更新訓練模型。
預測：根據當前遊戲狀態，自動根據模型選擇需要提供給遊戲需要
               的輸入。
<img width="366" height="876" alt="image" src="https://github.com/user-attachments/assets/bbf9e918-fb13-406e-bdf2-1117f1da98da" />

# 需求-功能(打磚塊
## 外掛名稱：自動打磚塊AI
遊戲名稱：PAIA一起打磚塊
遊戲規則：左右控制板子移動，反彈球並擊破所有磚塊為通關。
遊戲操作(外掛輸入)：控制板子動作，分為板子往左、板子往右
   、球發往左、球發往右以及不動。

外掛功能：
訓練：接收到狀態後，依照訓練中模型的權重選擇一輸入，並根據
　　　  此次輸入的反饋來更新訓練模型。
預測：根據當前遊戲狀態，自動根據模型選擇需要提供給遊戲需要
               的輸入。
<img width="348" height="861" alt="image" src="https://github.com/user-attachments/assets/17ac9b34-d0a4-448b-be16-c0ed33769397" />

# 需求-效能(乒乓
訓練目標 
1.接到每次對手打過來的球
2.嘗試讓對手無法接到打過去的球。

# 需求-介面(乒乓
1.外部介面:板子嘗試接反彈回來的球，試圖讓對手接不到球
2.內部介面
<img width="528" height="699" alt="image" src="https://github.com/user-attachments/assets/94de7ecd-9e94-44f3-8156-320e131992ee" />

# 需求-介面(打磚塊
1.外部介面:板子嘗試接反彈回來的球，試圖打掉所有磚塊
2.內部介面
<img width="538" height="717" alt="image" src="https://github.com/user-attachments/assets/d77e6476-88c9-4155-bebb-3125e4f83f16" />

# 需求-限制(乒乓
<img width="856" height="591" alt="image" src="https://github.com/user-attachments/assets/7a48623d-7d1a-4e9e-8ef1-090efb98590a" />

# 需求-限制(打磚塊
<img width="861" height="589" alt="image" src="https://github.com/user-attachments/assets/9bfee2f5-12a4-48f8-b1a2-699fb3c19fd9" />

# 需求-限制(乒乓&打磚塊
限制
語言:Python(AI訓練)

環境版本:
Python:3.10

模組版本:
PIAI
作業系統： 
Windows 10 專業版64位元

<img width="1200" height="599" alt="image" src="https://github.com/user-attachments/assets/153f3239-8898-4146-bbcc-d2af8af3baab" />


# 12/11報告
## 流程圖
<img width="1123" height="536" alt="image" src="https://github.com/user-attachments/assets/f519fafa-93f3-4d12-a0af-7dac52377ea4" />
<img width="986" height="582" alt="image" src="https://github.com/user-attachments/assets/7fc0294b-1a87-4c84-a7f8-feaa392d2c89" />

## API文件
<img width="1243" height="500" alt="image" src="https://github.com/user-attachments/assets/a6b16c75-3ceb-4ebe-a7f8-16e9455c837d" />
<img width="1247" height="581" alt="image" src="https://github.com/user-attachments/assets/c79f50ed-7532-421b-ab80-02763c3b1fdb" />
<img width="1223" height="465" alt="image" src="https://github.com/user-attachments/assets/0e241169-7426-4b38-b561-5e6ab9800e7d" />

## 訓練成果

<img width="1037" height="208" alt="image" src="https://github.com/user-attachments/assets/03035714-4ce3-46a1-ab63-691152307b0f" />

### 訓練5步
<img width="960" height="720" alt="loss_curve" src="https://github.com/user-attachments/assets/5a5106eb-11ea-494f-aee1-4210ba2bcae5" />

### 訓練50步
<img width="960" height="720" alt="loss_curve" src="https://github.com/user-attachments/assets/de2c65b4-087b-4364-b591-e3b751def78a" />

### 訓練100步
<img width="960" height="720" alt="loss_curve" src="https://github.com/user-attachments/assets/48e7b607-dd96-4761-9a77-01fec7f01fb1" />

### 訓練500步
<img width="960" height="720" alt="loss_curve" src="https://github.com/user-attachments/assets/106718f8-a5b9-4bf6-a8ff-4a50768ea51c" />

### 訓練6000步
<img width="960" height="720" alt="loss_curve" src="https://github.com/user-attachments/assets/2b97462c-7fbc-4337-9a9a-029176d4edcc" />
