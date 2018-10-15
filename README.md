# release-npm-module
Introduce how to release a Vue2.0 frontend module to Npm . 介绍如何发布Vue前端项目模块到NPM中央仓库中

## 操作步骤

* 创建npm账号

	npm add user

	enter your name

	enter your password

	enter your email

	after register success, you can login your account here : https://www.npmjs.com/

* 验证邮箱

    创建账号后，npm会发送一封验证邮件到你的邮箱中，验证后激活

* 发布项目

    执行命令

      npm publish

    发布成功后，将会在邮箱中收到通知

## 使用

* 下载依赖

    npm insta ll --save release-npm-module

* 配置使用

  js:

    import hello from 'release-npm-module'

    components: {
        hello
    },

  html:

   	 <hello></hello>

