# 全局变量

全局变量可以在平台中所有case处引用,常在[准备/执行信息/断言恢复]中使用

## 全局变量添加
首先进入```数据服务``` ```全局变量```页面 添加
![图片](/image/接口测试平台数据服务.png)
![图片](/image/接口测试平台全局变量添加.png)
输入变量key,变量值及变量描述,保存编辑即可.
变量值如果是各环境通用全局变量,则输入通用全局变量字段即可,否则可根据各套环境输入对应环境的变量值.

## 全局变量查询

![图片](/image/接口测试平台全局变量查询.png)
可根据[创建人]/[变量key]/[变量value]/[变量描述]条件匹配查询

## 全局变量使用

![图片](/image/接口测试平台全局变量使用.png)

调用方式$GVAR[gvarKey] ,可直接在[准备/执行信息/断言恢复]等处使用

## 全局变量操作

![图片](/image/接口测试平台全局变量操作.png)

点击 ```查看``` 按钮查看变量详情,点击 ```删除``` 按钮删除变量,点击```编辑``` 按钮可修改变量

![图片](/image/接口测试平台全局变量编辑.png)


