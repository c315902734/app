//页面跳转函数
function goToPage(page){
         api.openWin({
                                        name: 'live',
                                        url: page,
                                        pageParam: {
                                            name: 'test'
                                        },
                                      animation:  {
                                        type:"push",                //动画类型（详见动画类型常量）
                                        subType:"from_right",       //动画子类型（详见动画子类型常量）
                                        duration:200                //动画过渡时间，默认300毫秒
                                    }

                                });
         }
function convertUrl(__siteUrl__,i){

 ret=__siteUrl__+i;

 return ret;

}

function  extAlert(msg,location){
         api.toast({
                    msg: msg,
                    duration:2000,
                    location:location
                        });

         }