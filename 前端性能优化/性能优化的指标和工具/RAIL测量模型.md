## RAIL测量模型



### 什么是RAIL

*是一个谷歌推出的性能标准*。

- **R: Response 响应  用户交互后有没有及时给出响应**
- **A: Animation 动画 动画是否足够流畅**
- **I: Idle 空闲  浏览器主线程是否有足够的空闲**
- **L: Load 加载  浏览器加载是否足够及时**



### RAIL评估标准

- 响应: 所有的处理事件(交互)应在50ms以内完成
- 动画：每i0ms产生一帧
- 空闲：尽可能增加空闲时间
- 加载：在5s内完成内容的加载并可以交互





## 性能测量工具

- Chrome DevTools 开发调试，性能评测
- Lighthouse 网站整体质量评估
- WebPageTest 多测试地点，全面性能报告