#### <script>标签用来放JavaScript语句

##### 1.直接将JavaScript代码放入<script>标签中

##### 2.通过src引用外部JavaScript文件

#### <template>

##### html中的`template`标签中的内容在页面中不会显示。但是在后台查看页面DOM结构存在`template`标签。这是因为template标签天生不可见，它设置了`display:none;`属性

#### <style scoped>

##### 在组件的`<style></style>`加上 `scoped`属性，可以让`<style></style>`里的样式只在当前组件生效

#### ＜div＞元素容器

##### div class 和style的区别

###### 1.class一般是定义在css(层叠样式表)文件里的，同类型的标签可以对css文件中的class进行复用

###### 2.class除了可以当作style集合使用以外，还可以使用纯css实现动画效果

###### 3.class定义时一般是针对某个标签类定义其对应的class，具有一定的针对行，比如"div.myClass{……}"而style一般是现定义现用，且不会复用，定义的时候不会有针对性，直接```style=“xxxxxx”````就完事了

###### 4.style和class同时对标签的某些属性进行了个性化时，style中的属性设置优先使用。













