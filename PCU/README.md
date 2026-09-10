# PCU
緊急停止スイッチの状態に応じて電源出力をON/OFFする基板（PCU：Power Control Unit）

### 入力
バッテリー電源（XT60 オス）

電源スイッチ（XH2ピン　オス）

緊急停止スイッチ（XH2ピン　オス）

緊急停止信号（XH2ピン　オス）

### 出力  
バッテリー電源（XT60 メス）

### コンセプト
・Fuseを搭載

・電源スイッチと緊急停止スイッチが押されるとリレーの励磁が停止し、電源出力がOFFになる。

・RDK X5から出力される緊急停止信号の状態に応じてリレーの励磁が停止し、電源出力がOFFになる。

・瞬間的な電流不足を補う大容量コンデンサ（10000μf）を搭載&放電回路を搭載

## 3Dモデル
<img width="909" height="693" alt="PCU_3D1_ver ROX2026 2" src="https://github.com/user-attachments/assets/6ca0a5bd-6b39-4849-beec-9b07a6da8773" />

<img width="960" height="604" alt="PCU_3D2_ver ROX2026 2" src="https://github.com/user-attachments/assets/2f46ea9a-df47-47cc-af26-2e8b9d7777d1" />

## 回路図
<img width="1179" height="826" alt="PCU_ver ROX2026 2" src="https://github.com/user-attachments/assets/9ecd9c5c-5f9a-45ae-b5d6-ae385a092c21" />

## PCB
<img width="792" height="535" alt="PCU_FB_ver ROX2026 2" src="https://github.com/user-attachments/assets/fc91f48c-3c00-4310-b8da-39ea36b7b7d6" />

<img width="792" height="535" alt="PCU_F_ver ROX2026 2" src="https://github.com/user-attachments/assets/e64c266b-2d7e-425d-aca5-74a02ee13a23" />

<img width="792" height="535" alt="PCU_BB_ver ROX2026 2" src="https://github.com/user-attachments/assets/8eda0a58-416a-4261-91ac-3d89f4e5240a" />

<img width="792" height="535" alt="PCU_B_ver ROX2026 2" src="https://github.com/user-attachments/assets/2f7c1f35-5650-484a-b5b3-ebb2cfcbe956" />
