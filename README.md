
<!---

此README是从这些文件中的注释自动生成的:
iron-flex-layout.html

编辑这些文件，我们的readme bot将在这里复制它们！
编辑此文件，机器人将压缩您的更改 :)

男孩做一些处理的降价。 如果错误，请提交错误
事情! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/iron-flex-layout.svg?branch=master)](https://travis-ci.org/PolymerElements/iron-flex-layout)

_[Demo and API docs](https://elements.polymer-project.org/elements/iron-flex-layout)_


##&lt;iron-flex-layout&gt;

该 `<iron-flex-layout>` component provides simple ways to use
[CSS flexible box layout](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes),
also known as flexbox. This component provides two different ways to use flexbox:

1. [Layout classes](https://github.com/PolymerElements/iron-flex-layout/tree/master/iron-flex-layout-classes.html).
布局类样式表提供了一组简单的基于类的flexbox规则
让您直接在标记中指定布局属性。 您必须包括此文件
在每个需要使用它们的元素.

样品使用:

   <link rel="import" href="../iron-flex-layout/iron-flex-layout-classes.html">

   <style is="custom-style" include="iron-flex iron-flex-alignment"></style>

   <div class="layout horizontal layout-start">
     <div>横轴开始对齐</div>
   </div>

1. [自定义CSS混合](https://github.com/PolymerElements/iron-flex-layout/blob/master/iron-flex-layout.html).
mixin样式表包括可以在CSS规则中使用`@ apply`函数应用的自定义CSS混合.



请注意老 [/deep/ layout classes](https://github.com/PolymerElements/iron-flex-layout/tree/master/classes)
已弃用，不应使用。 继续使用布局属性
直接在标记中，请切换到使用新的 `dom-module`-based
[layout classes](https://github.com/PolymerElements/iron-flex-layout/tree/master/iron-flex-layout-classes.html).
Please note that the new version does not use `/deep/`, and therefore requires you
to import the `dom-modules` in every element that needs to use them.

A complete [guide](https://elements.polymer-project.org/guides/flex-layout) to `<iron-flex-layout>` is available.


