# TimeLine 时间控件


> 效果预览

![](https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif)  

> 使用方法



<pre><code>
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
</code></pre>