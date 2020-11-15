 学习笔记
 
 nbsp: 不推荐使用，会将前后两个词并为一个
 
 [DTD](http://www.w3.org/TR/xhtml1/DTD/xhtml-lat1.ent)
 
 
 ### Html
 
 * `<strong></strong>`：表示词在文章中的重要性，不改变语义
 * `<em></em>`：表示在语句中的语气强调
 
 #### 合法元素
 * Element：`<tagname></tagname>`
 * Text：
 * Comment：
 * DocumentType：
 * ProcessingInstruction：
 * CDATA：
 
 #### 字符引用
 * 
 
 #### 事件Api
 `target.addEventListener(type, listener, [options])`
 
 `options`为`true` | `false`, 事件是捕获模式还是冒泡模式
 `options`
   * capture: 
   * once
   * passive；事件是否不会产生副作用，在一些高频事件中可以置为true，优化新能
 
 #### DOM
 * 节点
 * 事件
 * Range Api
 
 #### 高级操作
 * compareDocumentPosition 用于比较两个节点中关系的函数
 * contains 检查一个节点是否包好另一个节点的函数
 * isEqualNode 检查两个节点是否完全相同（dom结构相同就完全相同 ）
 * isSamneNode 检查两个节点是否是同一个节点，实际上在javaScript 中可以用"==="
 * cloneNode 复制一个节点，如果传入参数true，则会连同子元素做深拷贝
 
#### window
window.devicePixelRatio 