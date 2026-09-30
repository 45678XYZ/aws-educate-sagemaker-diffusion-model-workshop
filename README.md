</div>
<br>
<h1 align="center">卡牌鍊金術：用 Amazon SageMaker 召喚你的專屬角色！</h1>
<p align="center"></p>

<p align="center">
  <a aria-label="Notion page" href="https://aws-educate-tw.notion.site/Amazon-SageMaker-2ec6bfee6817809eb416d6f8bdf4b170?pvs=143">
    <img alt="Notion" src="https://img.shields.io/badge/Notion-View%20Page-brightgreen?style=social&logo=Notion&link=https%3A%2F%2Faws-educate-tw.notion.site%2FAI-SageMaker-AI-e5135d2fdc674a12bfdbbe30a95ca355">
  </a>
  </a>
</p>



### 專案簡介
本次工作坊將在 Amazon SageMaker Unified Studio 中 Fine-tune `Stable Diffusion 2.1` 模型，並結合 AWS Serverless 架構打造一個**互動式的卡牌生成網站**。使用者可以輸入帶有觸發詞的 Prompt，生成專屬風格的角色圖片並將其製作成卡牌。

實作內容分為兩個部分：

- 模型準備
  - 準備含有特定角色或物件的圖片作為訓練資料
  - 使用 Amazon SageMaker JumpStart 進行 Fine-tune
  - 部署模型至 Amazon SageMaker Endpoint 供推論使用
  - 透過 JupyterLab 進行測試

- 應用程式部署
  - 利用 AWS CloudFormation 部署所需的資源
  - 託管靜態網站於 Amazon S3
  - 串接 AWS 服務，完成卡牌生成網站

### 專案架構
![architecture](imgs/0131-aif-workshop-architecture.png)

### 成果展示
![architecture](imgs/0131-aif-workshop-demo.png)
