# jQuery Transfer

A jQuery plugin that is a shuttle box.Base on Bootstrap framework

## Demo

demo：`demo.html`

![base use](https://github.com/delei/jquery-transfer/blob/master/doc/demo.jpg)

## update

- [x] update folder
- [x] upgrade jQuery and Bootstrap
- [x] use icon font Glyphicons
- [x] fix css issues
- [x] update search function
- [x] fix checkbox issues

## plugins

- jQuery v1.12.4
- bootstrap v3.3.7

## how to use

```javascript
$('#container').transfer({
    soruce:'#source',
    target:'#target'
});
```

## options

<table>
   <tr>
		<th>Name</th>
        <th>Description</th>
        <th>Default value</th>
   </tr>
   <tr>
       <td>itemTpl</td>
       <td>tpl</td>
       <td></td>
   </tr>
    <tr>
       <td>source</td>
       <td>Source select element</td>
       <td>select:first</td>
   </tr>
   <tr>
       <td>sourceTtitle</td>
       <td>Source list title</td>
       <td>list1</td>
   </tr>
   <tr>
       <td>target</td>
       <td>Target select element</td>
       <td>select:last</td>
   </tr>
   <tr>
       <td>targetTitle</td>
       <td>Target list title</td>
       <td>list2</td>
   </tr>
    <tr>
       <td>iconPrefix</td>
       <td>Icon prefix</td>
       <td>glyphicon</td>
   </tr>
   <tr>
       <td>iconSearch</td>
       <td>Search icon class name</td>
       <td>glyphicon-search</td>
   </tr>
   <tr>
       <td>iconLeft</td>
       <td>Arrow left icon class name</td>
       <td>glyphicon-arrow-left</td>
   </tr>
   <tr>
       <td>iconRgiht</td>
       <td>Arrow right class name</td>
       <td>glyphicon-arrow-right</td>
   </tr>
</table>


## Thanks
shixinke jquery-transfer: [Github Repo](https://github.com/shixinke/jquery-transfer)

nekolr jquery-transfer:[Github Repo](https://github.com/nekolr/jquery-transfer)

bootstrap-transfer: [Github Repo](https://github.com/rabihkodeih/bootstrap-transfer)
