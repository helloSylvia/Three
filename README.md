# 街区地图项目
## 应用架构
1、Knockout.js<br/>
2、Google Map API<br/>
3、MVC模式<br/>
4、JQuery Ajax<br/>

## 界面设计
1、页面具有响应性，在PC和移动端能良好的适用。

## 应用功能
### 1、地点筛选
   1.1 输入框，输入标记中存在的地点名称或地点类型（可以不是全称），及时搜索，匹配的列表项和对应标记即会显示。<br/>
### 2、列表视图 
   2.1 默认显示所有的地点名称的列表视图，及对应的标记。<br/>
   2.2 分类选择，点击类型，匹配的列表项和对应标记即会显示，不匹配的隐藏。<br/>
   2.3 点击某个地点名称，对应标记跳动且显示信息窗和信息内容，左侧栏也显示对应内容。<br/>
### 3、标记
   3.1 标记hover状态时，图像变大。<br/>
   3.2 标记点击状态时，显示信息窗和信息内容，左侧栏也显示对应内容。<br/>
   3.3 关闭信息窗，标记停止动画。
   3.4 点击显示、隐藏按钮可显示、隐藏所有的标记。<br/>
### 4、地图
   4.1 地图可点击样式切换按钮，切换地图样式。
   
## 异步数据使用
### 1、信息窗
   1.1 信息窗中显示内容为调用第三方（百度地图API）API查询详情所得。<br/>
   1.2 信息窗中调用Google Map webService ，显示街景地图，没有街景地图，提示用户没有查询结果。<br/>
### 2、错误处理
   2.1 第三方调用使用ajax，错误返回在error中处理。<br/>
   2.2 对每次调用服务和或API返回的数据，做非空判断。
 
## 应用效果
   基本完成项目要求。
   
## 项目修改
   1、解决了点击列表名称后再点击下一个，上一个信息窗没有关闭的问题。
   2、优化了及时搜索
   3、优化了google API 返回错误，给用户及时提示
   