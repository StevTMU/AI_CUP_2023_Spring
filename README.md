# AI_CUP_2023_Spring

「TEAM_3693_MLP_FinalUpdate」是我們最後交出的檔案，其餘「TEAM_3693_CNN」、「TEAM_3693_MLP+CNN」均為比較模型，用以比較三者模型效能之差異。

# Usage: 
1. 使用前請先點以下連結，並加入自己雲端硬碟的捷徑
https://drive.google.com/drive/folders/1q7hLdK0AqJyM2mBwwlmTk1j2eaZPV1i9?usp=share_link

2. 更改在『~ 環境準備』的程式碼：
『
my_working_root = "/content/gdrive/Shareddrives/1112_AI智慧醫療三日工作坊/第04大組_Pony小馬車/code"
os.chdir(my_working_root)
』

將working root路徑改為自己的的雲端硬碟內，並仿照上方格式

3. 更改在『資料處理』的程式碼：
『
##讀取資料表
df = pd.read_csv("/content/gdrive/Shareddrives/1112_AI智慧醫療三日工作坊/教材/Training Dataset/training datalist.csv")
df
』
將csv路徑改為 https://drive.google.com/drive/folders/1_qXKLqQq7YPtXvARj05ebxoIw0APRlUW?usp=sharing 
硬碟中的「 Training Dataset/training datalist.csv 」
