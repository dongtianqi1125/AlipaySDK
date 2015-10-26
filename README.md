AlipaySDK
=========

[Alipay SDK](https://b.alipay.com/order/productDetail.htm?productId=2013080604609654&tabId=4#ps-tabinfo-hash)

[支付宝文档](http://doc.open.alipay.com/doc2/detail?spm=0.0.0.0.BPSDYG&treeId=59&articleId=103660&docType=1)

支付宝移动支付 SDK 标准版 from 2.0

由于不太经常关注更新，如果发现有新版更新欢迎PR。Thx

> TIPS:
> 
>  iOS 9 出现支付时不能打开支付宝app反而调用 webview 的情况（支付宝app已安装），请在 `info.plist` 文件的 `LSApplicationQueriesSchemes` key 下增加 `alipay` 和 `alipayshare` 两个值。


####payOrder:fromScheme:callback: 接口的回调结果

- 6001 取消支付
