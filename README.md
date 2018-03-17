# vuetest

> Some Vue practices

## first vue project
> A simple html game
demo:[vuepuzzle](http://dovahkiin.top/vue/puzzle/);
直接从``vue init webpack``里出来的配置文件打包会出错，网上搜似乎不少人都被这个坑了。需要把打包配置文件的build.assetsPublicPath的值改成``./``，一开始我还愚蠢的改dev.assetsPublicPath，改回开发环境又报错了，来回折腾几回才成功打包出来。
总之，第一个用了组件化开发，第一次成功webpack把文件打包出来了，めでたしめでたし🐸