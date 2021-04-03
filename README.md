# 开发说明

1. **在带有8px的容器中进行开发** 因为开发的组件是作为content template, 引入之后有8px的padding,  

2. **@media 里面的样式要 ！important**， 因为 “编译” 后类里面的样式会变成 行内样式，@media里面的则不会

3. 主要是进行布局，各种padding，margin, 里面的内容不重要
