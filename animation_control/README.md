### 用于对3DMax导出的带有动画的模型进行开关控制
	
模型要求：

1. 导出的模型只包含一个完整帧动画
2. 该动画仅包含打开或关闭的动画，另一半动画由程序逆向播放动画来完成

应用方法：

在场景节点 root 上，执行：
>	AnimationSetting v; 
>	root->accpet(v);

即可

完成后，左键双击执行“开”动画；右键双击执行“关”动画