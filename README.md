# verilog_using_vscode
settings for verilog coding environment in vscode
  
## 因為好用，所以回不去了。
  
### 所需要安裝軟體:
### 1. vscode  
  
### 2. iStyle(自動排版功能)  
  
### 3. universal-ctags(自動語法檢查功能)  

### 4. Icarus(自動語法檢查功能)  
---
  
#### step1: 安裝vscode(略)  
  

#### step2: 安裝iStyle
[istyle-verilog-formatter](https://github.com/0qinghao/istyle-verilog-formatter/releases) released iStyle.exe  
直接下載完畢後，解壓縮，放在一個資料夾內，之後由VSCODE呼叫執行。  
(或在/doc 資料夾內)  

#### step3: 安裝universal-ctags
[universal-ctags](https://github.com/universal-ctags/ctags-win32/releases) release version
直接下載完畢後，解壓縮，放在一個資料夾內，之後由VSCODE呼叫執行。  
![universal-ctags/ctags-win32](/doc/pic-vscode-extensions-ctags.png "ctags-win32") 

#### step4: 安裝Icarus  
[Icarus](http://bleyer.org/icarus/)  
直接下載完畢後安裝。  
![universal-ctags/ctags-win32](/doc/pic-vscode-extensions-Icarus.png "Icarus") 

#### step5: 新增環境變數
step5.1  
![system-1](/doc/pic-system-settings.png "system setup1")  
step5.2  
![system-2](/doc/pic-system-settings2.png "system setup2")  
step5.3  
![system-3](/doc/pic-system-settings3.png "system setup3")  
step5.4  
![system-4](/doc/pic-system-settings4.png "system setup4")  
step5.5: 最後結果  
![system-4](/doc/pic-system-settings5.png "system setup5")  

#### step6: 新增VSCode Extensions
step6.1  
extension installation: SystemVerilog
![extension-1](/doc/pic-vscode-extensions-systemverilog.png "extension1")  
step6.2  
click extension - setting 
![extension-2](/doc/pic-vscode-extensions-systemverilog2.png "extension2")  
step6.3  
text entry: -i  
![extension-3](/doc/pic-vscode-extensions-systemverilog3.png "extension3")  
step6.4  
text entry: iverilog  
![extension-4](/doc/pic-vscode-extensions-systemverilog4.png "extension4")  
step6.5  
extension installation: verilog-formatter
![extension-5](/doc/pic-vscode-extensions-verilog-formatter.png "extension5")  
step6.6  
click extension - setting 
![extension-6](/doc/pic-vscode-extensions-verilog-formatter2.png "extension6")  
step6.7  
text entry: 1. iStyle path  
text entry: 2. format sytle  
![extension-7](/doc/pic-vscode-extensions-verilog-formatter3.png "extension7")  
step6.8  
之後去Settings (ctrl + ,)  
在Text Editor底下的Formatting  
勾選Format On Save  
![extension-8](/doc/pic-vscode-setting-save.png "extension8")  

---

## 測試功能
  
### 故意將分號移除;(產生錯誤訊息提示)
![exp-1](/doc/experimental-1.png "exp-1")  
