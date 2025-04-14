# CloudNative
雲原生作業2
(1)	repo創建:登入github後，右上角+號創建新的repo，確定repo名稱及描述，並設成public且加入README檔案。  
(2)	main branch:   
1.	README:點選README即可直接修改，然後commit。  
2.	建立main.py，裡面包含用python寫的加法函式，然後commit。  
3.	建立測試檔test_main.py，裡面包含測試main.py加法的函式，然後commit。  
4.	建立 GitHub Action 檔.github/workflows/main.yml，如附圖，用來做action，觸發條件是分支發pr到main的時候，會checkout repo，設定python環境，並測試main.py加法函式對不對。  
5.	建立Issue Template -> .github/ISSUE_TEMPLATE/bug.md，內容為回報錯誤的一些格式，然後commit後就可使用。  
(3)	hw1-p branch:  
1.	左上角「main ▼」後輸入hw1-p後，「Create branch: hw1-p from 'main'」。  
2.	在main.py新增註解後發pr，action成功。  
3.	在pr的commit那裡選擇更改的程式碼，留言後add single comment。  
(4)	hw1-f branch:  
1.	左上角「main ▼」後輸入hw1-f後，「Create branch: hw1-f from 'main'」。  
2.	在main.py中將加法函式改成減法後發pr，action失敗。  
(5)	Issue  
1.	點「Issues」分頁 → 「New issue」，看要不要選擇模板，寫好標題與內容後送出。  
