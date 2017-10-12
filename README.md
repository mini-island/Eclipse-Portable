# Eclipse-Portable
免安裝的 Eclipse，可使用隨身碟直接執行，適用於公用電腦開發環境。自帶 JDK，確保穩定的 Java 執行環境；內建 Git 支援，搭配 Github 超方便。

- From: [Eclipse Portable [4.6] [4.7] [4.8] - Makes Eclipse working on USB-Devices.
](https://sourceforge.net/projects/eclipse-neon-portable/) by [berny23](https://sourceforge.net/u/berny23/)
- Eclipse PHOTON 4.8M2
- Operating System: Windows 64bit
- Download size: About 250 mb

## Additional plugins
- EGit
- Eclipse Java Development Tools
- JDK 1.8.0 (Portable)

## Usage
1. Download or Clone this project.
2. Unzip the file after you download it.
3. Copy the folder to your USB stick.
4. Execute "EclipsePortable.exe" to go.

## Hello-Java
### 建立你的第一個 Java 程式，並且熟悉 Github 的操作。

1. 在瀏覽器登入你的 Github 帳號。
2. 到 [Hello-Java](https://github.com/mini-island/Hello-Java) 專案。
3. 於右上角，按下 Fork，選擇自己的帳號，複製整個專案到你的帳號下。
4. 切換到你的 Hello-Java 專案下，點選「Clone or Download」複製文字框內的連結。
   - 請確認你複製的連結是 .git 結尾的。
5. 打開你的 Eclipse。
6. 由工具列：File -> Import -> Git -> Project from Git -> Clone URI
> 如果沒有自動代入 Git 資訊，表示第 4 步驟未正確複製，請關閉對話框，複製完，再重做此步驟。
7. 點選 Next -> (確認 master 有打勾) -> Next -> 輸入自訂的 Directory -> Next
> Directory 可放在隨身碟裡，但速度較慢(小程式影響不大)，可以不用每次都重新 Clone。
8. 會自動偵測到專案：Import existing Eclipse projects -> Next -> Finish
9. 在 Project Exploer 中的 HelloWorld 以右鍵點選 -> Run as -> Java application
10. Console 中出現「Hello, World」字樣即完成。

### 第一次從 Eclipse 中 push 程式

1. 在 Project Exploer 中，從 src 裡找到 HelloWorld.java，點選後在右方會出現程式碼。
2. 試著稍微修改 "Hello, World" 的文字內容，例如："Hello Java World"。
3. Ctrl-S 存檔。
4. 在 Project Exploer 中的 HelloWorld 以右鍵點選 -> Team -> Commit...
5. 在右下角的 Git Staging 頁籤中的 Commit message 區塊，輸入訊息，例如："Hello Java World"。
> 一定要有 Commit message 才能 push。
6. 點選 Commit and Push...
7. 會跳出認證視窗，請輸入你的 GitHub 帳號及密碼。
8. 回到瀏覽器，到你的 Hello-Java 專案下，找到 HelloWorld.java，確認文字內容如你所修改的，就完成此項。

## Feedback
任何問題請到 Issues 區提出，請詳述發生的情形。
