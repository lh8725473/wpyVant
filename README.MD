### wepy集成vant项目示例

1.安装依赖
```
  npm install
  or
  yarn install
```

2.用微信开发者工具打开根目录

3.配置开发者工具'本地设置'选项

![weSetting](./static/weSetting.png) 

4.wpy文件中增加组件引用

![vanDome](./static/vanDome.png) 

5.wpy文件模板中正常使用
```
<div class="container">
  <van-button bindtap="mytestClick" type="primary">按钮<van-button>
</div>  
```