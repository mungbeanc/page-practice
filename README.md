# page-practice
静态页面
@charset "utf-8";
* {margin:0;padding:0;}
ul,ol,li {list-style: none;}
a,u {text-decoration: none;}
i,em {font-style: normal;}
b,strong {font-weight: normal;}
h1,h2,h3,h4,h5,h6{font-size: 16px;font-weight: normal;}

#topwrap {height:80px;background: black;}
#topwrap .wrap-cont,.case-cont,.news-cont{width:1000px;margin: 0 auto;}
.wrap-cont {height:80px;}
.wrap-cont .logo {height: 51px;width:177px;float:left;padding:11px 0 0 12px;}
.list-box {width:778px;height:52px;float:right;padding-top: 10px;}
.list-box li {
    height:62px;
    float:left;
    background: url(../images/libg_03.jpg) no-repeat right center;
    line-height: 62px;
    font-size: 12px;
    padding:0 16px;
}
.list-box li a {color:#fff;}
.list-box .bg-none {background: none;}

#banner {
    height:420px;
    background: url(../images/banner_01.jpg) no-repeat center;
    border-bottom: 1px solid #a8a8a8;
}

#case {height:350px;background: #f5f5f5;}
.case-cont{height:350px;}
.case-cont li {
    text-align:center;
    padding-top:55px;
    float: left;
    background: url(../images/casebg_03.jpg) no-repeat right 35px;
    height:295px;
}
.case-cont li h2 {font-size: 20px;line-height: 20px;color:#252e3b;margin-top: 16px;}
.case-cont li h3 {font-size: 12px;line-height: 12px;color :#546c7d;margin: 19px 0 16px;}
.case-cont li p{font-size: 12px;line-height: 18px;color: #a3c8de;}
.case-show1 {width:262px;}
.case-show2 {width:255px;}
.case-show3 {width:252px;}
.case-cont .case-show4 {width:231px;background: none;}

.news-cont{height:269px;padding-top: 40px;}
.news-l{
    width:297px;
    height: 224px;
    border: 1px solid #ADAAAA;
    padding:1px;
    float:left;
}
.news-l img{width:297px;height: 224px;}
.news-c{width: 320px;height: 250px;float: left;margin:0 18px 0 15px;}
.news-c h2{
    font-size: 18px;
    line-height: 18px;
    color: #222;
    padding-top: 6px;
}
.news-c h3{font-size:14px;line-height:14px;margin:17px 0 12px;}
.news-c p {font-size:12px;line-height:18px;text-indent:2em;border-bottom:1px dashed #ccc;padding-bottom:10px;}
.news-c p a{color: #999;}
.news-r {
    width:345px;
    height: 220px;
    background:gray;
    margin-top: 4px;
    float: left;
}
