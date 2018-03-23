# muyuchengfeng
muyuchengfeng



## popup
---
<Popup :popup-msg='msg' :show='show' @select="select"></Popup>

data(){
  return{
    msg: 'AA',      // 弹窗的提示文案
    show: Boolean
  }
}
 ######获取用户选择结果 1是 0否 */
select (status) {
  this.show = false  // 关闭弹窗
}

---