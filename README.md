# 5StarOneKey
根据JQ的代码修改而来。改成了我常用的以下几种打分方式：
{button:"Five Star", total:5, name:5, history:5, unique:5, location:5, safety:5},
{button:"555535", total:5, name:5, history:5, unique:5, location:3, safety:5},
{button:"555335", total:5, name:5, history:5, unique:3, location:3, safety:5},
{button:"553535", total:5, name:5, history:3, unique:5, location:3, safety:5},
{button:"553335", total:5, name:5, history:3, unique:3, location:3, safety:5},

使用教程
-------------
首先，浏览器安装了tampermonkey之类的userjs插件，然后点击
https://github.com/bigrice666/5StarOneKey/raw/master/5%20Star%20One%20Key.user.js
浏览器会弹出安装界面

不想用默认评分？
-------------
很容易。

照着这个写，别忘了后面的逗号，在源代码上直接改就行

{button:"553355", total:5, name:3, history:3, unique:3, location:5, safety:5},

↑按钮名称          ↑总分     ↑名字    ↑历史      ↑独一无二   ↑位置       ↑安全

插入/替换到buttons那个list里即可
