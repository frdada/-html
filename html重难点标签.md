# html常用标签

## a 标签
  作用：

  1.跳转外部页面

  2.跳转内部锚点

  3.跳转邮箱或者电话等
  ### href的取值
  1. 网址
   * https://google.com
   * http://google.com
   * //google.com
  2. 路径
   * /a/b/c 以及 a/b/c
   * index.com 以及 /index.com
  
 
  3. 伪协议
   * javascript:代码
   * mailto:邮箱
   * tel:手机
  4. id
   * href:#xxx
  
  ### target的取值
  * 内置名字
  
     -black

     _top

     _parent

     _self
  * 程序员命名
  
     window的name

     iframe的name


  download

  rel=noopener

  ## 作用



## table 标签
  作用：

      用于新建表格

      <thead>
          <tr>
            <th>
                <td>
                <td/>
            <th/>
          <tr/>
      <thead/>

      <tbody>
          <tr>
            <th>
                <td>
                <td/>
            <th/>
          <tr/>
      <tbody/>

      <tfoot>
      <tr>
        <th>
          <td>
          <td/>
        <th/>
      <tr/>
      <tfoot/>

 相关样式：

 table-layout:auto;

 border-collapse:collapse;

 border-spacing:0;



## img标签的用法
### 作用

 发出get请求，展示一张图片
### 属性

 alt/height/width/src

### 事件

 onload/onerror

### 响应式
 max-width:100%

## from标签

### 作用

 发出get或者post请求然后刷新页面
### 属性

 action/autocomplete/method/target

### 事件

  onsubmit   

### 注意点
 需要跟submit事件配合使用，input默认type默认是submit