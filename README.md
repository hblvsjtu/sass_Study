# React_Study
        
        
        
## 五，sass的基本使用
        
        
### 作者：冰红茶  

### 参考源：[sass官网](http://sass-lang.com)
### 参考源：[sass教学视频](https://www.bilibili.com/video/av17492787/?p=1)
  
        
------    
        
        
        
   sass跟css有很大的不一样，css是一种层叠样式表，并不是一种编程语言，至少没有变量，循环，流程控制等语法。而sass前置解释器，拥有以上的功能，使得编辑和更新css就更加的方便。对于未来日益复杂和工程化的项目，掌握类似sass或者less等是非常有利的。因为之前在webpack打包的时候发现sass加载不进去，我就想看看到底是怎么回事^_ ^
        
        
## 目录
        
## [五，sass的基本使用](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md)
### [5.1 简介](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.1)
#### [5.1.1 背景和特点](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.1.1)
#### [5.1.2 Compass](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.1.2)
#### [5.1.3 比较差异sass和less和styus](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.1.3)
### [5.2 基本语法](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2)
#### [5.2.1 设置变量](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.1) 
#### [5.2.2 文件的导入](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.2) 
#### [5.2.3 嵌套](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.3)
#### [5.2.4 继承@extend](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.4)  
#### [5.2.5 数据类型与数据操作](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.5)
#### [5.2.6 @mixin@include](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.6)
#### [5.2.7 自定义函数@function@return](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.7)
#### [5.2.8 流程控制](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.2.8)
### [5.3 自动化构建](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.3)
#### [5.3.1 cli命令](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.3.1) 
#### [5.3.2 基础项目结构](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.3.2) 
#### [5.3.3 grup自动化构建](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.3.3)
#### [5.3.4 webpack自动化构建](https://github.com/hblvsjtu/React_Study/blob/master/五，sass的基本使用.md#5.3.4)

        
------
