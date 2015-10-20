本篇將教大家如何建置 WoT.City 儀錶板 (theme-d3js-liquegauge)。

**步驟一**：請先至該倉庫複製 clone URL，並在您的工作區目錄使用 git clone 指令。

`git clone https://github.com/wotcity/theme-d3js-liquegauge.git`

![alt](https://oranwind.s3.amazonaws.com/2015/Oct/1a-1445352970507.png)

**步驟二**：使用 npm 安裝 Gulp 和 Bower 等工具 (已裝過的人請跳過此步驟)，指令如下：

`npm install --global gulp.
 npm install --global bower`

Q & A：[npm 報錯 Error: ENOENT](http://oranwind.org/node-js/)

**步驟三**：接著切換到 theme-d3js-liquegauge 的專案目錄下，並安裝相關套件及進行建置，指令如下：

`npm install
bower install
gulp build`

![](https://oranwind.s3.amazonaws.com/2015/Oct/3-1445353449637.png)
看到以上訊息代表已建置成功。

**步驟四**：打開專案目錄中的 index.html 並在其後方加入參數(裝置 ID) **#testman**，接著會看到儀表板數值隨意跳動。
![alt](https://oranwind.s3.amazonaws.com/2015/Oct/4-1445353699700.png)

完成。

**注意**：接著若修改專案內的 js 檔，請重新執行 gulp build 進行建置。
