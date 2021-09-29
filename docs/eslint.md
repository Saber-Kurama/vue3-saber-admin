## eslint 的配置

https://www.breword.com/typicode-husky

### parser 解析
Espree

esprima

Babel-ESLint 

@typescript-eslint/parser

vue-eslint-parser

实际上，eslint使用espree（封装于Acorn）解析JS代码，如果希望eslint解析TS代码我们需要自行把eslint的解析器（Parser）设置为@typescript-eslint/parser并提供相应的插件支持@typescript-eslint/eslint-plugin（需要安装typescript模块）。

而babel使用的解析器@babel/parser（曾用名babylon，封装于Acorn）本身就支持JS和TS代码的解析。

https://messiahhh.github.io/blog/frontend/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%8C%96.html#%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6

### parserOptions 解析参数


https://dev.to/hxlnt/these-vs-code-extensions-help-you-fix-accessibility-and-compatibility-bugs-while-you-code-2196

https://levelup.gitconnected.com/set-up-a-vue-app-running-on-vite-e816247a24e2

https://www.digitalocean.com/community/tutorials/vuejs-vue-eslint-prettier

https://vite-rollup-plugins.patak.dev/

https://github.com/unjs