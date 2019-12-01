## vueLearn

### vue介紹

1.  漸進式架構
    -   從工具箱中依需求選擇工具，可以只用一部分的功能
2.  響應式原理、系統 (reactivity system)
    -   雙向綁定
    -   Vue資料響應是依賴Object.defineProperty ( IE8不支援 )
    -   Vue 3.0 改用ES6的Proxy
3.  輕量，檔案小，載入快
    
4.  類MVVM ( 基本上follow )
    

| Model | View Model | View |
| --- | --- | --- |
| Vue實例的data | Vue實例 | DOM |
| data變化 | VM監聽 | DOM變化 |

5.  核心專注view layout的呈現
    
6.  資料變化，操作資料，不直接操作DOM元素
    
7.  組件化 ( 組成 )
    
    -  模板 | ( v-if / v-for …等，Vue提供之方法 )
        
    -  實例 | ( data / methods …等，Vue實體提供之方法 )
        
8.  SPA ( single page application )
    
9.  聲明式渲染 ( Vue/React/Angular )，JQurey為命令式


### 優點

1.  無需綁定事件，View Model只有單純的邏輯
2.  掃一眼Html便能定位Js對應的方法
3.  View Model銷毀時，事件處理器自動刪除
