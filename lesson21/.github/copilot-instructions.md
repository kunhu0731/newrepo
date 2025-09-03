# Copilot 專案指南

## 專案架構
此專案是一個 Python 學習專案，包含以下主要組件：
- `lesson21.ipynb`: Jupyter notebook 檔案，用於互動式學習
- `lesson21_2.py`: Python 腳本檔案
- `AGENTS.md`: 環境設定說明文件

## 開發環境設定
1. 專案使用 Conda 環境管理
2. 主要的 Conda 環境為 `data_repo_1`
3. 在執行任何 Python 檔案前，請先啟動 Conda 環境：
   ```bash
   conda activate data_repo_1
   ```

## 檔案執行方式
- Python 腳本執行：
  ```bash
  python lesson21_2.py
  ```
- Jupyter Notebook：
  使用 VS Code 的 Jupyter 擴充功能直接開啟並執行 `lesson21.ipynb`

## 注意事項
1. 確保使用正確的 Conda 環境
2. 在執行 Jupyter Notebook 時，kernel 應設定為 `data_repo_1` 環境

## 專案慣例
1. 檔案命名：使用小寫字母與底線分隔
2. Python 檔案應包含適當的註釋說明
3. 環境相關設定統一記錄在 `AGENTS.md` 中

若需更新此說明文件，請確保包含：
- 新增的環境依賴
- 新的執行命令或工作流程
- 重要的程式碼模式或慣例
