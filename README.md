# Christmas-tree-code
# 最简单的绘制圣诞树

height = 5                        # 树的高度
stars = 1                         # 树的雪花数，初始为1
for i in range(height):            # 以树的高度作为循坏次数
    print(('' * (height - i)) + ('*' * stars))
    stars += 2
    print((''*height)+'|')         # 输出树干
-----------------------------------
python 圣诞树代码 python圣诞树代码复制手机
https://blog.51cto.com/u_16099213/6589774
