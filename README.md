AnimatedGif
===========

GIF动态图

使用方法：

  NSURL *Url =[NSURL fileURLWithPath:[[NSBundle mainBundle] pathForResource:@"Go" ofType:@"gif"]];
	UIImageView	*Animation = [AnimatedGif getAnimationForGifAtUrl:Url];
