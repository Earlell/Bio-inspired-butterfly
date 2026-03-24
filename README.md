![Markdown标志](https://markdown-here.com/img/icon256.png "Logo")
 [Markdown语法]([https://www.example.com "Example的网站"](https://blog.csdn.net/cava_cxz/article/details/151992573?ops_request_misc=elastic_search_misc&request_id=ddf4fd094b0981c8e6df4fdb91745c16&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-151992573-null-null.142^v102^pc_search_result_base3&utm_term=markdown%E8%AF%AD%E6%B3%95%E5%A4%A7%E5%85%A8&spm=1018.2226.3001.4187))
 | 功能  | 语法            |
| --- | ------------- |
| 标题  | `# 标题`        |
| 粗体  | `**文字**`      |
| 斜体  | `*文字*`        |
| 删除线 | `~~文字~~`      |
| 链接  | `[文字](url)`   |
| 图片  | `![alt](url)` |
| 列表  | `- 项目`        |
| 代码  | `` `code` ``  |
| 代码块 | ` `           |
| 引用  | `> 引用`        |
| 分割线 | `---`         |


# 更新日志
## 2026年3月23日
1.  我把2.0（温和代码）进行了的修改，改成了四驱，目前代码没出现什么问题
     *主要的修改的地方有*
     + 增加了tim2,tim3的3，4通道
     - 把adc采样的引脚修改了(代码如下)
     ``` GPIO_InitStruct.Pin = GPIO_PIN_0|GPIO_PIN_1|GPIO_PIN_6|GPIO_PIN_7;//GPIO_PIN_0|GPIO_PIN_4|GPIO_PIN_6|GPIO_PIN_7;```
2. 2号空心杯电机好像出问题了
3. 在githib创建了一个仓库，把代码传了上去。


# 问题与总结
```markdown
# 小型锂电池（如 3.7V 70mAh）过放总结

## 🔋 什么是过放
过放是指电池电压低于安全下限（约 2.5V～3.0V），导致电池内部发生不可逆损伤。

## 🔌 过放后的表现

- 无法充电（完全没反应）  
- 充电后续航明显下降  
- 发热异常或鼓包（危险）  

## 💡 使用与保养建议

- 电量低于 20% 及时充电  
- 避免长时间完全没电存放  
- 长期不用保持 40%～60% 电量  
- 每月补电一次  


