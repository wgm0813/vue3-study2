# vue3-study2
vue3的进阶-脚手架、组件使用

1、创建vue项目，先安装脚手架，全局安装命令
npm install @vue/cli -g

2、升级版本命令
npm update @vue/cli -g

3、创建vue项目命令 :打包基于webpack
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


文件夹介绍
1、public
项目中的一些资源

2、src
所有的源代码

3、.browserslistrc
设置目标浏览器

4、.gitignore
git的忽略文件

5、babel.config.js
babel的配置

6、jsonfig.json
VSCode编辑器识别，这样更好给出对应的提示

7、package.json
项目的管理文件

8、引用vue版本
默认Vue版本：runtime, vue-loader完成template的编译过程
vue.esm-bundler: runtime + compile，对template进行编译

9、vue文件style自己的作用域scoped:只在自己组件内部生效
<style scoped></style>

10、配置用户代码片段 （snippet-generator.app网站转换）
文件 -> 首选项 ->用户代码片段 -> 选择vue文件 -> 粘贴添加代码

VSCode插件:编辑器
vetur: vue2/vue3
volar: vue3


11、创建vue项目的第二种方式  ：此打包工具基于vite
(具体见03-vue-vite文件夹README文件解释)
npm init vue@latest 
1、安装一个本地工具：create-vue
2、使用create-vue创建一个vue项目

>Project name: >>03-vue-vite03-vue-vite
√ Add TypeScript? ... No / Yes
√ Add JSX Support? ... No / Yes
√ Add Vue Router for Single Page Application development? ... No / Yes
√ Add Pinia for state management? ... No / Yes
√ Add Vitest for Unit Testing? ... No / Yes
√ Add an End-to-End Testing Solution? » No
√ Add ESLint for code quality? ... No / Yes
默认是没有装依赖的

npm install