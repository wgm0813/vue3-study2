# vue3-study2
vue3的进阶-脚手架、组件使用

1、创建vue项目，先安装脚手架，全局安装命令
npm install @vue/cli -g

2、升级版本命令
npm update @vue/cli -g

3、创建vue项目命令
vue create 项目名称

？Please pick a preset:选择预设
 Default([Vue 3]babel, eslint)
 Default([Vue 2]babel, eslint)
>Manually select features(手动选择)//此处我自己选择这个

？Check the features needed for your project:选择新特性
*Babel：对ES代码进行转换
 TypeScript：
 Progressive Web App (PWA) Support：项目是否支持PWA
 Router：路由
 Vuex：Vuex状态管理
 CSS Pre-processors：选择CSS预处理器
 Linter / Formatter：选择ESLint对代码进行格式化限制
 Unit Testing：单元测试
 E2E Testing：E2E测试

?Choose a version of Vue.js that you want to start the project with //选择Vue版本
 2.x
>3.x

? Where do you prefer placing config for Babel, ESLint, etc.? //是否将配置信息放到独立的文件中
>In dedicated config files //独立的文件
 In package.json

?Save this as a preset for future projects? //生成预设下一次直接新建项目选择同样的

?Pick the package manager to use when installing dependencies:(Use a keys)
 Use Yarn
 Use PNPM
*Use NPM