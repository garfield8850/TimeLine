# TimeLine 时间控件

> 演示DEMO

[点击我查看](https://github.com/garfield8850/TimeLine/blob/master/index.html)

> 效果预览

![](https://github.com/garfield8850/TimeLine/blob/master/demo.png)

> 使用方法



```javascript
var timeline = new TimeLine({
    container: 'timeline',
    data: {
        year: [
            {text: '', date: '2013-01-02'},
            {text: '', date: '2014-01-02'},
            {text: '', date: '2015-01-02'},
            {text: '', date: '2016-01-02'}],
        month: [{text: 'Hello World', date: '2013-01-02'},
            {text: 'Hello World', date: '2013-04-02'},
            {text: 'Hello World', date: '2013-06-02'},
            {text: 'Hello World', date: '2013-08-02'}],
        day: [{text: 'Hello World', date: '2013-01-02'},
            {text: 'Hello World', date: '2013-01-04'},
            {text: 'Hello World', date: '2013-01-04'},
            {text: 'Hello World', date: '2013-01-04'},
            {text: 'Hello World', date: '2013-01-04'},
            {text: 'Hello World', date: '2013-01-05'},
            {text: 'Hello World', date: '2013-06-02'},
            {text: 'Hello World', date: '2013-08-02'}]
    }
});
```