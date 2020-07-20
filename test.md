#### 四级标题 ####
##### 五级标题 #####
###### 六级标题 #####
```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8"/>
        <title>混合布局</title>
    </head>
    <style>
    body{
        margin:0;
    }
    .box{
        width:960px;
        margin:0 auto;
    }
    .header{
        height:120px;
        background-color:#ddd;    
    }
    .main{
        height:400px;
        background-color:#f00;
        position:relative;
    }
 
    .main .left{
        width:200px;
        height:400px;
        position:absolute;
        left:0;
        top:0;
        background-color:#0fccaa;
    }
    .main .center{
        height:400px;
        margin:0 305px 0 205px;
        background-color:#123456;
    }
 
    .main .right{
        width:300px;
        height:400px;
        position:absolute;
        right:0;
        top:0;
        background-color:#ff0;
    }
    .footer{
        height:80px;
        background-color:#ddd;
    }
    </style>
    <body>        
        <div class="box">
            <div class="header">header</div>
            <div class="main">
                <div class="left">left</div>
                <div class="center">center</div>
                <div class="right">right</div>        
            </div>
            <div class="footer">footer</div>
        </div>    
    </body>
</html>
```
![Image text](https://raw.githubusercontent.com/lenhop/gweb/master/img/frame.jpeg)


