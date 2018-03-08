<h2>Vue.js 2.4.4版本，源码解读</h2>

<a style="text-decoration: underline;" href="https://github.com/terribleness/vue-read/issues/2" target="_blank"><h3>Vue运行时---第一步扩展实例方法（链接）</h3></a>
<p>Vue扩展实例方法流程为：</p>
<p>1、	定义function Vue()</p>
<p>2、	initMixin扩展vm._init</p>
<p>3、	stateMixin扩展vm.$data、vm.$props、vm.$set、vm.$delete、vm.$watch</p>
<p>4、	eventsMixin扩展vm.$on、vm.$once、vm.$off、vm.$emit</p>
<p>5、	lifecycleMixin扩展vm._update、wm.$forceUpdate、vm.$destroy</p>
<p>6、	renderMixin扩展vm.$nextTick、vm._render和一些工具方法</p>
