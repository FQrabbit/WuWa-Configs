# 鸣潮视频配置
Pure copy without any modification.  
纯搬运，如果你需要看最新配置，请访问[源项目](https://github.com/AlteriaX/WuWa-Configs)。  
其他使用说明可查看[nga帖子](https://g.nga.cn/read.php?tid=40329895)，这里就不再过多赘述。

根据您的显卡型号等级，可以大致确定你需要哪种配置：
| Config | NVIDIA                                                                            | AMD                                                                   | Intel                |
|--------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------|----------------------|
| 1      | RTX 4090, 4080, 4070, 3090, 3080 Ti, 3080, 3070 Ti                                | RX 7900 XTX/XT/GRE, 7800 XT, 7700 XT, 6950 XT, 6900 XT, 6800 XT, 6800 |                      |
| 2      | RTX 4060 Ti, 4060, 3070, 3060 Ti, 3060, 3050, 2080, 2070, 2060, GTX 1080 Ti, 1080 | RX 7600 XT, 6700 XT, 6700, 6650 XT, 6600 XT, 6600, 5700 XT, 5700      | A770, A750, A580     |
| 3      | GTX 1660 Ti, 1660 SUPER, 1660, 1650 SUPER, 1070, 1060 6GB                         | RX 6500 XT, 5600 XT, 5500 XT, 590, 580                                |                      |
| 4      | RTX 2050, GTX 1650, 1050 Ti, 1050                                                 | RX 6400, 580 2048SP, 570, 560, 780M, 680M                             | A380, A310, Arc iGPU |
| 5      | GT 1030, MX350/250/150                                                            | RX 550, Vega iGPU                                                     | Iris Xe              |

左边数字对应项目文件夹的 `Config1 Config2 Config3` ...以此类推。  
抄作业的朋友请按照实际需求更改参数嗷。 

---

以下是原项目的简单翻译:    
所有使用的命令值均与游戏默认值不同。  
项目里`Info`文件夹包含已测试过但不起作用或默认已启用/禁用的命令列表。  
项目里`Common`文件夹包含对 ``Scalability.ini`` 的调整，用于关闭后处理效果，例如：
```
Chromatic Abberation(色差)、Depth of Field(景深)、Film Grain(胶片颗粒)、Vignette(渐晕)
```
`Engine.ini`文件存放路径:  
Wegame:   
```
..WeGameApps\rail_apps\Wuthering Waves(2002137)\Client\Saved\Config\WindowsNoEditor
```   
官方:   
```
..Wuthering Waves\Wuthering Waves Game\Client\Saved\Config\WindowsNoEditor
```


# WuWa-Configs

## Configs require mod to apply properly now.

All commands used have different value from the game's default. 

For explanations and image comparisons visit my Reddit post: [Link](https://www.reddit.com/r/WutheringWaves/comments/1d07cku/ue4_engine_tweaks_to_improve_visuals_and_reduce/) | [Discord Server](https://discord.com/invite/JhtKDnu9MK)

Info folder contains list of commands that have been tested but does not work or already enabled/disabled by default.

Common folder contains tweaks for ``Scalability.ini`` to turn off post-processing effects such as:
```
Chromatic Abberation, Depth of Field, Film Grain, Vignette
```

Copy ``Engine.ini`` (choose one config) and ``Scalability.ini`` to this location: 
> ..Wuthering Waves\Wuthering Waves Game\Client\Saved\Config\WindowsNoEditor

Probably got the performance wrong for some but this should help to choose a config quickly.

| Config | NVIDIA                                                                            | AMD                                                                   | Intel                |
|--------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------|----------------------|
| 1      | RTX 4090, 4080, 4070, 3090, 3080 Ti, 3080, 3070 Ti                                | RX 7900 XTX/XT/GRE, 7800 XT, 7700 XT, 6950 XT, 6900 XT, 6800 XT, 6800 |                      |
| 2      | RTX 4060 Ti, 4060, 3070, 3060 Ti, 3060, 3050, 2080, 2070, 2060, GTX 1080 Ti, 1080 | RX 7600 XT, 6700 XT, 6700, 6650 XT, 6600 XT, 6600, 5700 XT, 5700      | A770, A750, A580     |
| 3      | GTX 1660 Ti, 1660 SUPER, 1660, 1650 SUPER, 1070, 1060 6GB                         | RX 6500 XT, 5600 XT, 5500 XT, 590, 580                                |                      |
| 4      | RTX 2050, GTX 1650, 1050 Ti, 1050                                                 | RX 6400, 580 2048SP, 570, 560, 780M, 680M                             | A380, A310, Arc iGPU |
| 5      | GT 1030, MX350/250/150                                                            | RX 550, Vega iGPU                                                     | Iris Xe              |

References: [UE4.27 Commands](https://framedsc.com/GeneralGuides/ue4_commands.htm), [UE4 Documentation](https://docs.unrealengine.com/4.27/en-US/), UE Forum

[<img src="https://i.imgur.com/yxCCgvy.png">](https://ko-fi.com/alteria/)
