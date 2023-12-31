## 注意事項

我們對自動評分(Autograding)框架進行了修改，提供較友善的命令。現在，你可以使用以下指令：

- ../testing：您必須進入練習/問題目錄以執行此指令，用以驗證您的作業答案。
- ./grading：這個指令驗證你的作業答案並生成/提交評分報告。
- ./mystatus：使用此指令查看你已提交的所有評分報告。

## 作業提交

*執行 `./grading` 命令來驗證你的程式並輸出`成績報告`：*
```shell
[week07]$ ./grading 
Checking 'ex01' => passed!
Checking 'ex02' => passed!
Grade: 100

Database[hdl2023fall] - week07

Do you need to submit a scoring report? (yes/no): yes
Scoring report submitted!
```

*如果您準備好提交你的`成績報告`，當看到以下提示時，輸入 "`yes`"：*
```
Do you need to submit a scoring report? (yes/no):
```
- `為減少資料庫不必要的存取用量，盡可能避免多次提交成績報告!` 
- `如有異常多次提交報告，你的帳戶將被鎖住。`

*如果您的`成績報告`成功提交，您將看到以下提示：*
```
Scoring report submitted!
```

*您可以使用 `./mystatus` 命令來查看您已提交的所有`成績報告`：*
```shell
[sol-week07]$ ./mystatus
Class ID       : hdl2023fall
Github User    : jyang
----------------------------------------
Assessment     : week06
Passed         : ex01 ex02 ex03 
Grade          : 100
Summit         : 2023-10-18 00:04:52
----------------------------------------
Assessment     : week07
Passed         : ex01 ex02 
Grade          : 100
Summit         : 2023-10-19 17:24:54
----------------------------------------
```
