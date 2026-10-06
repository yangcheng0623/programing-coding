# AGENTS.md

- 所有回應一律使用繁體中文。
- 程式語言為 Python，一律用 conda 管理套件，環境名稱為 `iem_python`（已驗證：Python 3.12.13）。
- 執行 Python 前先確認環境：`conda run -n iem_python python --version`；conda 在本機不在 PATH，需用完整路徑 `C:\Users\user\anaconda3\Scripts\conda.exe` 或先 `conda activate iem_python`。
- 不要用 `pip`、`venv`、`.venv` 直接安裝；需要新套件時用 `conda install -n iem_python <pkg>`，並在回覆中註明套件名稱與用途。
- 專案現況為綠地：僅有 `README.md`（佔位符，不視為規格）與 Python 版 `.gitignore`，尚無原始碼、測試、CI。新增程式碼時同步更新本檔：實際的目錄結構、安裝／測試／lint 指令。
