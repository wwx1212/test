## 项目名称

前后端分离的通用快速初始化项目

## 开发

```bash
# 克隆项目
git clone git@git.boryou.com:yfb/web/frontend/proj-init-f.git

# 进入项目目录
cd proj-init-f

# 安装依赖
# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 http://localhost:8399

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```