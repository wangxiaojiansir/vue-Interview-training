<!--
 * @Autor: 王小建
 * @Date: 2020-01-20 14:26:45
 * @Description: 
 * @LastEditTime : 2020-01-20 14:39:09
 * @LastEditors  : 王小建
 -->
## 1.v-if和v-for哪个优先级高？如果两个同时出现，应该怎么优化得到更好的性能？
***  
>v-for  优先级更高
```
   <ul>
        <li v-for="item in list" v-if="item.active">
                显示内容部分
        </li>
   </ul>
```
