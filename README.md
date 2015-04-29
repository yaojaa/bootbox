# bootbox
javascript modal  for bootstrap 

e.g. 
<pre>
 bootbox.success('Your String', callbackFn)
 bootbox.danger('Your String', callbackFn)
 bootbox.warning('Your String', callbackFn)
 bootbox.info('Your String', callbackFn,3000) //3秒后自动关闭
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
