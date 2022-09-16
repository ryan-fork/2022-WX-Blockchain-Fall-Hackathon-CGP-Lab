# 铸造NFT的中间件

- 图片上传中间件
- 在NFT.Storage上上传nft的元数据文件
- 在链上铸造NFT

### 运行

注意:监听的http端口在app.js最后一行配置

```bash
node app.js
#or
npm run start
```

### 访问客户端

```bash
curl http://localhost:17171
```

### 上传文件

```bash
curl -F 'file=@/home/wcc/my/blockchain/hackathon/2022-WX-Blockchain-Fall-Hackathon-CGP-Lab/Web3.CGP/app.js' http://127.0.0.1:17171/upload
```
