# webpack-knowledge
webpack的一些注意点

# <font color="#00ffff">Vue组件内使用jquery，并且jquery不被打包，jquery单独全局引用的配置</font>
<pre>
<code>
    externals: {
        jquery:{
          root: '$',
          commonjs: 'jquery',
          commonjs2: 'jquery',
          amd: 'jquery'
        }
    }
</code>
</pre>

