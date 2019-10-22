# mock-server
方便在某些特殊情况下模拟接口数据

### 使用步骤
```
1.npm install
2.npm run mock //启动端口 5050
3.api地址写 http://localhost:5050/
```
### api.json
api.json主要是模拟接口返回的数据结构，mock data可以使用mockjs,随机生成数据。

### serve.js 
serve.js主要是读取api.json数据，找到符合的url，返回相应的数据

