# assign6-blank
- 2015 web assign 6 blank
- [作業說明連結](https://docs.google.com/presentation/d/1Ma1Oko6cEy7z3K9ijf1DUdCNK-NeAIFqWoa3ItUci4g/edit#slide=id.p4)
- 不知道該怎麼設定角色或怎麼做簽到功能，請不要客氣的問助教，我們會給你一些指引。

## 請依照註解完成以下檔案
- js/key.js
- signUp.html
- logIn.html
- index.html
- attendantList.html

順序：
先寫js/key.js
寫signUp
logIn(使用者簽到要先創造一個object)
index
最後寫attendantList

#Questions
- var AttendantList = Parse.Object.extend("AttendantList"); //新增資料表
- e.preventDefault是避免點選連結時轉址，例如點下href = "xxx" ，應會轉址，寫上preventDefault按了也不會轉址。
- Parse.User.logIn()//為什麼user logIn 有辦法判斷user資料裡面有沒有match到？parse寫好的
- 無論是不是預設的原生物件都可以用.set，Subsequent updates to a user can be done by calling save.


