## 原elementui官方地址
https://github.com/ElemeFE/element

## 运行过程遇到问题
1-使用npm i和yarn install安装依赖node-sass报错
  改用cnpm i解决
2-改写时老报书写格式有问题
  去除eslint
3-打包时报格式有问题
  去除dist命令行中'npm run eslint'
  
## 写在后面
此项目为本人从elementui官方git上fork的版本，具体改写内容有修改datepicker组件使其支持'yyyy-MM-dd HH'格式的format选择