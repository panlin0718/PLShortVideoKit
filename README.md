# 1 产品简介
七牛短视频 SDK，方便开发者快速实现短视频拍摄、剪辑、编辑、合成、分发功能。我们提供 80+ 功能供开发使用，申请 **0 元体验**可联系销售或[填写表单](https://jinshuju.net/f/IeOD89?ref=www.qiniu.com)获得产品试用权限。
# 2 多版本功能分布
短视频 SDK 主要区分基础版、进阶版、专业版 3 个版本，不同版本的功能区别见如下表格

| 功能                                                         | 子功能                                                       |         基础版          |         进阶版          |          专业版          |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :---------------------: | :---------------------: | :----------------------: |
| **用户交互界面**                                             | **提供了一套完整的UI交互源码，可复用或自定义**               |            ✓            |            ✓            |            ✓             |
| **视频拍摄录制**                                             | **摄像头采集**                                               |            ✓            |            ✓            |            ✓             |
|                                                              | **麦克风采集**                                               |            ✓            |            ✓            |            ✓             |
|                                                              | **视频采集参数定义**<br />*支持最高 1080P 拍摄，支持自定义视频采集源、采集画面的分辨率、采集画面的长宽比等参数* |            ✓            |            ✓            |            ✓             |
|                                                              | **音频采集参数定义**<br />*支持自定义音频采集源、音频格式、音频声道、音频采样率等参数* |            ✓            |            ✓            |            ✓             |
|                                                              | **视频编码参数定义**<br />*支持自定义编码视频的码率、帧率、分辨率、H.264 编码方式等参数* |            ✓            |            ✓            |            ✓             |
|                                                              | **音频编码参数定义**<br />*支持自定义编码音频的码率、采样率、声道数、AAC 编码方式等参数* |            ✓            |            ✓            |            ✓             |
|                                                              | **拍摄时长设置**<br />*支持设置实际拍摄过程中的最大、最小拍摄时长* |            ✓            |            ✓            |            ✓             |
|                                                              | **摄像头切换**<br />*支持切换前后摄像头进行拍摄*             |            ✓            |            ✓            |            ✓             |
|                                                              | **闪光灯设置**<br />*支持开关闪光灯用于拍摄时的补光*           |            ✓            |            ✓            |            ✓             |
|                                                              | **曝光调节**<br />*支持调整曝光度参数*                       |            ✓            |            ✓            |            ✓             |
|                                                              | **画面对焦**<br />*支持手动对焦和自动对焦*                   |            ✓            |            ✓            |            ✓             |
|                                                              | **焦距调节**<br />*支持手动调节画面焦距进行放大、缩小*       |            ✓            |            ✓            |            ✓             |
|                                                              | **画面镜像**<br />*支持设置是否镜像预览画面和编码画面*       |            ✓            |            ✓            |            ✓             |
|                                                              | **横屏拍摄**<br />*支持根据设备的方向自动确定竖屏、横屏拍摄* |            ✓            |            ✓            |            ✓             |
|                                                              | **分段拍摄**<br />*支持拍摄过程中实现连续多次拍摄、断点续拍、回删* |            ✓            |            ✓            |            ✓             |
|                                                              | **变速拍摄**<br />*支持设置拍摄时的快/慢速率，目前支持 5 种拍摄速率* |            ✗            |            ✓            |            ✓             |
|                                                              | **音频录制**<br />*支持纯音频录制*                             |            ✓            |            ✓            |            ✓             |
|                                                              | **音频录制（图片特效）**<br />*支持音频录制的过程中，增加图片旋转效果，输出为 mp4 文件* |            ✗            |            ✓            |            ✓             |
|                                                              | **背景音乐**<br />*支持拍摄前选择本地文件作为背景音乐*       |            ✗            |            ✓            |            ✓             |
|                                                              | **实时截图**<br />*支持拍摄时实时截图拍照保存到本地*         |            ✓            |            ✓            |            ✓             |
|                                                              | **静音功能**<br />*支持静音拍摄*                             |            ✓            |            ✓            |            ✓             |
|                                                              | **分屏拍摄（合拍）**<br />*可以根据素材视频（或图片）进行合拍，生成双画面视频* |            ✗            |            ✗            |            ✓             |
|                                                              | **屏幕录制(全屏) / View 录制(局部)**<br />*支持对整个屏幕或部分区域进行录制，实现整体或局部的录制效果* |            ✗            |       ✓<br />全屏       |     ✓<br />全屏+局部     |
|                                                              | **外部导入**<br />*支持外部音视频裸数据导入，生成 mp4 文件*    |            ✗            |            ✗            |            ✓             |
|                                                              | **前后台切换**<br />*根据监听到 Application 的前后台状态自动停止和开始录制视频，默认从后台进入前台自动开始录制* |            ✓            |            ✓            |            ✓             |
|                                                              | **实时水印**<br />*支持拍摄时添加静态水印，支持设置水印位置、大小、透明度，设置作用时间范围* |            ✗            |            ✓            |            ✓             |
|                                                              | **实时美颜**<br />*支持拍摄时启用美颜功能，支持设置美颜、美白、红润 3 种效果并调节强度* |            ✓            |            ✓            |            ✓             |
|                                                              | **实时滤镜**<br />*支持拍摄时启用滤镜功能，支持自由调节多种滤镜效果（33 种）* | ✓<br />提供 10 种滤镜效果 | ✓<br />提供 10 种滤镜效果 | ✓<br />提供 33 种滤镜效果  |
|                                                              | **实时预览**<br />*支持实时本地预览*                         |            ✓            |            ✓            |            ✓             |
|                                                              | **草稿箱**<br />*支持将当前录制的片段与设置项存入草稿箱*     |            ✓            |            ✓            |            ✓             |
| **视频剪辑合成**                                             | **视频导入**<br />*支持本地视频快速导入后编辑*               |            ✓            |            ✓            |            ✓             |
|                                                              | **编辑预览**<br />*支持编辑时实时预览本地效果*               |            ✓            |            ✓            |            ✓             |
|                                                              | **视频剪辑**<br />*支持按照给定的时间范围生成一个 mp4 文件*    |            ✓            |            ✓            |            ✓             |
|                                                              | **视频剪裁**<br />*支持按照视频画面大小（原比例、指定区域）精确裁剪视频生成一个 mp4 文件* |            ✗            |            ✗            |            ✓             |
|                                                              | **视频转码**<br />*支持按照给定的目标旋转角度、码率、帧率等参数，生成一个 mp4 文件* |            ✓            |            ✓            |            ✓             |
|                                                              | **视频拼接**<br />*基础功能：支持设置多个视频按照前后顺序导入拼接生成一个 mp4 文件*<br />*高级功能：支持设置多个视频的时间范围按照前后顺序导入拼接生成一个 mp4 文件（先分割后拼接）* |            ✗            |     ✓<br />基础功能     | ✓<br />基础功能 + 高级功能 |
|                                                              | **视频合成**<br />*支持设置多个视频合并为一个视频，支持设置每一个视频的位置、大小、开始播放时间等* |            ✗            |            ✗            |            ✓             |
|                                                              | **GIF动画**<br />*支持基于多个图片或视频直接导出GIF动图*     |            ✗            |            ✓            |            ✓             |
|                                                              | **图片拼接**<br />*支持设置多个图片按照前后顺序导入拼接生成一个 mp4 文件* |            ✗            |            ✓            |            ✓             |
|                                                              | **图片 & GIF 图 & 视频混拼**<br />*支持设置多个视频和图片按照前后顺序导入拼接生成一个 mp4 文件* |            ✗            |            ✗            |            ✓             |
| **视频编辑处理**                                             | **滤镜特效**<br />*支持给视频文件添加滤镜效果，默认支持33种滤镜效果* |            ✗            | ✓<br />提供 10 种滤镜效果 | ✓<br />提供 33 种滤镜效果  |
|                                                              | **贴纸特效**<br />*支持给视频文件添加静态贴纸，并且能够自由设置贴纸大小、位置、旋转角度，支持设置特效显示的时间范围，可以自定义素材或使用供应商提供的收费素材* |            ✗            |            ✓            |            ✓             |
|                                                              | **水印特效**<br />*支持给视频文件添加静态、动态水印，并且能够自由设置水印的大小、位置、透明度、旋转角度，支持设置特效显示的时间范围，可以自定义素材或使用供应商提供的收费素材* |            ✗            |            ✓            |            ✓             |
|                                                              | **时间特效**<br />*支持对视频文件进行整体变速、分段变速，支持5种变速效果（极慢、慢、正常、快、极快）*<br />*支持1种倒放操作（即时光倒流特效）* |            ✗            |       ✓<br />变速       |     ✓<br />变速+倒序     |
|                                                              | **字幕特效**<br />*支持给视频文件添加文字特效，支持设置文字内容，字体大小，字体颜色，透明度，旋转，位置等，支持设置特效显示的时间范围* |            ✗            |            ✓            |            ✓             |
|                                                              | **MV特效**<br />*支持给视频文件添加 MV 效果，默认提供 4 种 MV 特效，MV 特效素材需要客户自行按要求制作* |            ✗            |            ✗            |            ✓             |
|                                                              | **涂鸦特效**<br />*支持画笔尺寸和颜色调整，支持设置特效显示的时间范围* |            ✗            |            ✓            |            ✓             |
|                                                              | **基础转场**<br />*支持在视频图片片段之间，增加淡入淡出效果*   |            ✗            |            ✓            |            ✓             |
|                                                              | **过场字幕**<br />*支持在视频之间增加转场字幕，支持定义转场字幕的背景色、持续时间、支持文字和图片特效，支持旋转、放大、位置移动、淡入淡出 4 种效果* |            ✗            |            ✗            |            ✓             |
|                                                              | **混音特效**<br />*支持给视频文件添加多个背景音乐，支持调整视频原声、背景音乐音量，支持设置多个背景音乐有效时间区域* |            ✗            |  ✓<br />支持单音频混音  |  ✓<br />支持多音频混音   |
|                                                              | **旋转特效**<br />*支持设置视频左右上下旋转，实时预览旋转效果* |            ✗            |            ✓            |            ✓             |
| **视频播放**                                                 | **播放器SDK**                                                |            ✓            |            ✓            |            ✓             |
| **上传分发**                                                 | **视频上传**                                                 |            ✓            |            ✓            |            ✓             |
|                                                              | **断点续传**                                                 |            ✓            |            ✓            |            ✓             |
|                                                              | **上传加速**                                                 |            ✓            |            ✓            |            ✓             |
| **接口扩展**                                                 | **扩展接口支持对接第三方美颜特效等增值能力**                 |            ✓            |            ✓            |            ✓             |
| **增值能力**<br />（需要客户单独选购，在视频拍摄或视频编辑阶段增加） | **高级美颜**<br />*拍摄设置大眼、瘦脸、V脸、下巴调整、短脸、小鼻效果，并支持调节强度* |            ✓            |            ✓            |            ✓             |
|                                                              | **人脸贴纸**<br />*支持人脸识别，进行人脸 2D、3D 贴纸操作*     |            ✓            |            ✓            |            ✓             |
|                                                              | **手势识别**<br />*可以对拍摄的人物的特定手势进行识别，配合其他特效*|            ✓            |            ✓            |            ✓             |
|                                                              | **AR 特效**<br />*支持拍摄时设置AR特效*                      |            ✓            |            ✓            |            ✓             |
|                                                              | **变声混响**<br />*拍摄时对录制的人音进行变声（如萝莉、大叔）和混响效果等操作（如KTV、会堂）* |            ✓            |            ✓            |            ✓             |
|                                                              | **类抖音特效**<br />*滤镜效果，支持抖动、幻觉、灵魂出窍等数种抖音特效* |            ✓            |            ✓            |            ✓             |
|                                                              | **背景抠图**<br />*将画面中的绿色元素(比如纯绿背景)抠除，替换成其他的元素，比如动态背景/PPT 等* |            ✓            |            ✓            |            ✓             |

# 3 设备以及系统要求

- 设备要求：搭载 iOS 系统的设备
- 系统要求：iOS 8.0 及其以上

# 4 安装方法

[CocoaPods](https://cocoapods.org/) 是针对 Objective-C 的依赖管理工具，它能够将使用类似 PLShortVideoKit 的第三方库的安装过程变得非常简单和自动化，你能够用下面的命令来安装它：

```bash
$ sudo gem install cocoapods
```

## 4.1 Podfile

为了使用 CoacoaPods 集成 PLShortVideoKit 到你的 Xcode 工程当中，你需要编写你的 `Podfile`

## 4.2 专业版安装
**如果你购买的是七牛专业版本的短视频 SDK，请使用下面的安装方式：**

###  4.2.1 Podfile 添加专业版 

```ruby
target 'TargetName' do
pod 'PLShortVideoKit'
end
```

### 4.2.2 Warnings

**在使用了七牛的推流或连麦 SDK 的工程中，集成该短视频 SDK 会出现美颜库导致的符号冲突问题 duplicate symbol _OBJC_CLASS_ MuseProcessor，解决方法如下**

```ruby
target 'TargetName' do
pod 'PLShortVideoKit/ex-libMuseProcessor'
end
```
### 4.2.3 运行 pod
然后，运行如下的命令：

```bash
$ pod install
```
## 4.3 进阶版安装
**如果你购买的是七牛进阶版本的短视频 SDK，请使用下面的安装方式：**

### 4.3.1 Podfile 添加进阶版 

```ruby
target 'TargetName' do
pod 'PLShortVideoKit', :podspec => 'https://raw.githubusercontent.com/pili-engineering/PLShortVideoKit/master/PLShortVideoKit-Advanced.podspec'
end
```

### 4.3.2 Warnings

**在使用了七牛的推流或连麦 SDK 的工程中，集成该短视频 SDK 会出现美颜库导致的符号冲突问题 duplicate symbol _OBJC_CLASS_ MuseProcessor，解决方法如下**

```ruby
target 'TargetName' do
pod 'PLShortVideoKit/ex-libMuseProcessor', :podspec => 'https://raw.githubusercontent.com/pili-engineering/PLShortVideoKit/master/PLShortVideoKit-Advanced.podspec'
end
```
### 4.3.3 运行 pod
然后，运行如下的命令：

```bash
$ pod install
```

## 4.4 基础版安装
**如果你购买的是七牛基础版本的短视频 SDK，请使用下面的安装方式：**

### 4.4.1 Podfile 添加基础版 

```ruby
target 'TargetName' do
pod 'PLShortVideoKit', :podspec => 'https://raw.githubusercontent.com/pili-engineering/PLShortVideoKit/master/PLShortVideoKit-Basic.podspec'
end
```

### 4.4.2 Warnings

**在使用了七牛的推流或连麦 SDK 的工程中，集成该短视频 SDK 会出现美颜库导致的符号冲突问题 duplicate symbol _OBJC_CLASS_ MuseProcessor，解决方法如下**

```ruby
target 'TargetName' do
pod 'PLShortVideoKit/ex-libMuseProcessor', :podspec => 'https://raw.githubusercontent.com/pili-engineering/PLShortVideoKit/master/PLShortVideoKit-Basic.podspec'
end
```
### 4.4.3 运行 pod
然后，运行如下的命令：

```bash
$ pod install
```

## 4.5 Warning 
- Podfile 中添加 PLShortVideoKit 时如果不指定 podspec，默认安装的是 **专业版** 的短视频 SDK
- 如果你安装的七牛短视频 SDK 版本和你购买的七牛短视频 SDK 版本不一致，比如购买的基础版，但是使用的是进阶版或者专业版的短视频 SDK，会引起你的 App 产生 crash 。**请一定安装和你购买匹配的短视频 SDK 版本**


# 5 PLShortVideoKit 文档

请参考开发者中心文档：[PLShortVideoKit 文档](https://developer.qiniu.com/pili/sdk/3733/short-video-ios-sdk)

# 6 声明

本短视频 SDK 需授权方可使用，可通过 400-808-9176 转 2 号线联系七牛商务咨询，或者 [通过工单](https://support.qiniu.com/?ref=developer.qiniu.com) 联系七牛的技术支持。

# 7 反馈及意见

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 issues 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 Labels 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-engineering/PLShortVideoKit/issues)







