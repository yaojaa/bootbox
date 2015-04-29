# bootbox
javascript modal  for bootstrap

e.g. 
~<code>~
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
    
~</code>~

#see the demo
http://yaojaa.github.io/bootbox/demo.html
