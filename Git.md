# 查看 git 版本
git --version 

# 版本變更時記錄作者資訊
git config --global user.name {"輸入姓名"}  
git config --global user.email {"輸入信箱"} 

 # 將資料夾轉成具有版本功能的 git 儲存庫:建立.git資料夾儲存變更歷史
 git init

 # 清空終端機
 clear

 # 終端機狀態
git status

# 檔案從未追蹤改成已追蹤 {*.md}代表副檔名為md的所有資料 {.}代表所有修改
git add {檔案名稱}/{*.md}/{.}

# 檔案從未追蹤改成已追蹤（顯示 A 代表已接受拍照）
git add {輸入檔案名稱}/

# 檔案從未追蹤改成已追蹤（顯示 A 代表已接受拍照）
git commit -m {"輸入修改訊息"}

# 檔案從未追蹤改成已追蹤（顯示 A 代表已接受拍照）
git commit -m {"輸入修改訊息"}

# 日誌：列出先前修改的提交歷史
git log           # 要在按下 q 退出
git log --oneline # 簡化版

# 查看版本修改地方的比較
git diff {輸入日誌編號} -- {輸入檔案名稱}

# 將日誌編號的節點設為最新狀態並刪除後面修改的節點 注意：不可逆！！
git reset -- hard {輸入日誌編號}