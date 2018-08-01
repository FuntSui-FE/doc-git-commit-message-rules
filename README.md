# :memo:git代码提交message规范
  
## 先来几个完整的例子
```
feat:新增自开奖页面

新增活动页面，但是产品还有需求遗漏，待完善
- 新增内容1
- 新增内容2
```

```
fix:活动页面设置渠道后,自动添加渠道文字类型判断错误
```

## 完整的commit message需包含三个部分：Header,Body;Header必填，其他可以省略！

```
<Header>

<Body>
```

## Header
Header包含两个部分：type,subject
```
<type>:<subject>
```
  
#### subject为对commit的简短描述  

#### type为7种类别：  
- feat:新功能(feature)
- fix:修复Bug  
- doc:文档
- style:格式化代码(在不影响代码功能的前提)
- refactor:重构代码
- test:添加测试用例
- chore:构建过程或者辅助工具变动  

## Body
body是对本次commit的详细描述。

用`- `和换行隔开每一项
