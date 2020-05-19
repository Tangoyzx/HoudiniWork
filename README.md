# HoudiniWork
 
![章鱼腿](https://github.com/Tangoyzx/HoudiniWork/blob/master/pictures/bone_to_curves.gif)
尝试实现[视频中章鱼腿](https://www.youtube.com/watch?v=LCJlBs1B46M&t=345s)，但总感觉没做出来那种各个地方很弯曲的效果，尝试过一开始就把骨骼弄成curve但是vellum中没找到类似c3d的resthold的属性。
做成了一个HDA，可以输入章鱼腿生成的点以及碰撞体以及magnet的位置，点下DO就可以根据输入的点copytopoints一些章鱼腿并且生成对应的骨骼去做vellum solver。