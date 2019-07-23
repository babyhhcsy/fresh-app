> 使用vue-cli脚手架的时候，经常会碰到chromedriver安装卡壳。 
> 解决办法：设置源
```js
npm config set "chromedriver_cdnurl" "https://npm.taobao.org/mirrors/chromedriver"
```