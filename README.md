## 说明：
这是一个使用ES6语法（主要是ES6类、let、箭头函数、模板字符串`${}`的使用）编写的一个抽奖程序，主要功能如下：
1. 使用了html5 localStorage来存储中奖的号码
2. 按空格键可以开始和停止抽奖
3. 按左右方向键可以切换上一轮或下一轮抽奖环节
4. 按Ctrl + z组合键可以清除所有的中奖记录
5. 方向上键可以查询所有中奖记录
6. 本项目中安装好了Babel，直接在本项目根目录执行`npm run build` 即可编译es6->es5
7. 在IE9+下面运行改程序，必须先将该程序放到服务器环境，否则`IE doesn't support localStorage for local files`
## 项目使用：
``` bash
# 安装项目所需依赖
npm install

# 编译ES6
npm run build
```
update:
2017-10-20
支持每轮抽奖可以设置多个抽奖项目

