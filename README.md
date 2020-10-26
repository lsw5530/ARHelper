# ARHelper
#项目简介
随着5G的不断部署和智能设备的发展，以及在疫情情况下暴露出的各种专家不能现场指导的问题，远程协助应用需求有极大的提升。在一些复杂的设备维修场景、紧急的医疗救助、远程教育教学等方面，普通的音视频远程指导已经不能满足需求，远程指导需要更加精确的定位和标记。
在这种需求下，我们这个项目在满足用户基础视音频的需求上，通过图像识别技术、SLAM定位技术，让设备识别周围环境进行空间定位，定位之后在远程指导过程中不需要预先放置识别物或者内置模型即可进行准确的标记和远程指导。
以此为基础对现有的远程协助进行技术升级和体验升级，解决当前远程视频协助过程中的“口舌之争”，在工业行业中设备维修的指导可以达到螺丝的级别；在医疗行业中可以进行精准的手术指导；在教育行业可以实时在画面中对学生作业进行批注等等，相信在需要远程协助的各行各业都会有新的体验和效果提升。

#主要创新点
本项目的出发点在于解决远程知道过程中指导不明确的问题，特别是一些比较专业的场景，可能需要点对点的进行指导，因此本项目主要创新点如下：
1、SLAM技术的应用，对环境进行即时、快速建模和定位，提高定位精度和指导准确度
2、AR定位和裁剪，在专家模式下，定点获取视频区域，进行点对点标注
3、5G以及实时音视频技术和通讯技术，通过专业云服务和算法，提高传输速率

#项目集成
1、声网视音频SDK
2、腾讯云游戏联机对战引擎 MGOBE
3、Vuforia
使用前须分别申请相应的授权，并填写到指定位置

#业务逻辑
1、软件采用Unity开发，支持跨平台应用
2、软件目前分为专家/工程师/游客等角色，以专家和工程师为主要适用对象，专家通过视频指导工程师进行运维、教学等各项操作
3、专家端包括创建会议、视音频基本操作、屏幕绘图、模型标注（待完善）、图片标注等功能；工程师端包括创建会议、视音频基本操作、环境识别、AR定位、专家模式切换等内容
4、演示在手机4G和PC有线的情况下，略有延迟；项目推广中将配合5G环境布设，有效降低延迟

团队介绍
春秋呆瓜团

ToDoLists
1、优化操作体验，增强软件操作性
2、各个使用者的角色和功能开发
3、SLAM的技术开发
