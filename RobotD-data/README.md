# RobotD-data

請把 RobotD / RobotDEX 使用的 CSV 檔案放在這個固定資料夾。`RobotD.html` 與 `RobotDEX.html` 只會掃描 `RobotD-data`，並把找到的 `.csv` 檔案列在下拉選單中。

使用方式：

1. 將 CSV 檔案提交到此 `RobotD-data` 資料夾，子資料夾中的 CSV 也可被掃描。
2. 開啟 GitHub Pages：`https://moniemntim.github.io/Web/RobotD.html` 或 `https://moniemntim.github.io/Web/RobotDEX.html`。
3. 在下拉選單選擇 CSV；`RobotD.html` 可做分類分析，`RobotDEX.html` 可依日期範圍繪製數值圖表。

如果下拉選單沒有出現檔案，請確認 CSV 已提交到此資料夾，並等待 GitHub Pages 完成重新部署。
專案根目錄包含 `.nojekyll`，GitHub Pages 會以靜態檔案方式發布這些 HTML/CSV，不需要 Jekyll 建置。
