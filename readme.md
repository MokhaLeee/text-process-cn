## text-process-cn (W.I.P)
参考 [textprocess pytools](https://github.com/StanHash/FE-PyTools) 实现的无需Parse即可直接导入文本的EA工具


## 编译方式
texts\TextBuildfile.txt保存有所有待烧录字串，语法同 [textprocess](https://feuniverse.us/t/fe8-text-code-reference/4880) 。但目前只支持```[N] [X]```两种标记。

安装完成python3后调用指令:
```python3 text-process-cn.py TextBuildfile.txt InstallTextData.event TextDefinition.txt```
即可生成用于烧录的```InstallTextData.event```。

## 烧录方法
将```InstallTextData.event```包含进自己的buildfile中即可完成。可参考 [FE8U-cn-Project](https://github.com/MokhaLeee/Proj-FE8Ucn-in-EA) 做烧录。

