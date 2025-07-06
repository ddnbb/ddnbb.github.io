# Hexo Blog

这是一个使用Hexo构建的博客项目。Hexo是一个快速、简洁且高效的博客框架，支持Markdown语法，适合技术博客和个人博客。

## 项目结构

- **scaffolds/draft.md**: Hexo的草稿模板，用于创建新的草稿文章。
- **source/_posts/hello-world.md**: 示例文章，展示博客的基本结构和内容。
- **source/_data**: 存放数据文件的目录，可以在博客中引用。
- **themes/landscape**: 包含Hexo主题“landscape”的文件，定义了博客的外观和样式。
- **_config.yml**: Hexo的配置文件，包含博客的基本设置，如标题、描述、作者等。

## 使用说明

1. **安装Hexo**: 确保你已经安装了Node.js和npm，然后在项目根目录下运行以下命令安装Hexo：
   ```
   npm install hexo-cli -g
   ```

2. **初始化项目**: 在项目根目录下运行：
   ```
   hexo init
   ```

3. **生成静态文件**: 运行以下命令生成静态文件：
   ```
   hexo generate
   ```

4. **启动本地服务器**: 运行以下命令启动本地服务器：
   ```
   hexo server
   ```

5. **访问博客**: 打开浏览器，访问 `http://localhost:4000` 查看你的博客。

## 贡献

欢迎任何形式的贡献！如果你有建议或发现问题，请提交issue或pull request。