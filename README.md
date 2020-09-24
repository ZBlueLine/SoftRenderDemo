# 作业三 #

完成了前5项要求
+ ## rasterize_triangle ## 
    在上次作业的基础上增加了颜色，法向量，纹理坐标，模型原坐标这几个值的插值
+ ## phong_fragment_shader ##
    按照 blinnphong模型计算了高光项漫反射项以及环境光项。
+ ## texture_fragment_shader ##
    用getcolor函数将phong_fragment_shader中的color换成了纹理。
+ ## bump_fragment_shader ##
    按照注释写了凹凸纹理的计算方返回值为凹凸处理之后的法向量
## displacement_fragment_shader ##
    在bump_fragment_shader的基础上增加了顶点位移然后用blinn phong模型计算了三种光。