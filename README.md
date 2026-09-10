# ROX2026の熊本高専（熊本キャンパス）の回路構成

## 概要
広島のmolten [the Box]で行われたROX2026にロボコン部として参加した。

結果としては、九工大RoDEPとの決勝戦の末、13-14で熊本高専（熊本キャンパス）は準優勝という結果になった。

また、ロボットの装飾が評価されクリエイティビティ賞を受賞した。

本githubでは、大会参加時の回路構成について公開する。

大会HP： https://robotics-open-exchange.com/

## 大会に参加したロボット
<img width="4067" height="2711" alt="DSC02484" src="https://github.com/user-attachments/assets/8baef8eb-3832-4b23-b0ee-457e288e8da0" />

## 回路構成
<img width="2003" height="1494" alt="image" src="https://github.com/user-attachments/assets/ef0e206f-1513-4a07-8b8d-0a0d15552713" />

## 製作した基板

### RDK_X5_BoardR（マザーボード）
RDK X5のGPIO端子の配置を変換し、IMUやモータドライバなどの他の回路部品と接続しやすくする基板  
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/RDK_X5_Board  


  
### IMU_Board
IMU（BNO055）を搭載するだけの基板  
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/IMU_Board  
  
### PCU
緊急停止スイッチの信号に応じて電源の出力をON/OFFする基板  
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/PCU  
  
### DriveCANHUB
電源とCAN信号（XT30(2+2)）のHUB基板  
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/DriveCANHUB  
  
### PowerHUB
電源(XT60)のHUB基板   
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/PowerHUB  
  
### LPMD
低容量モータ向けのモータドライバ基板  
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/LPMD  

### NeoPixelsControlBoard
LEDテープに対して5V電源と信号を供給する基板  
詳細：https://github.com/S-Shunsuke-NITK-K/ROX2026-NITK.K-ELEC/tree/main/NeoPixelsControlBoard  
  
## 搭載したアクチュエータ

### 足回り
Edulight

### ドリブル機構&ボール取り込み機構


### ボール送り出し機構


### ボール投射機構
