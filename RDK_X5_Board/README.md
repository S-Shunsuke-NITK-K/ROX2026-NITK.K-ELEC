# RDK_X5_Board
RDK X5のGPIOを自分たちが使いやすいインターフェースに変換する基板

## 仕様

搭載したポート
| シルク文字 | 説明 | ポート数 |
|------|------|------|
| I2C | I2C通信用のポート　IMUとの通信に使用した。| 2 |
| SPI | SPI通信用のポート　実際には、MOSI端子だけを使ってLEDテープの制御をした。 | 1 |
| LPMD | モータドライバ制御信号出力ポート（Digital信号 x2 + PWM信号 x1） | 1 |
| Limit0 | 緊急停止スイッチ読み取りポート | 1 |
| FAN | 冷却FAN用のポート | 1 |
| LED0,LED1 | 元々はLEDテープの制御用に設けたが、その用途では使えなかった。実際には、PCUの制御に使用した。| 1 |
| ShutDown | トグルスイッチを接続し、RDK X5のシャットダウンのトリガーとして使用した。 | 1 |
| Game0,Game1 | トグルスイッチを接続し、各ゲームに対応したプログラムを実行できるようにした。 | 1 |

その他のインターフェース
| インターフェース | 個数 |
|------|------|
| ブザー | 1 |
| 電源表示LED | 2 |
| UserLED | 2 |

## 3Dモデル
<img width="640" height="545" alt="RDK_X5_3DF_ver ROX2026 2" src="https://github.com/user-attachments/assets/4e67d752-9d00-4476-98fa-8df0552e3ff7" />

<img width="836" height="412" alt="RDK_X5_3DB_ver ROX2026 2" src="https://github.com/user-attachments/assets/ab748068-af70-4d3f-a360-3395522db3a1" />

## 回路図
<img width="1179" height="826" alt="RDK_X5_ver ROX2026 2" src="https://github.com/user-attachments/assets/9c3f1151-3c42-4643-a662-07784acab6e6" />

## PCB
<img width="466" height="705" alt="RDK_X5_FB_ver ROX2026 2" src="https://github.com/user-attachments/assets/1c0501f7-03b0-4d48-9558-1ae12a53a1bb" />

<img width="466" height="705" alt="RDK_X5_F_ver ROX2026 2" src="https://github.com/user-attachments/assets/63dc0483-76c9-432c-aac8-f4d6127acbdb" />

<img width="466" height="705" alt="RDK_X5_BB_ver ROX2026 2" src="https://github.com/user-attachments/assets/17483608-6e16-40d2-8686-3d68211aa727" />

<img width="466" height="705" alt="RDK_X5_B_ver ROX2026 2" src="https://github.com/user-attachments/assets/e1e5d6b1-518a-4c9e-ae05-786522a56335" />

