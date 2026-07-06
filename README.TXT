Coding Agent 好物推薦：Browser Use 發佈 CLI 3.0，更高效的瀏覽器操作
雖然大家的 Coding Agent 都有 Browser 操作能力，但大部分的操作都是使用 click()、type() 以及 screenshot 這種猜測，而且在操作的時候，常常需要把整個 DOM 樹塞入上下文中，非常慢，佔 token 以及耗時間。
Browser Use CLI 3.0 使用 Chrome DevTools Protocol，讓 Coding Agent 的操作更為直接。最厲害的是能累積並重複使用在不同網站上的操作經驗。無論是摸索出的登入流程、元素選擇器還是特殊狀況的處理方式，都會被儲存為專屬的「網域技能（domain-skills）」。未來遇到相似網站就能自動套用，操作越久越流暢。
若執行過程中遇到缺乏對應指令的狀況（例如需要上傳檔案卻沒有現成的函式可用），Agent 能夠立刻自行撰寫出需要的程式碼並接續執行，確保流程順暢、不會中斷卡死。
支援三種環境，即 Chrome、雲端環境及自訂端點，應該是萬用了。
怎麼安裝？在 Claude Code 或 Codex 中，直接輸入：
「使用 Python 3.12，透過 uv 安裝或升級 browser-use 到最新穩定版，從 browser-use skill 註冊該 skill，並連接到我的瀏覽器。如果設定或連線失敗，請依照 https://github.com/browser-use/browser-use 的說明處理。」
去官網產生一個 API Key 就行(免費)。試了非常好用也快，大家快點裝起來。
