Icon 图标
用于展示 icon，组件名：uni-icons，代码块： uIcons。
可直接替换官方的ico

使用方式：

在 script 中引用组件
```
import uniIcons from "@/components/yangxiaochuang-icons/yangxiaochuang-icons.vue"
export default {
    components: {uniIcons}
}
```
在 template 中使用组件
```
<uni-icons type="contact" size="30"></uni-icons>
```
Icons 属性说明：

属性名|类型|默认值|说明
--|:--:|--:--|:
type|String|-|图标图案，参考示例
color|String|-|图标颜色
size|Number|24|图标大小（单位px）

Icons 事件说明： |事件名 |说明 | |click |点击 Icon 触发事件 |

安装后，在
```
components/yangxiaochuang-icons/yangxiaochuang-icons.vue
```
打开后可以看到具体的样式名和样式，建议直接覆盖官方的图标文件进行使用（新建项目选择uni-app示例，将该插件覆盖官方的图标文件即可使用官方示例进行预览，就不重复造轮子了）
注：如果你实在是新手到连覆盖文件都不会的话，可以留言请教别人，但请不要乱评论，尊重别人的劳动成果就是尊重你自己
