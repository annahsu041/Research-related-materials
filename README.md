# Research-related-materials
一、核心研究計畫
文件：台德AI研究計畫-VLA

研究主題： 觸覺視覺語言行動模型（VTLA/MVLA）三年期發展計畫

研究架構：

    第一年： 插銷組裝（Peg-in-Hole Assembly）
    
    建立多模態VLA基礎模型（視覺、觸覺/力覺、語言、材質）
    目標成功率：90%
  
  
    第二年： 多孔物件組裝
    
    混合專家機制與分層規劃策略
    目標成功率：80%，錯誤恢復時間<3秒
  
  
    第三年： 柔性扁平電纜（FFC）組裝
    
    偏好學習與Flow Matching技術
    材料損壞率<10%



預期成果： 精密製造效能提升30-40%，開源數據集與模型權重

二、技術論文
文件：MVLA

論文標題： MVLA: Toward Pre-Contact Material-Aware Force Regulating for Vision-Language-Action Models

https://github.com/user-attachments/assets/a7994f00-9f0b-40a3-a686-b21df597bfa7



核心創新：

    1. 接觸前材料分類與物理特性預測
    
    2. 主動式力調節（vs. 傳統被動反應）
    
    3. 材料感知數據庫（EMPD）整合
    
    4.體積估算與形狀因子學習

實驗成果：

    材料分類準確率：85%
    平均損壞率：10.4%（優於OpenVLA的20.4%）
    易碎物體處理成功率：75%
    
    技術平台： PyBullet、MuJoCo、Isaac Sim


https://github.com/user-attachments/assets/b5b583a9-1770-4eae-846f-63167102ff5f


三、專題研究報告
3.1 MVLA系統開發
文件：碩士_專題報告摘要_MVLA

研究期間： 2024年9月至今

指導教授： 王傑智

研究性質： 獨立完成

主要貢獻：

    1.設計VLA模型嵌入架構
    2.建立模態感知融合機制（視覺、語言、材質辨識）
    3.整合開源VLA模型建構可微調訓練框架
    4. 規劃並模擬多元場景任務實驗（Nvidia Isaac Lab、PyBullet）

後續發展： 已投稿ICRA 2026，計畫投稿IROS 2026

3.2 電漿清洗與視覺辨識
文件：碩士_專題報告摘要_電漿清洗

研究期間： 2023年9月至2024年6月

指導教授： 蔡佳宏

專題成績： A+

研究內容：

    1.氬氣電漿於精密鋼珠清潔應用（3kV、15W、20 slm、5分鐘）
    2.導入EfficientAD建立髒污辨識系統
    3.綠色製程與環保效益評估

技術整合：

    電漿物理與表面處理
    深度學習異常偵測（EfficientAD）
    製程優化與品質控管


研究特色

跨域整合能力： 結合機械工程、電機控制、人工智慧與製程優化

完整研發鏈： 從基礎實驗到系統整合，再到實際應用驗證

創新技術突破： 實現接觸前材料感知，突破傳統VLA模型限制

實務應用導向： 聚焦精密製造與工業自動化實際需求
