## About Yxk
    最简单的实现hello world的package

## 安装
    composer require yxk/hello
    
## 生成配置文件
     php artisan vendor:publish --provider="Yxk\Hello\HelloServiceProvider" 
     
## 调用方式
    $ret = Hello::sayHello();
    return $ret;
    //输出Hello China即调用成功
