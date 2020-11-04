react-native link @ant-design/icons-react-native

## 安装依赖



### `ant-design`

```sh
# 最好使用npm 不要用yarn
npm install @ant-design/react-native
npm install @ant-design/icons-react-native
# 链接字体图标
react-native link @ant-design/icons-react-native
```



安装依赖后执行

```shell
react-native link @ant-design/icons-react-native
react-native link @react-native-community/async-storage
```



### 直接完成链接

> 彻底解决 `react-native link` 链接失败的问题

```shell
npx react-native link
# 再重新安装
npm run android
```



### 清空缓存启动

```shell
npm start --clearCache
```



### 按需加载

```sh
npm install --save-dev  babel-plugin-import
```





### 热更新

```sh
yarn add react-native-update 
react-native link react-native-update
```

