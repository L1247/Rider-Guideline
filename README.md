## 讀取阿星的Rider設定檔
My Rider Setting Repository
https://github.com/L1247/Rider-Setting-Repository
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Load%20RepositorySetting.gif?raw=true)
# Rider-Guideline
https://github.com/JetBrains/resharper-unity

GetComponent
https://github.com/JetBrains/resharper-unity/wiki/Avoid-usage-of-GetComponent-methods-in-performance-critical-context

# Shortcuts
## Code Complete 自動完成
* 括號內使用可以Show出所有該格可以使用的參數 。括號內按 Alt + Space 
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Code%20Complete%20-%20Basic.png?raw=true)

## Code Complete-Cyclic Expand Word 字串自動完成。 
* 字串內按 Alt + / 尋找目前開啟的視窗，自動填入符合的字串
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Code%20Complete%20-%20Cyclic%20Expand%20Word.gif?raw=true)

## Basic Completion 基本的自動完成，搜尋現有已宣告的欄位(field)
* 按下 Ctrl + Space
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Basic%20Completion.gif?raw=true)

## Parameter Info 參數資訊
* 括號內按 Ctrl + P
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Show%20Parameter%20Info.png?raw=true)

## Comment With Line 註解單行
* Ctrl + /

![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Comment%20With%20Line.gif?raw=true)

## Comment With Block 註解選取，並加上/**/
* 選取範圍程式碼後，Ctrl + Shift + /
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Block%20Comment.gif?raw=true)

## Rearrange Code 重新排列程式碼，需使用阿星的File Layout，按照Public Protected Priveate 往下排列
* Ctrl + Alt + ,
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Rearrange%20Code.gif?raw=true)

## Reformat Code 重新格式化程式碼，將開頭對齊，或者刪除沒用的空白
* Shift + Alt + L
![image](https://github.com/L1247/Rider-IDE-Guideline/blob/master/ScreenShot/Reformat%20Code.gif?raw=true)
 
* Ctrl + E - Recent Files.
* Ctrl+Shift+Alt+A - Inspect This.
  * 在函數上使用，可以顯示外部內部調用、Code Issues等等
* Ctrl+/ - 單行註解。
* Ctrl+Shift+/ - 選取的範圍註解。
* Ctrl+Shift+Space - Smart Type. 智慧提示。
* Alt+Insert - Generate Code. 產生一些範例程式碼
* Crtl+W - Extend Selection. 每按一次，慢慢往外選擇。
* Ctrl+Left | Ctrl+Right - Move Creat to Previous Word | Move Creat to Next Word. 切換所在輸入位置至前後的字。
* Alt+Left | Alt+Right - Select Previous Tab | Select Next Tab. 切換所在位置的上下分頁。
* Alt+Shift+Up | Alt+Shift+Down - Move Creat to Previous Method | Move Creat to Next Method. 上下切換函數。
* Ctrl+Shift+A - Find Action.
* Ctrl+Shift+R - Refactor This.
* Shift+Alt+L - Locating Current File in Solution Explorer.
* Ctrl+Alt+S - Rider settings.
* Ctrl+Alt+Z - Revert Changes.
* Ctrl+Alt+Right - Split Current Editor Tab Move Right.
* Ctrl+Alt+Left - Move To Opposite Group.
* Ctrl+Shift+Enter - 在IF區域大括號(右)外面按下會自動產生Else.
* Ctrl+Q - Show API Documentation.
* Ctrl+J - Show Method Info. 在方法內按下會顯示該參數的細節。
* Ctrl+Backspace - Delete to Word Start. 刪除一行到上一行的最後。
* Ctrl+Enter - 跳到對齊行的開頭，可以不用一直按TAB。
* 在方法內打完參數後，按下Ctrl + Enter 就會直接跳到尾端.
* Shift + Enter 則跳下一行.
* 在方法上面，按Ctrl+Alt+Up or Down 能夠切換使用此方法的地方，上為回去上一個、下為跳到下一個。
* Alt+6 - Show All Todo.
* Ctrl+F12 - Show File Member.
* Ctrl+/ | Crtl+Numpad/ - Comment with Line Comment
* Ctrl+Shift+/ | Ctrl+Shift+Numpad/ - Comment with Block Comment
* Alt+Home - Jump To Navigation Bar in Main menu.
* Shift+Shitft - Search EveryWhere.
* Ctrl+Alt+j - Surround With. 可以把選取的括號之類的。
* Ctrl+Shift+j - Join Line. 1.在該行的前面用可以把下一行的頭Cut到該行的最後面。2.把多行選起來，可以讓多行變成同一行。
* Ctrl+Shift+Enter - 直接在最後面加上分號，並的開頭跳到下一行。
* Ctrl+Shift+I - Show出目前的類別檔案在小視窗內。
* Ctrl+B - Goto Declaration. 跳到宣告的地方.
* Ctrl+Minus - Back. 返回上一個地方。

# Refactoring
* Ctrl+Alt+V - 產生區域變數
* Ctrl+Alt+D - 產生欄位變數

# Custom Shortcuts
* Shift+Alt+Up or Down - Previous or Next Method.
* Alt+Up or Down - Move Line Up or Down.

# TODO
* 在相同關鍵字上下移動
* 插入上一行
* 把選擇的區段往左或右的括號內移動。

# Code
* // Todo 使用關鍵字Todo可以寫下未作的事情，並可按下Alt+6 - Show All Todo。
