# VUE-BASE

### createApp & Setup


### ref,reactive

ref() : 可以接受任何型態的資料，但是不會對物件或陣列內部的屬性變動做監聽。
reactive() : 只能接受物件或陣列，可以做深層的監聽，以及訪問資料不需要 .value。

### 資料綁定v-model

### 事件綁定 v-on
v-on:click
@click

### readonly
防止定義的資料被修改

### v-for 列表渲染
key:不變動且唯一，增加渲染效能 

### v-if,v-show
v-if:新增,刪除dom
v-show:ccs控制

### v-bind:attribute

### Computed
Computed 會針對結果進行緩存，不能傳入參數

### watch,watchEffect資料監控
watchEffect 有使用到才會被監控，可被停止

### Lifecycle Hooks 生命週期
onBeforeMount  => DOM 渲染前執行 
onMounted  => DOM 渲染完成後執行 
onBeforeUpdate  => 資料更新DOM更改前執行
onUpdated => 資料更新DOM更改後執行
onBeforeUnmount => 組件銷毀前執行
onUnmounted => 組件銷毀後執行
onErrorCaptured => 當組件發出錯誤時後調用
onRenderTracked => 監控 virtual DOM 重新選染時調用 ( 此事件告訴你操作什麼監聽了組件以及該操作的物件)
onRenderTriggered => 監控 virtual DOM 重新選染時調用 ( 此事件告訴你操作什麼觸發了重新渲染，以及該操作的物件)

### v-html

### 事件修飾符 Event Modifiers
.stop
.prevent
.self
.capture
.once
.passive