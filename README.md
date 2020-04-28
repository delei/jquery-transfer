# jQuery Transfer

一个使用jQuery,基于普通select元素实现的穿梭框，左右双列表插件

## 插件效果

demo：`demo.html`

![基本用法](https://github.com/delei/jquery-transfer/blob/master/doc/demo.jpg)

## 更新内容

- [x] 调整了仓库文件夹目录
- [x] 更新升级基础依赖插件的版本，满足目前常用的最低版
- [x] 更新bootstrap后，默认图标修改为Glyphicons
- [x] 更新bootstrap后，修复样式兼容问题
- [x] 增强查询功能(前端查询)，支持模糊字查询

## 插件依赖
对原作者的依赖进行了版本更新升级

- jQuery v1.12.4
- bootstrap v3.3.7

## 插件基本用法

```javascript
$('#container').transfer({
    soruce:'#source',
    target:'#target'
});
```

## 插件参数

<table>
   <tr>
		<th>参数名</th>
        <th>说明</th>
        <th>默认值</th>
   </tr>
   <tr>
       <td>itemTpl</td>
       <td>每个选项模板内容</td>
       <td></td>
   </tr>
    <tr>
       <td>source</td>
       <td>第一个下拉框选择器</td>
       <td>select:first</td>
   </tr>
   <tr>
       <td>sourceTtitle</td>
       <td>列表标题</td>
       <td>列表1</td>
   </tr>
   <tr>
       <td>target</td>
       <td>第二个下拉框选择器</td>
       <td>select:last</td>
   </tr>
   <tr>
       <td>targetTitle</td>
       <td>列表标题</td>
       <td>列表2</td>
   </tr>
    <tr>
       <td>iconPrefix</td>
       <td>字体图标前缀</td>
       <td>glyphicon</td>
   </tr>
   <tr>
       <td>iconSearch</td>
       <td>搜索图标</td>
       <td>glyphicon-search</td>
   </tr>
   <tr>
       <td>iconLeft</td>
       <td>向左图标</td>
       <td>glyphicon-arrow-left</td>
   </tr>
   <tr>
       <td>iconRgiht</td>
       <td>向右图标</td>
       <td>glyphicon-arrow-right</td>
   </tr>
</table>

## 致谢原作者

author : shixinke <ishixinke@qq.com>

github : [源仓库](https://github.com/shixinke/jquery-transfer)
