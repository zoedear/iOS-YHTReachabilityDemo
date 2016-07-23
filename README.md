# iOS-YHTReachabilityDemo
iOS开发中,用于监听网络状态,本人自己封装的方法

使用规则:
1.前提需要导入AFNetworking第三方库,下载网址:https://github.com/NSLog-YuHaitao/iOS-AFNetworking
2.将YHTReachability文件夹拖入工程中;
3.最后一步,在你想要实现检测网络的地方导入头文件,然后进行类方法调用即可,只需要一句话即可;
[YHTReachability reachabilityChanged];
