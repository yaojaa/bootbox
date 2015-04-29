# bootbox  v0.1 

javascript modal  for bootstrap ，基于bootbox的增强扩展，简洁了语法。增加了成功\失败、警告、加载中、右下角弹窗等。
并定义了样式方案，如需修改直接改bootbox.css即可。


###调用方式
<pre>
 bootbox.success('Your String', callbackFn)
 
 bootbox.danger('Your String', callbackFn)
 
 bootbox.warning('Your String', callbackFn)
 
 bootbox.info('Your String', callbackFn,3000) //默认3秒后自动关闭 
 
 bootbox.loading('loading...',callbackFn)
 
 bbootbox.dialog({
        message: $("#myModal").html(),
        title: "注册新用户",
        className: "",
        buttons: {
            ok: {
                label: "立即注册",
                className: "btn-success",
                callback: function() {}
            },
            "cancel": {
                label: "取消",
                className: "btn-default",
                callback: function() {}
            }
        }
    });
    
</pre>

#see the demo
###写说明比较费劲 先自己看示例吧
http://yaojaa.github.io/bootbox/demo.html
