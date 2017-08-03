---
layout: docs
title: Buttons
description: Use Bootstrap's custom button styles for actions in forms, dialogs, and more with support for multiple sizes, states, and more.
group: components
redirect_from: "/components/"
---
## UI组件

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

<!-- ## Examples -->
## 1.短按钮:

{% example html %} 
  <button class="ui-btn">确定</button>
  <button class="ui-btn ui-btn-primary">确定</button>
  <button class="ui-btn ui-btn-danger">确定</button>
  <button class="ui-btn ui-btn-highlight">确定</button>
{% endexample %}


<!-- ## Examples -->
## 2.长按钮

{% example html %}
<button class="ui-btn-lg">确定</button>

<button class="ui-btn-lg ui-btn-primary">确定</button>
       
<button class="ui-btn-lg ui-btn-danger">确定</button>
      
<button class="ui-btn-lg disabled">取消</button>
           
<button class="ui-btn-highlight ui-btn-lg">取消</button>
{% endexample %}


## 3.2/3按钮
{% example html %}
<button class="ui-btn-lg-nowhole">取消</button>
<button class="ui-btn-lg-nowhole ui-btn-primary">取消</button>
<button class="ui-btn-lg-nowhole ui-btn-danger">取消</button>
<button class="ui-btn-lg-nowhole ui-btn-danger disabled">取消</button>
{% endexample %}

## 菜单 actionsheet

{% example html %}
	<div class="ui-actionsheet ">
	    <div class="ui-actionsheet-cnt am-actionsheet-down">
	        <h4>同时会将我从对方的列表中删除</h4>
	        <button>分享</button>
	        <button class="ui-actionsheet-del">删除</button>
	        <div class="ui-actionsheet-split-line"></div>
	        <button id="cancel">取消</button>
	    </div>
	</div>
{% endexample %}


## 提示
## 1.提示:

{% example html %}
<div class="ui-tooltips">
    <div class="ui-tooltips-cnt ui-tooltips-cnt-link ui-border-b">
        无法连接服务器，请检查你的网络设置。
    </div>
</div>
<div class="ui-tooltips">
    <div class="ui-tooltips-cnt ui-border-b">
        无法连接服务器，请检查你的网络设置。<a class="ui-icon-close"></a>
    </div>
</div>
{% endexample %}


<!-- ## Examples -->
## 2.警示提示

{% example html %}
<div class="ui-tooltips ui-tooltips-warn">
    <div class="ui-tooltips-cnt ui-tooltips-cnt-link ui-border-b">
        <i></i>无法连接服务器，请检查你的网络设置。
    </div>
</div>
<div class="ui-tooltips ui-tooltips-warn">
    <div class="ui-tooltips-cnt ui-border-b">
        <i></i>无法连接服务器，请检查你的网络设置。<a class="ui-icon-close"></a>
    </div>
</div>
{% endexample %}

<!-- ## Examples -->
## 3.引导提示

{% example html %}
<div class="ui-tooltips ui-tooltips-guide">
    <div class="ui-tooltips-cnt ui-tooltips-cnt-link ui-border-b">
        <i class="ui-icon-talk"></i>进行时状态相关进行时状态相关进行时状态相关进行时状态相关
    </div>
</div>
<div class="ui-tooltips ui-tooltips-guide">
    <div class="ui-tooltips-cnt ui-border-b">
        <i></i>新手引导、新功能推荐、广告推广等。新手引导、新功能推荐、广告推广等。<a class="ui-icon-close"></a>
    </div>
</div>
<div class="ui-tooltips ui-tooltips-guide ui-tooltips-function">
    <div class="ui-tooltips-cnt ui-border-b">
        <i></i>新手引导、新功能推荐、广告推广等。新手引导、新功能推荐、广告推广等。<button class="ui-btn-s">开通</button>
    </div>
</div>
{% endexample %}

<!-- ## Examples -->
## 4.底部引导条

{% example html %}
<div class="ui-tooltips ui-tooltips-guide ui-tooltips-action">
    <div class="ui-tooltips-cnt ui-border-b">
        <i></i>底部引导条<button class="ui-btn-s">开通</button><a class="ui-icon-close"></a>
    </div>
</div>
{% endexample %}


<!--  -->
## 1.文字提示（带标题）

{% example html %}
	<div class="ui-dialog">
	    <div class="ui-dialog-cnt">
	        <div class="ui-dialog-bd">
	            <h4>下线通知</h4>
	            <p>你的账号于17:00在一台Android手机登录。如非本人操作，密码可能已泄露，建议立即冻结账号。</p>
	        </div>
	        <div class="ui-dialog-ft">
	            <button type="button" data-role="button">退出</button>
	            <button type="button" data-role="button" class="btn-recommand">重新登录</button>
	        </div>
	    </div>        
	</div>
{% endexample %}

<!-- ## Examples -->
## 2.文字提示（不带标题）

{% example html %}
	<div class="ui-dialog">
	    <div class="ui-dialog-cnt">
	        <div class="ui-dialog-bd">
	            <h4>将终止文件发送，确定返回？</h4>
	        </div>
	        <div class="ui-dialog-ft">
	            <button type="button" data-role="button">取消</button>
	            <button type="button" data-role="button">确定</button>
	        </div>
	    </div>        
	</div>
{% endexample %}

<!-- ## Examples -->
## 3.结构化消息提示

{% example html %}
	<div class="ui-dialog ui-dialog-function">
	    <div class="ui-dialog-cnt">
	        <div class="ui-dialog-bd">
	            <h4>发送到 seame芝麻</h4>
	            <div class="ui-dialog-item">
	                <div class="ui-img">
	                    <span style="background-image:url(http://placeholder.qiniudn.com/140x140)"></span>
	                </div>
	                <div class="ui-dialog-info">
	                    <h5 class="ui-nowrap">这是标题，加ui-nowrap可以超出长度截断</h5>
	                    <p class="ui-nowrap">这是内容，加ui-nowrap可以超出长度截断</p>
	                    <span class="ui-nowrap">应用 开眼</span>
	                </div>
	            </div>
	        </div>
	        <div class="ui-dialog-ft">
	            <button type="button" data-role="button">取消</button>
	            <button type="button" data-role="button">确定</button>
	        </div>
	    </div>
	</div>
{% endexample %}

<!-- ## Examples -->
## 4.运营提示(运营图展示类)

{% example html %}
	<div class="ui-dialog ui-dialog-operate">
	    <div class="ui-dialog-cnt">
	        <div class="ui-dialog-hd">
	            <div class="ui-img">
	                <span style="background-image:url(http://placeholder.qiniudn.com/640x300)"></span>
	            </div>
	        </div>
	        <div class="ui-dialog-bd">
	            <p>按钮颜色根据运营氛围需要自行重置！</p>
	        </div>
	        <div class="ui-dialog-ft">
	            <button type="button" data-role="button" class="ui-btn">查看详情</button>
	            <button type="button" data-role="button" class="ui-btn">下个任务</button>
	        </div>
	        <i class="ui-dialog-close" data-role="button"></i>
	    </div>              
	</div>
{% endexample %}

<!-- ## Examples -->
## 5.运营提示(图标展示类)

{% example html %}
	<div class="ui-dialog ui-dialog-operate ui-dialog-operate-icon">
	    <div class="ui-dialog-cnt">
	        <div class="ui-dialog-hd">
	            <div class="ui-img">
	                <span style="background-image:url(http://placeholder.qiniudn.com/420x220)"></span>
	            </div>
	        </div>
	        <div class="ui-dialog-bd">
	            <h3>恭喜你获得10个专属福袋！</h3>
	        </div>
	        <div class="ui-dialog-ft">
	            <button class="ui-btn-lg">发福袋</button>
	        </div>
	        <i class="ui-dialog-close" data-role="button"></i>
	    </div>              
	</div>
{% endexample %}

## 1.信息流

{% example html %}
	<div class="ui-feeds">
        <ul>
            <li>
                <img src="http://119.29.8.64/vipstyle/mobile/client/cartoon/v2/pic/community/item1.jpg" alt="">
            </li>
        </ul>
    </div>
{% endexample %}



## 1.通用设置类输入框:

{% example html %} 
	<div class="ui-form ui-border-t">
	    <form action="#">
	        <div class="ui-form-item ui-border-b">
	            <label>
	                列表标题
	            </label>
	            <input type="text" placeholder="18位身份证号码" />
	            <a href="#" class="ui-icon-close">
	            </a>
	        </div>
	        <div class="ui-form-item ui-form-item-link ui-border-b">
	            <label>
	                列表标题
	            </label>
	        </div>
	        <div class="ui-form-item ui-form-item-link ui-border-b">
	            <label>
	                标题
	            </label>
	        </div>
	        <div class="ui-btn-wrap">
	            <button class="ui-btn-lg ui-btn-primary">
	                确定
	            </button>
	        </div>
	    </form>
	</div>
{% endexample %}


<!-- ## Examples -->
## 2.强引导类输入框

{% example html %}
<div class="demo-block">
    <section class="ui-input-wrap ui-border-t">
        <div class="ui-input ui-border-radius">
            <input type="text" name="" value="" placeholder="我也说一句...">
        </div>
        <button class="ui-btn">评论</button>
    </section>
    <section class="ui-input-wrap ui-border-t">
        <div class="ui-input ui-border-radius ui-input-text">
            <input type="text" name="" value="" placeholder="我也说一句...">
        </div>
    </section>
 </div>
{% endexample %}


## 3.表单开关项
{% example html %}
<form action="#">
    <div class="ui-form-item ui-form-item-switch ui-border-b">
        <p>
            对附近的人可见
        </p>
        <label class="ui-switch">
            <input type="checkbox" />
        </label>
    </div>
</form>
{% endexample %}

## 4.表单单选项
{% example html %}
<form action="#">
    <div class="ui-form-item ui-form-item-radio ui-border-b">
        <label class="ui-radio" for="radio">
            <input type="radio" name="radio" />
        </label>
        <p>表单中用于单选操作</p>
    </div>
</form>
{% endexample %}

## 5.表单多选项,普通列表中多选项
{% example html %}
<form action="#">
    <div class="ui-form-item ui-form-item-checkbox ui-border-b">
        <label class="ui-checkbox">
            <input type="checkbox" />
        </label>
        <p>表单中用于多选操作</p>
    </div>
</form>
{% endexample %}

## 6.多选框
{% example html %}
<div class="demo-block">
    <p> 
        <label class="ui-checkbox-s">
            <input type="checkbox" name="checkbox" checked="" />
        </label>
         我已阅读并同意
    </p>
</div>
{% endexample %}

## 7.普通列表中单选项
{% example html %}
<ul class="ui-list ui-list-text ui-list-radio ui-border-tb">
    <li class="ui-border-t">
        <label class="ui-radio" for="radio">
            <input type="radio" name="radio" />
        </label>
        <p>普通列表中用于单选操作</p>
    </li>
    <li class="ui-border-t">
        <label class="ui-radio" for="radio">
            <input type="radio" checked="" name="radio" />
        </label>
        <p>普通列表中用于单选操作</p>
    </li>
</ul>
{% endexample %}

## 1.网格(float网格适合多行)

{% example html %}
	<ul class="ui-row">
        <li class="ui-col ui-col-50">50</li>
        <li class="ui-col ui-col-50">50</li>
        <li class="ui-col ui-col-25">25</li>
        <li class="ui-col ui-col-75">75</li>
        <li class="ui-col ui-col-33">33</li>
        <li class="ui-col ui-col-67">67</li>
        <li class="ui-col ui-col-20">20</li>
        <li class="ui-col ui-col-80">80</li>
        <li class="ui-col ui-col-10">10</li>
        <li class="ui-col ui-col-90">90</li>
    </ul>
{% endexample %}

<!-- ## Examples -->
## 2.flex网格

{% example html %}
	<div class="ui-row-flex ui-whitespace">
        <div class="ui-col ui-col">平均分</div>
        <div class="ui-col ui-col">平均分</div>
        <div class="ui-col ui-col">平均分</div>
        <div class="ui-col ui-col">平均分</div>
    </div>
    <div class="ui-row-flex ui-whitespace">
        <div class="ui-col ui-col-2">2/3</div>
        <div class="ui-col">1/3</div>
    </div>
    <div class="ui-row-flex ui-whitespace">
        <div class="ui-col ui-col-3">3/4</div>
        <div class="ui-col">1/4</div>
    </div>
    <div class="ui-row-flex ui-whitespace">
        <div class="ui-col ui-col-4">4/5</div>
        <div class="ui-col">1/5</div>
    </div>
    <div class="ui-row-flex ui-whitespace">
        <div class="ui-col ui-col-3">3/5</div>
        <div class="ui-col ui-col-2">2/5</div>
    </div>
{% endexample %}

<!-- ## Examples -->
## 3.竖排flex网格

{% example html %}
	<div class="ui-row-flex ui-whitespace ui-row-flex-ver">
        <div class="ui-col">1/2</div>
        <div class="ui-col">1/2</div>
    </div>
{% endexample %}

<!-- ## Examples -->
## 4.三列网格(无交界线)

{% example html %}
	<div class="ui-grid ui-grid-trisect">
              <ul class="ui-border-b">
                  <li>
                      <div class="ui-img-vertical">
                          <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
                      </div>
                      <div class="ui-grid-info">
                        <h4>高尔夫<span>2.3M</span></h4>
                        <p>辅助信息</p>
                      </div>
                      <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
                  </li>
                  <li>
                      <div class="ui-img-vertical">
                          <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
                      </div>
                      <div class="ui-grid-info">
                        <h4>高尔夫<span>2.3M</span></h4>
                        <p>辅助信息</p>
                      </div>
                      <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
                  </li>
                  <li>
                      <div class="ui-img-vertical">
                          <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
                      </div>
                      <div class="ui-grid-info">
                        <h4>高尔夫<span>2.3M</span></h4>
                        <p>辅助信息</p>
                      </div>
                      <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
                  </li>
                  <li>
                      <div class="ui-img-vertical">
                          <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
                      </div>
                      <div class="ui-grid-info">
                        <h4>高尔夫<span>2.3M</span></h4>
                        <p>辅助信息</p>
                      </div>
                      <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
                  </li>
              </ul>
          </div>
{% endexample %}

<!-- ## Examples -->
## 5.三列网格（有交界线）

{% example html %}
	<div class="ui-grid ui-grid-trisect">
      <ul class="ui-border-b">
          <li>
              <div class="ui-img-vertical">
                  <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
              </div>
              <div class="ui-grid-info ui-border-r">
                <h4>高尔夫<span>2.3M</span></h4>
                <p>辅助信息</p>
              </div>
              <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
          </li>
          <li>
              <div class="ui-img-vertical">
                  <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
              </div>
              <div class="ui-grid-info ui-border-r">
                <h4>高尔夫<span>2.3M</span></h4>
                <p>辅助信息</p>
              </div>
              <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
          </li>
          <li>
              <div class="ui-img-vertical">
                  <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
              </div>
              <div class="ui-grid-info ui-border-r">
                <h4>高尔夫<span>2.3M</span></h4>
                <p>辅助信息</p>
              </div>
              <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
          </li>
          <li>
              <div class="ui-img-vertical">
                  <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
              </div>
              <div class="ui-grid-info ui-border-r">
                <h4>高尔夫<span>2.3M</span></h4>
                <p>辅助信息</p>
              </div>
              <!-- <button class="ui-btn-s ui-btn-progress">免费</button> -->
          </li>
      </ul>
  </div>
{% endexample %}

<!-- ## Examples -->
## 6.两列网格

{% example html %}
	<div class="ui-grid ui-grid-bisect">
                <ul>
                    <li>
                        <div class="ui-img-horizontal">
                            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
                        </div>
                    </li>
                    <li>
                        <div class="ui-img-horizontal">
                            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
                        </div>
                    </li>
                    <li>
                        <div class="ui-img-horizontal">
                            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
                        </div>
                    </li>
                    <li>
                        <div class="ui-img-horizontal">
                            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
                        </div>
                    </li>
                </ul>
          </div>
{% endexample %}

<!-- ## Examples -->
## 7.两列文字网格

{% example html %}
	<div class="ui-grid ui-grid-bisect">
            <ul>
                <li>
                    <div class="ui-img-horizontal">
                        <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
                    </div>
                    <div class="ui-grid-info ui-border-r">
                      <h4>主要信息</h4>
                      <p>辅助信息</p>
                    </div>
                </li>
                <li>
                    <div class="ui-img-horizontal">
                        <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
                    </div>
                    <div class="ui-grid-info ui-border-r">
                      <h4>主要信息</h4>
                      <p>辅助信息</p>
                    </div>
                </li>
                <li>
                    <div class="ui-img">
                        <span style="background-image:url(http://placeholder.qiniudn.com/290x290)"></span>
                    </div>
                    <div class="ui-grid-info ui-border-r">
                      <h4>主要信息</h4>
                      <p>辅助信息</p>
                    </div>
                </li>
                <li>
                    <div class="ui-img">
                        <span style="background-image:url(http://placeholder.qiniudn.com/290x290)"></span>
                    </div>
                    <div class="ui-grid-info">
                      <h4>主要信息</h4>
                      <p>辅助信息</p>
                    </div>
                </li>
            </ul>
          </div>
{% endexample %}

<!-- ## Examples -->
## 8.banner位

{% example html %}
<div class="ui-img-banner">
        <span style="background-image:url(http://placeholder.qiniudn.com/750x550)"></span>
      </div>
{% endexample %}

<!-- ## Examples -->
## 9.cover位

{% example html %}
<div class="ui-img-cover">
          <span style="background-image:url(http://placeholder.qiniudn.com/750x232)"></span>
        </div>
{% endexample %}

<!-- ## Examples -->
## 10.2/3横排图标网格（两列）

{% example html %}
<div class="ui-grid-icon ui-grid-icon-horizontal">
          <ul>
            <li>
              <div class="ui-img-icon">
                <span style="background-image:url(http://placeholder.qiniudn.com/80x80)"></span>
              </div>
                <h4>标题</h4>
            </li>
            <li>
              <div class="ui-img-icon">
                <span style="background-image:url(http://placeholder.qiniudn.com/80x80)"></span>
              </div>
             <h4>标题</h4>
            </li>
          </ul>
        </div>
{% endexample %}

<!-- ## Examples -->
## 11.2/3横排图标网格（三列）

{% example html %}
<div class="ui-grid-icon ">
          <ul>
              <li>
                <div class="ui-img-icon">
                  <span style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                </div>
                <h5>标题</h5>
                <p>副标题</p>
              </li>
              <li>
                <div class="ui-img-icon">
                  <span style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                </div>
                <h5>标题</h5>
                <p>副标题</p>
              </li>
              <li>
                <div class="ui-img-icon">
                  <span style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                </div>
                <h5>标题</h5>
                <p>副标题</p>
              </li>
          </ul>
        </div>
{% endexample %}

<!-- ## Examples -->
## 1.单行列表（纯文字）

{% example html %}
	  <ul class="ui-list ui-list-one ui-list-link ui-border-tb">
        <li class="ui-border-t ui-list-single-font">
            <div class="ui-list-info">
                <h4 class="ui-nowrap">性别</h4>
                <div class="ui-txt-info">男</div>
            </div>
        </li>
        <li class="ui-border-t ui-list-single-font">
            <div class="ui-list-info">
                <h4 class="ui-nowrap">生日</h4>
                <div class="ui-reddot ui-reddot-static"></div>
            </div>
        </li>
   </ul>
{% endexample %}

<!-- ## Examples -->
## 2.单行小图

{% example html %}
	 <ul class="ui-list ui-list-link ui-border-tb">
                <li class="ui-border-t active">
                    <div class="ui-list-small">
                        <span style="background-image:url(http://placeholder.qiniudn.com/60x60)"></span>
                    </div>
                    <div class="ui-list-info">
                        <h4 class="ui-nowrap">ui-list-thumb缩略图</h4>
                    </div>
                </li>
                <li class="ui-border-t">
                    <div class="ui-list-small">
                        <span style="background-image:url(http://placeholder.qiniudn.com/60x60)"></span>
                    </div>
                    <div class="ui-list-info">
                        <h4 class="ui-nowrap">ui-list-thumb-s缩略小图</h4>
                    </div>
                </li>
                <li class="ui-border-t">
                    <div class="ui-list-icon ui-avatar">
                        <span style="background-image:url(http://placeholder.qiniudn.com/80x80)"></span>
                    </div>
                    <div class="ui-list-info">
                        <h4 class="ui-nowrap">ui-list-icon icon图</h4>
                    </div>
                </li>
            </ul>
{% endexample %}

<!-- ## Examples -->
## 3.图文单行列表

{% example html %}
	   <ul class="ui-list ui-list-one ui-list-link ui-border-tb">
                <li class="ui-border-t">
                    <div class="ui-list-thumb">
                        <span style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                    </div>
                    <div class="ui-list-info">
                        <h4 class="ui-nowrap">性别</h4>
                        <div class="ui-txt-info">男</div>
                    </div>
                </li>
                <li class="ui-border-t">
                    <div class="ui-list-thumb">
                        <span style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                    </div>
                    <div class="ui-list-info">
                        <h4 class="ui-nowrap">生日</h4>
                        <div class="ui-reddot ui-reddot-static"></div>
                    </div>
                </li>
            </ul>
{% endexample %}

<!-- ## Examples -->
## 4.列表带头像

{% example html %}
	       <ul class="ui-list ui-list-link ui-border-tb">
                <li>
                    <div class="ui-avatar">
                        <span style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                    </div>
                    <div class="ui-list-info ui-border-t">
                        <h4 class="ui-nowrap">这是标题，加ui-nowrap可以超出长度截断</h4>
                    </div>
                </li>
                <li>
                    <div class="ui-avatar">
                        <span  style="background-image:url(http://placeholder.qiniudn.com/100x100)"></span>
                    </div>
                    <div class="ui-list-info ui-border-t">
                        <h4 class="ui-nowrap">这是标题，加ui-nowrap可以超出长度截断</h4>
                        <p class="ui-nowrap">这是内容，加ui-nowrap可以超出长度截断</p>
                    </div>
                </li>
            </ul>
{% endexample %}

<!-- ## Examples -->
## 5.列表带正方形

{% example html %}
	<ul class="ui-list ui-border-tb ui-list-square">
        <li>
            <div class="ui-square">
                <span style="background-image:url(http://placeholder.qiniudn.com/144x144)"></span>
            </div>
            <div class="ui-list-info ui-border-t">
                <h4 class="ui-nowrap">这是标题，加ui-nowrap可以超出长度截断</h4>
                <p class="ui-nowrap">这是内容，加ui-nowrap可以超出长度截断</p>
            </div>
        </li>
        <li>
            <div class="ui-square">
                <span  style="background-image:url(http://placeholder.qiniudn.com/144x144);"></span>
            </div>
            <div class="ui-list-info ui-border-t">
                <h4 class="ui-nowrap">这是标题，加ui-nowrap可以超出长度截断</h4>
                <p class="ui-nowrap">这是内容，加ui-nowrap可以超出长度截断</p>
            </div>
        </li>
    </ul>
{% endexample %}

<!-- ## Examples -->
## 6.列表带长方形

{% example html %}
    <ul class="ui-list ui-border-tb">
        <li>
            <div class="ui-list-img ui-list-img-vertical">
                <span style="background-image:url(http://placeholder.qiniudn.com/134x94)"></span>
            </div>
            <div class="ui-list-info ui-border-t">
                <h4 class="ui-nowrap">这是标题，加ui-nowrap可以超出长度截断</h4>
                <p class="ui-nowrap">这是内容，加ui-nowrap可以超出长度截断</p>
            </div>
        </li>
        <li>
            <div class="ui-list-img ui-list-img-vertical">
                <span style="background-image:url(http://placeholder.qiniudn.com/134x94)"></span>
            </div>
            <div class="ui-list-info ui-border-t">
                <h4>标题标题标题标题标题标题标题标题标题标题标题</h4>
            </div>
        </li>
    </ul>
{% endexample %}

<!-- ## Examples -->
## 1.局部加载中

{% example html %}
	<div class="ui-loading-wrap">
        <p>正在加载中...</p>
        <i class="ui-loading"></i>
    </div>
{% endexample %}

<!-- ## Examples -->
## 2.页面加载中

{% example html %}
	<div class="ui-loading-block show">
	    <div class="ui-loading-cnt">
	        <i class="ui-loading-bright"></i>
	        <p>正在加载中...</p>
	    </div>
	</div>
{% endexample %}


## 1.通知

{% example html %}
	<section class="ui-notice">
	    <i></i>
	    <p>请检查网络</p>
	    <div class="ui-notice-btn">
	        <button class="ui-btn-primary ui-btn-lg">按钮</button>
	    </div>
	</section>
{% endexample %}

<!-- ## Examples -->
## 1.默认面板

{% example html %}
	<section class="ui-panel ui-grid ui-grid-trisect">
    <h2 class="ui-arrowlink">猜你喜欢<span class="ui-panel-subtitle">1328条</span></h2>
    <ul>
        <li>
            <div class="ui-img-vertical">
                <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
            </div>
            <div class="ui-grid-info ui-border-r">
                <h4 class="ui-nowrap-multi">我是主标题</h4>
                <p class="ui-nowrap">这里是副标题</p>
            </div>
        </li>
        <li>
            <div class="ui-img-vertical">
                <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
            </div>
            <div class="ui-grid-info ui-border-r">
                <h4 class="ui-nowrap-multi">我是主标题</h4>
                <p class="ui-nowrap">这里是副标题</p>
            </div>
        </li>
        <li>
            <div class="ui-img-vertical">
                <span style="background-image:url(http://placeholder.qiniudn.com/190x284)"></span>
            </div>
            <div class="ui-grid-info ui-border-r">
                <h4 class="ui-nowrap-multi">我是主标题</h4>
                <p class="ui-nowrap">这里是副标题</p>
            </div>
        </li>
    </ul>
    <div class="ui-panel-more ui-border-tb">
        <span class="ui-arrowlink">查看全部</span>
    </div>
</section>
{% endexample %}

<!-- ## Examples -->
## 2.面板（ui-panel-center居中）

{% example html %}
	<section class="ui-panel ui-panel-center ui-border-tb">
     <h2 class="ui-arrowlink"><span>标题文字</span><span class="ui-panel-title-tips">分类更多</span></h2>
</section>
{% endexample %}

<!-- ## Examples -->
## 3.面板（ui-panel-center-multi居中两行）

{% example html %}
	<section class="ui-panel ui-panel-center-multi ui-border-tb">
	    <h2 class="ui-arrowlink"><span>标题文字</span><span class="ui-panel-subtitle">副标题文字</span><span class="ui-panel-title-tips">分类更多</span></h2>
	</section>
{% endexample %}


<!-- ## Examples -->
## 1.进度条

{% example html %}
	<div class="ui-progress">
         <span style="width:50%"></span>
 </div>
{% endexample %}

<!-- ## Examples -->
## 1.图片上进度条

{% example html %}
	<ul class="ui-grid-halve">
    <li>
        <div class="ui-grid-halve-img">
            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
            <div class="ui-progress">
                <span style="width:50%"></span>
            </div>
        </div>
    </li>
    <li>
        <div class="ui-grid-halve-img">
            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
        </div>
    </li>
</ul>
{% endexample %}

!-- ## Examples -->
## 1.搜索栏

{% example html %}
	<div  class="ui-searchbar-wrap ui-border-b">
    <div class="ui-searchbar ui-border-radius">
        <i class="ui-icon-search"></i>
        <div class="ui-searchbar-text">搜索号码（2-10位）</div>
        <div class="ui-searchbar-input"><input value="" type="tel" placeholder="搜索号码（2-10位）" autocapitalize="off"></div>
        <i class="ui-icon-close"></i>
    </div>
    <button class="ui-searchbar-cancel">取消</button>
</div>
{% endexample %}



<!-- ## Examples -->
## 1.红色角标:

{% example html %}
<ul class="ui-grid-halve">
    <li>
        <div class="ui-grid-halve-img" style="overflow:hidden;">
            <i class="ui-subscript ui-subscript-red">最新</i>
            <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
        </div>
    </li>
</ul>
{% endexample %}

<!-- ## Examples -->
## 2.橙色角标:

{% example html %}
<ul class="ui-grid-halve">
  <li>
      <div class="ui-grid-halve-img" style="overflow:hidden;">
          <i class="ui-subscript ui-subscript-orange">活动</i>
          <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
      </div>
  </li>
</ul>
{% endexample %}

<!-- ## Examples -->
## 3.绿色角标:

{% example html %}
<ul class="ui-grid-halve">
  <li>
      <div class="ui-grid-halve-img" style="overflow:hidden;">
          <i class="ui-subscript ui-subscript-green">限免</i>
          <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
      </div>
  </li>
</ul>
{% endexample %}

<!-- ## Examples -->
## 4.蓝色角标:

{% example html %}
<ul class="ui-grid-halve">
  <li>
      <div class="ui-grid-halve-img" style="overflow:hidden;">
          <i class="ui-subscript ui-subscript-blue">免费</i>
          <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
      </div>
  </li>
</ul>
{% endexample %}

<!-- ## Examples -->
## 5.三个字角标:

{% example html %}
<ul class="ui-grid-halve">
  <li>
      <div class="ui-grid-halve-img" style="overflow:hidden;">
          <i class="ui-subscript ui-subscript-red ui-subscript-trisection">小表情</i>
          <span style="background-image:url(http://placeholder.qiniudn.com/290x160)"></span>
      </div>
  </li>
</ul>
{% endexample %}


<!-- ## Examples -->
## 1.两个Tab:

{% example html %}
<div class="ui-tab ">
    <ul class="ui-tab-nav ui-border-b ">
        <li class="current"><span>热门</span></li>
        <li><span>热门</span></li>
    </ul>
    <ul class="ui-tab-content" style="width:200%">
        <li>内容1</li>
        <li>内容2</li>
    </ul>
</div>
{% endexample %}

<!-- ## Examples -->
## 2.三个Tab:

{% example html %}
<div class="ui-tab">
    <ul class="ui-tab-nav ui-border-b">
        <li class="current"><span>热门直播类</span></li>
        <li><span>热门直播类</span></li>
        <li><span>热门直播类</span></li>
    </ul>
    <ul class="ui-tab-content" style="width:300%">
        <li>内容1</li>
        <li>内容2</li>
        <li>内容2</li>
    </ul>
</div>
{% endexample %}

<!-- ## Examples -->
## 3.四个Tab:

{% example html %}
<div class="ui-tab">
    <ul class="ui-tab-nav ui-border-b">
        <li class="current"><span>热门直播类</span></li>
        <li><span>热门直播类</span></li>
        <li><span>热门直播类</span></li>
        <li><span>热门直播类</span></li>
    </ul>
    <ul class="ui-tab-content" style="width:400%">
        <li>内容1</li>
        <li>内容2</li>
        <li>内容3</li>
        <li>内容4</li>
    </ul>
</div>
{% endexample %}
