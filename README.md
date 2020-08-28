# TabBar
## 说明

下载依赖: 

```bash
npm install prop-types --save // 对传入的props进行检查
npm install --save styled-components // 样式
```

注: 此组件tabs有默认值

可根据需要传入想要的值(tabs 要是一个数组)

```js
// 在需要的地方放引入
<Tab tabs={[
          { id: 5, title: "React" },
          { id: 6, title: "Vue" },
          { id: 7, title: "Angular" },
        ]}
        initPage={3}
      >
	<div className="demo">移动端适配 demo React</div>
	<div className="demo">移动端适配 demo Vue</div>
	<div className="demo">移动端适配 demo Angular</div>
</Tab>
```

