# VueJs_Study
>一、VueJs学习记录——TODoList
>>【1】安装VueJs的开发环境，使用VueJs实现HelloWorld的Demo;<br>
>>【2】熟悉VueJs的各种指令，主要理解双向绑定和列表渲染的使用方法;<br>
>>【3】熟悉semanticui的基本元素用法，实现一个简单的输入和简单的表格;<br>
>>【4】使用vuejs+semanticui创建的ToDoList: [Demo源码](https://github.com/BIGBANGTAEYANG/VueJs_Study/tree/master/ToDoList);<br>
>>【实现效果如下：】<br>
>>(1)使用VueJs实现输入添加用户;<br>
>>(2)使用VueJs实现删除用户以及全部删除,删除时候出现弹出层model<br>
>>![](https://github.com/BIGBANGTAEYANG/VueJs_Study/blob/master/DemoImage/todolist.png)<br>
>二、VueJs学习记录——事件对象及事件修饰符
>>【1】在VueJs中的事件是使用 v-on:click/mouseover...="function的名字" 的形式来声明事件的,也可以使用简单的写法 @click/mouseover... 形式;<br>
>>【2】在事件中，存在事件对象 @click="show($event)",event 就是事件对象;在事件处理程序中调用 event.preventDefault() 或 event.stopPropagation() 是非常常见的需求。尽管我们可以在 methods 中轻松实现这点，但更好的方式是：methods 只有纯粹的数据逻辑，而不是去处理 DOM 事件细节<br>
>>【3】为了解决这个问题， Vue.js 为 v-on 提供了 事件修饰符。通过由点(.)表示的指令后缀来调用修饰符。如在事件demo1中,使用.stop阻止事件冒泡。[Demo源码]()<br>
