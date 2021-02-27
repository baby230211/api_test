# api_test

用vuecli axios ,vue-router ,

做出頁面

目標

1.使用者滾動頁面可以加載 每滾動到最下面 call一次api 載入30個資料 ->類似instagram /facebook

2.router 頁面 顯示於最上面

遇到的問題

1.vue-router 子組件中callapi 為404 但是父組件 call的到 -> axios proxy改

2.組件的共用性 ,方法的共用性

3.vue-router-link router-view的觀念

4.vue-router會擋住url的變化

5.在部署到github pages時候 proxy會失效 反而不會有CORS的問題
