# 个人爱好

------

![](https://raw.githubusercontent.com/Parantric/picture-bed/main/202302282158720.png)

## :white_check_mark: cron表达式

### :white_check_mark: 圈x task 任务中使用 cron 表达式规范

#### :sunglasses: 5 位说明

> **\* \* \* \* \*  从左到右依次表示：分 时 日 月 星期**

#### :sunglasses: 6 位说明

> **\* \* \* \* \* \* 从左到右依次表示：秒 分 时 日 月 星期**

#### :heavy_check_mark: 简单示例

> ***/4 7-22/1 * * *    每天7-22点 每4分钟执行一次**

> **0 9,12,18 * * *      每天9点 12点 18点分别执行一次**

> **0 0-16/8 * * *        每天0点 8点 16点各一次**

> **0 * * * *                 每1小时执行一次**
