---
title: "太阳鸽鸽棒.md"
pegboardUUID: "a62ebd11-623e-4794-a6de-c31daeaf8820"
---
## 一、AE入门：太阳鸽鸽棒
### 1. 认识AE
#### 1.1 推荐配置
CPU：主频2.6ghz以上，睿频4.5ghz以上，6-8核心
内存：最低16gb，推荐32gb以上
显卡：GTX1660以上，显存6gb以上
硬盘：m.2固态硬盘，512GB以上

#### 1.2 基本快捷键
- 撤回：Ctrl(command)+Z
- 保存：Ctrl+S
- 渲染合成：Ctrl+M
- 清理内存：Ctrl+Alt(command)+/

- 「选择」工具：V
- 文字工具：Ctrl+T
- 标尺工具：Ctrl+R
- 钢笔工具：G
- 路径工具：Q

- 位置：P
- 旋转：R
- 缩放：S
- 不透明度：T
- 蒙版羽化：F
- **关键帧添加缓动：F9**
- 修改合成设置：Ctrl+K
- **显示图层关键帧：U**

- 新建纯色图层：Ctrl+Y
- 新建调整图层：Ctrl+Alt(option)+Y
- 新建文字图层：Ctrl+Shift+T
- 新建合成：Ctrl+N

#### 1.3 顶部菜单
- 文件—增量保存：不覆盖现有工程文件，新增保存文件
- 文件—整理工程（文件）：打包一切
- 编辑—清理：清理缓存
- 图层—变换—自动定向：物体沿路径运动时，始终朝向运动的方向

### 2. 使用前的准备
#### 2.1 首选项
自己调整即可，其中纹理内存推荐设置为最大内存的90%。

#### 2.2 插件与脚本推荐
- 插件
	- [RG Universe](https://www.lookae.com/universe-61/)：多种转场特效、滤镜、特效。
	- [Red Giant Trapcode Suite](https://www.lookae.com/trapcode-1518/)：粒子特效。
	- [Red Giant Magic Bullet Suite](https://www.lookae.com/mbs-13016/)：降噪/磨皮/美颜/调色。
	- [RG VFX Suite](https://www.lookae.com/hjrv310/)：跟踪抠像/光工厂视觉特效。
	- [Plexus](https://www.lookae.com/plexus-326/):点线面三维粒子特效。
	- [Stardust](https://www.lookae.com/stardust-160b/)：节点式三维粒子特效。
	- [Newton](https://www.lookae.com/newton-34/)：牛顿动力学插件。
	- [Mocha Pro](https://www.lookae.com/mocha-mac2022/)：平面跟踪、旋转扫描、对象移除、稳定和网格跟踪软件。
	- [Sapphire](https://www.lookae.com/sapphire-202052-mac/)：蓝宝石视觉特效和转场插件。
	- [Superpose](https://www.lookae.com/superpose-22/)：动态物体自动去除插件。
	- [Real Glow](https://www.lookae.com/mac-real-glow/)：真实辉光特效插件。
	- [Deep Glow](https://www.lookae.com/deep-glow-mac144/)：高级辉光发光插件。
	- [Shadow Studio](https://www.lookae.com/shadow-studio/)：阴影特效插件。
	- [AutoFill](https://www.lookae.com/autofill-115/)：图层边界自动填充生长动画。
	- [RetroDither](https://www.lookae.com/retrodither-17/)：粗糙复古8bit比特像素效果。
	- [LongShadow](https://www.lookae.com/longshadow-210/)：阴影长拖尾投影特效。
	- [GifGun](https://www.lookae.com/gifgun-1723/)：一键快速输出GIF动图格式插件。

- 脚本
	- [Overlord](https://www.lookae.com/overlord-122/)：AI与AE实时交互。
	- [Big Pack of Elements](https://www.lookae.com/big-pack-elements/)：1850种MG动画元素。
	- [CuttanaNir](https://www.lookae.com/cuttananir/)：文字书写动画生成器。
	- [Motion](https://www.lookae.com/motion-chn/)：MG运动图形高级工具脚本。
	- [Motion Tools](https://www.lookae.com/motion-tools-2/)：中心点对齐关键帧曲线调整MG脚本。
	- [AutoSway](https://www.lookae.com/autosway-chn/)：风吹自由摇曳摆动MG动画。
	- [Boxcam](https://www.lookae.com/boxcam-25/)：二维平面摄像机动画控制。
	- [CartoonMoblur](https://www.lookae.com/cartoonmoblur-162/)：卡通动态模糊拖尾特效。
	- [iExpressions](https://www.lookae.com/iexpressions-3205/)：精品表达式合集效果库。
	- [True Comp Duplicator](https://www.lookae.com/tcd-3914/)：合成复制脚本(同合成复制修改相互不影响)。
	- [AE Pixel Sorter](https://www.lookae.com/pixel-sorter-222/)：像素方向拉伸撕裂分离特效。

### 3. 图层系统
#### 3.1 文本图层
处理文字的图层，快捷键为Ctrl+Alt+Shit+T。若需要文字按特定路径排列，则在文本图层创建蒙版后，在“路径选项”选择蒙版。

#### 3.2 纯色图层
快捷键Ctrl+Y，Ctrl+Shift+Y唤出设置。真实的颜色图层，配合蒙版可以创建形状。
适合作为插件/效果的承载图层，也适合作为蒙版。

#### 3.3 灯光图层
快捷键Ctrl+Alt+Shift+L。原生3D图层，只对3D图层产生效果。一般用于光影制作、栏目包装、3D插件的配合使用。

#### 3.4 摄相机图层
快捷键Ctrl+Shift+Alt+C。原生3D图层，配合3D图层使用。常用预设是35mm/50mm，设置中很多参数与景深有关。

#### 3.5 空对象图层
快捷键Ctrl+Alt+Shift+Y。空图层，配合父子集控制/表达式控制器。当作控制器使用。

#### 3.6 形状图层
矢量路径的承载体。修改器由顺序决定，若路径有误可通过“合并路径”改变。

#### 3.7 调整图层
快捷键Ctrl+Alt+Y。效果调整，影响其下的所有图层。

#### 3.8 内容识别填充图层
序列图层，抠除多余物体。

### 4. AE的运动系统
#### 4.1 关键帧
- 线性关键帧：最基本的关键帧类型，匀速变化。
- 缓动关键帧：由缓入和缓出构成，快捷键F9。
- 定格关键帧：制作速度快的动画，或者抽帧动画。
- 平滑关键帧：最少三个关键帧，Ctrl+左键点击关键帧。
- 漂浮穿梭关键帧：让运动变得平滑。

运动曲线本质上是贝赛尔曲线，可用Motion插件调整。有“时间—位移”曲线和“时间—速度”曲线。

#### 4.2 表达式
学习方法：学一个用一个。
- wiggle摆动表达式：制作无规则摆动效果。位置，`wiggle(频率,幅度)`。
- time时间表达式：制作和时间有关的效果。旋转，`time*x`。
- random随机表达式：制作无法预测的随机效果。`random(min,max)`
- loop循环表达式：制作循环动画。`loopIn()`关键帧左侧循环，`loopOut()`关键帧右侧循环（默认整组动画循环）。
	- 几个例子：
	- `loopOut(type="pingpong",numberkeyframes=0)` 类似乒乓球的来回循环
	- `loopOut(type="cycle",numberkeyframes=0)` 周而复始的循环
	- `loopOut(type="continue")` 延续属性变化的最后速度
	- `loopOut(type="offset",numberkeyframes=0)` 重复指定的时间段进行循环
	- `numerkeyframes=0`是循环的次数，0为无限循环，1是最后两个关键帧无限循环，2是最后三个关键帧无限循环
	- 弹性表达式：利用代码形成的动画效果。或者用Motion插件的弹性功能。

```javascript
// 弹性动画表达式
amp = .1;
freq = 2.0;
decay = 2.0;
n = 0;
if (numKeys > 0){
n = nearestKey(time).index;
if (key(n).time > time){n--;}
}
if (n == 0){t = 0;}
else{t = time - key(n).time;}
if (n > 0){
v = velocityAtTime(key(n).time - thisComp.frameDuration/10);
value + v*amp*Math.sin(freq*t*2*Math.PI)/Math.exp(decay*t);
}
else{value}
```

### 5. 时间系统
#### 5.1 时间轴
- 快捷键
	- Alt+滚轮：缩放时间轴
	- Ctrl（+Shift）+左右箭头：时间线向前后移动一（十）帧
- 窗口
	- 预览：若预览卡顿，可设置“跳过”

#### 5.2 图层显示区
- 快捷键
	- 左右中括号：移动图层的入点或出点到时间线位置
	- Alt+左右中括号：切断时间线左侧或右侧的部分图层
	- Ctrl+Shift+D：分割图层

#### 5.3 时间重映射、冻结帧
- 时间重映射：控制局部的播放速度，只能应用于合成。不推荐转化为缓动关键帧。
- 冻结帧：特殊的时间重映射，使时间静止。

#### 5.4 时间表达式
- 核心：`Time`表达式，提取当前时间作为函数返回值。
	- `valueAtTime`：`value`是当前属性的值，`valueAtTime`则是该属性当前时间的值。
		- 例1：在位置表达式加上`.valueAtTime(time-1)`，就可以延迟位置发生变化的时间（1s）。
	- `index`：返回当前表达式所在图层的序号。
		- 例2：在例1的表达式中，将`time-1`替换为`time-(index*1)`，复制多个应用此表达式的图层，可以达到拖尾动画的效果（可用“残影”插件实现）。
	- `wiggle(频率,幅度,系数,复杂度,时间)`：实现可循环的随机摆动效果。（例3见下）

```javascript
// 例3
// 位置，循环随机摆动
freq = 1;
amp = 200;  //幅度
looptime = 3;  //循环时间周期为三秒
t = time%looptime;  //当前时间与循环时间周期求余
wiggle1 = wiggle(freq,amp,1,0.5,t);
wiggle2 = wiggle(freq,amp,1,0.5,t-looptime);
linear(t,0,looptime,wiggle1,wiggle2)
```

### 6. 常用插件讲解
插件本质就是一个动态库（通常是aex文件），当输出图象进入动态库，输出之后就能得到新效果。

#### 6.1 基础插件
分类：声音、通道、扭曲、抠像、文本、时间、杂色、模拟、模糊和锐化、生成、表达式控制、过渡、遮罩、颜色校正、风格化

##### 6.1.1 生成
- 填充（fill）：更换图层内像素的颜色。
- 网格：生成横竖线阵列。
![[wangge.png]]
- 棋盘：生成方格阵列。
![[fangge.png]]
- 单元格图案：丰富背景元素，规律颜色信息
![[danyuange.png]]
- 四色渐变：生成四种渐变颜色。
- 梯度渐变：生成两种渐变颜色。
- 描边：初级生长动画效果。
- 无线电波：生成规律的图形扩散图案。
![[wireless.png]]
##### 6.1.2 杂色和颗粒
- 分形杂色：随机分形图案，一般用作背景或纹理。
![[turbulence.png]]
- 湍流杂色：与分形杂色相似，算法不同。
![[turbenlences.png]]
-杂色：添加像素颗粒，一般用于创造复古质感或缓和颜色分层效果。
![[zase.png]]

##### 6.1.3 扭曲
- 贝赛尔曲线变形：用贝赛尔杠杆扭曲图形形状，一般用于制作渐变背景或调整形状。
- 放大：类似放大镜的效果，可用于制作特写。
![[bigda.png]]
- CC Bender：利用两个控制点扭曲图层元素，可制作摆动效果或直线扭曲效果。
- CC Page Turn：翻页效果。
- CC Power Pin：利用四个定位点扭曲图层。
- 边角定位：类似CCPP。
- CC Smear：利用两个定位点对图层的信息制作涂抹效果，可配合分形/湍流杂色制作流体扭曲或高温扭曲的效果。
![[liangdian.png]]
- 光学补偿：透镜变形效果，用于制作切换和转化动画。
- 湍流置换：对图形进行随机的置换扭曲，用于制作随机纹理抖动和波纹的效果。
- 置换图：利用参考图层的信息，使目标图层的颜色发生置换。用于制作图层的贴图效果。
- 网格变形：生成网格，通过调整点与贝赛尔杠杆扭曲图层。
![[beiasss.png]]
- 极坐标：将横向的阵列元素扭曲成圆形。用于圆形纹样制作。
![[jizuobiao.png]]
- 波形变形：使图层发生波纹变形，可用于制作摆动效果。
- 液化：微调图形元素的像素位置，通常用于处理瑕疵。

##### 6.1.3 颜色校正
- 曲线：利用贝赛尔曲线调整图层的颜色通道及alpha通道的对比度，通常用于调整对比度。
- 曝光度：调整曝光程度、偏移与灰度系数，用于调整效果的整体颜色亮度。
- 色调：双色调。
- 色阶：通过修改黑白两色的输入与输出，修改效果的整体颜色。
- 色相饱和度：调整整体与局部的色相、饱和度、亮度。
- 亮度和对比度：整体调整。
- 自然饱和度：增强颜色纯度，但不会过纯。推荐使用其调整饱和度。
- 颜色平衡：影响色彩偏向，用于调色。
- 黑色和白色：去色，只保留明度值，获取图层的黑白颜色信息。

##### 6.1.4 抠像
- 提取：去除物体的黑色或白色信息，也能去除颜色。用于特定颜色的提取和抠素材。
- 颜色范围：抠除特定范围的颜色。
- 插值遮罩：利用颜色数值与容差统一抠除颜色（约等于明度），用于制作特定素材的抠像。
- Keylight：抠除蓝/绿幕的背景，用于影视合成。

##### 6.1.5 其他
- 简单阻塞工具：可让两个物体的轮廓向内收缩，且相交的地方相融；也可处理物体的边缘毛刺。
- 动态拼贴：延展图形边界，用于制作阵列对象或纹理。

- 残影：拖尾效果。
- 编号、时间码：倒计时效果。

#### 6.2 外置插件
##### 6.2.1 粒子
- Particular：模拟粒子效果。
- Plexus：点线面风格的粒子效果，生成三维网格和线条。
- Stardust：节点式的粒子插件。
- Form：静态粒子。

##### 6.2.2 调色
- RG Magic Bullet：调色。
- Looks：调色。
- Film：电影质感插件。
- Mojo：快速调色插件。
- Denoiser：降噪。

##### 6.2.3 光效
- Optical Flares：光斑。
- Shine：扫光、放射光效果。
![[radicallight.png]]

##### 6.2.4 动力学
Newton：制作动力学动画。

##### 6.2.5 3D类
E3D：导入三维模型。

### 7. 3D系统和摄相机
#### 7.1 3D图层
3D图层是图层**属性**，决定图层能否在3D空间中存在。

#### 7.2 3D视图菜单和视图布局
创建摄相机图层后，可以使用摄相机工具改变观察视角。
预览窗口底部靠右的“活动摄相机”可调出多个视图。

#### 7.3 摄相机进阶控制
利用空对象拆分位置的运动。例如要控制图层A做斜线运动，可让A做横向运动、一个是其父级图层的空对象做竖向运动。

#### 7.4 摄相机反求技术
运用跟踪器。
跟踪摄相机：生成跟踪点，绿色代表质量较好（平均误差<3像素）。选择3-4个跟踪点确定地面位置创建实底和摄相机。
变形稳定器：减少抖动。
跟踪运动：追踪特定物体，生成对应空对象。
稳定运动：生成反向运动，补偿摄相机抖动。

#### 7.5 摄相机投影技术
用2D图象制作3D透视移动。

### 8. 图像处理
