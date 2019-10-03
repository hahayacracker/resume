预览简历：https://resume.52bess.com/public/

### 使用方法

1. 安装Node.js环境：https://nodejs.org/
2. 安装git: https://git-scm.com/
3. 执行以下命令：

```
git clone https://github.com/bessyjl/resume.git
cd resume
npm install
npm run dev
```

### 部署方法

1. 编辑 config/index.js，修改第 10 行的 assetsPublicPath，值为 `项目名/public`。如果你没有修改项目名 resume，则可跳过此步骤。
2. 编译、上传

```
bash
npm run build
git add .
git commit -m "update"
git push
```

​	开启 GitHub Pages 功能, 或者把生成的目标文件`public/*`放在你的服务器上。是不是很像Hexo？😀

4，访问地址一般为：https://your-github-username.github.io/resume/public，如果部署在服务器上，地址就是你自己设置的那个。

### 更新

如果你clone时的时间，距离我上传有点长了，建议更新下依赖。
(不更新也能使用,但是GitHub可能会给你发送许多警告邮件！)

### 致谢

感谢原作者[Samuel Reed](https://github.com/strml)开源，和GitHub提供的托管服务！


