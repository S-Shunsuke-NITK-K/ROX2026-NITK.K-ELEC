# IMU_Board

ロボットの姿勢をセンシングするためのIMU（BNO055）をロボットに搭載しやすくするための基板。  
使用したIMU：https://akizukidenshi.com/catalog/g/g116996/

### コンセプト
・秋月電子で販売されているIMU基板は取付穴がなく扱いにくいため、固定しやすいように改善

・マザーボード（RDK_X5_Board）にIMUを搭載する方法もあるが、可能な限りIMUはロボットの中心に設置したい。  
　┗ IMU（BNO055）は加速度センサ、ジャイロ、地磁気センサを融合して姿勢を計算している。  
　　 IMUの設置がロボットの中心から離れれば離れるほど遠心加速度や振動の影響を受けやすくなる（自説）  

## 3Dモデル
<img width="661" height="644" alt="IMU_3D_ver ROX2026 1" src="https://github.com/user-attachments/assets/af3bc795-efbd-4e43-b528-c3c3146f730c" />

## 回路図
<img width="1179" height="826" alt="IMU_ver ROX2026 1" src="https://github.com/user-attachments/assets/cf1621d5-e814-4680-9134-0187b48a1eec" />

## PCB
<img width="661" height="662" alt="IMU_FB_ver ROX2026 1" src="https://github.com/user-attachments/assets/9014601f-a989-44aa-8d6e-2d3d7eea83da" />

<img width="661" height="662" alt="IMU_F_ver ROX2026 1" src="https://github.com/user-attachments/assets/21850bc2-304a-4c30-b429-932f65ed0ceb" />

<img width="661" height="662" alt="IMU_BB_ver ROX2026 1" src="https://github.com/user-attachments/assets/3e70b31a-6f5e-4e47-bf0f-ecfefcf6373e" />

<img width="661" height="662" alt="IMU_B_ver ROX2026 1" src="https://github.com/user-attachments/assets/0c290431-c511-49dc-863e-aa4b62415060" />

