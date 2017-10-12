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
建立你的第一個 Java 程式，並且熟悉 Github 的操作。

1. 在瀏覽器登入你的 Github 帳號。
2. 到 [Hello-Java](https://github.com/mini-island/Hello-Java) 專案。
3. 於右上角，按下 Fork，選擇自己的帳號，複製整個專案到你的帳號下。
4. 切換到你的 Hello-Java 專案下，點選「Clone or Download」複製文字框內的連結。
   - 請確認你複製的連結是 .git 結尾的。
5. 打開你的 Eclipse。
6. 由工具列：File -> Import -> Git -> Project from Git -> Clone URI
   - 如果沒有自動代入 Git 資訊，表示第 4 步驟未正確複製，請關閉對話框，複製完，再重做此步驟。
7. 點選 Next -> (確認 master 有打勾) -> Next -> 輸入自訂的 Directory -> Finish
   - Directory 建議放在公用電腦的桌面，而非隨身碟，速度較快。
8. 在 Project Exploer 中的 HelloWorld 以右鍵點選 -> Run as -> Java application
9. Console 中出現「Hello, World」字樣即完成。

## Feedback
任何問題請到 Issues 區提出，請詳述發生的情形。
