# 注意事项

* 看看效果：https://lhsaq2009.github.io/Github-Pages-Demo/

* 克隆本项目，快速开始吧，唯一需要做的就是下面这个

  * 推送 GitHub 后，手动操作

    远程仓库 -> Settings -> Pages -> Build and deployment：选择 GitHub Actions

* 其它备注

  * 解决构建后，GitHub Pages 访问静态文件 404

      ```shell
      vite.config.js -> defineConfig -> base: './'
      ```

  * GitHub Actions 构建脚本：.github/workflows/main.yml

  * Share Project on GitHub，不能是 private

