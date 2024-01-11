# 蓝图编程

## 节点

1. 相机
2. 拆分通道
3. 合并通道
4. 图像滤波
5. 图像调整
6. 二值化
7. 找线
8. 找圆
9. 模板匹配
10. 几何变换(平移 旋转 镜像 转置)
11. ROI
12. 图像保存
13. 图像裁剪

https://github.com/ganleiboy/CMakeTutorial
## 已经完成
1. 工具动态加载
2. 工具执行逻辑

## TODOS
1. 工具配置界面
2. 工程保存和加载
3. 海康相机和basler相机集成
4. 界面美化
5. ROI
6. 深度学习推理工具集成
7. 工具初始化和连续运行模式
```
QObject::connect(node, &NodeWidget::on_change, [this, node]()
                    { update_all_node(); });
```