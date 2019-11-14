react-baidu-map
---

这是一个基于 React 封装的百度地图组件。帮助你轻松的接入地图到 React 项目中。

> 不依赖 uiw 组件库

## 安装

```bash
npm install @uiw/react-baidu-map --save
```

## 使用

<!--DemoStart,bgWhite,codePen--> 
```jsx
import { Map, APILoader } from '@uiw/react-baidu-map';

const Demo = () => (
  <div style={{ width: '100%', height: '300px' }}>
    <APILoader akay="GTrnXa5hwXGwgQnTBG28SHBubErMKm3f">
      <Map />
    </APILoader>
  </div>
);
ReactDOM.render(<Demo />, _mount_);
```
<!--End-->

## 组件 

- [`<Map>`](src/map/README.md)

## 开发

```bash
npm install # 安装依赖
npm run watch # Listen compile .ts files.
npm run build # compile .ts files.

npm run start

npm run doc:dev # 文档网站运行
```
