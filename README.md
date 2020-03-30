# Flutter-Need
本项目将长期进行维护，以简体中文形势，帮助Web前端工程师更好的学习和上手Flutter项目
如果你想加入此项目的开发与维护，可以添加我的QQ:303690243
我也将在人数超过50人后成立QQ群。
## Fluuter-Need将会持续更新Flutter中Widget的相关文档，并对比Web前端开发中的代码，让国内前端工程师更加快速上手Flutter应用
## 项目从2020年3月30日开始进行维护，由于第一次做相关工作，还请各位同学多提意见。
### Widget目录
#### Container---一个可以灵活使用的部件，我们可以将其理解成HTML中的DIV标签
##### 前端代码
```
<div class='container'>文字</div>
<style>
.container{
    padding:40px,
    background-color:red,
    width:400px,
    height:400px,
    magin:40px
}
</style>
```
##### Flutter代码

```
Container(
    alignment: Alignment.center,   //设置Container的子部件相对与其的对齐方式
    padding:EdgeInsetsAll(40),    //设置Container内部填充的大小
    color:Colors.red               //设置背景颜色(不能和decoration属性共同使用)
    decoration:                    //装饰器
    foregroundDecoration:
    width:400,             //部件的宽
    height:400,            //部件的高
    constraints             
    margin:EdgeInsetsAll(40)     //设置Container的外边距
    transform
    child:Text('文字')       //设置Container的子部件(子元素)
)
```