# OpenCloudOS文档库

欢迎来到OpenCloudOS文档库！

OpenCloudOS是由20余家操作系统、云平台、软硬件厂商与个人共同倡议发起的操作系统社区项目，即将进入开放原子开源基金会（OpenAtom Foundation）孵化及运营。目标是打造全面中立、开放、安全、稳定易用、高性能的Linux服务器操作系统，共建国产操作系统开源技术社区，扩大社区发行版影响力，构建操作系统健康繁荣的生态。

欢迎访问：[https://www.opencloudos.org/](https://www.opencloudos.org/)

# 如何贡献

欢迎贡献OpenCloudOS！

## 贡献OpenCloudOS

## 贡献文档

1. Fork[文档仓库](https://github.com/OpenCloudOS/opencloudos.github.io/fork)
2. 将您Fork后的文档仓库clone至本地
    ```sh
    git clone git@github.com:yourname/opencloudos.github.io.git # (1)
    ```

    1.  将*yourname*更换为你fork后自己的用户名

3. 安装环境
    - 安装Python 3.x
    - 安装[mkdocs-material](https://squidfunk.github.io/mkdocs-material/)及多语言插件
    ``` sh
    pip install mkdocs-material
    pip install mkdocs-static-i18n
    ```
    - 本地运行
    ``` sh
    mkdocs serve
    ```

4. 可以开始贡献啦！
    - 具体markdown及本文档站支持的显示特性可查看mkdocs-material的[说明文档](https://squidfunk.github.io/mkdocs-material/reference/)。

	!!! info "其他注意点"

	    1. 中英文文档提交格式：
	        ```
	        中文文档：xxx.md
	        英文文档：xxx.en.md
	        ```
	        放在同一路径下即可，导航栏切换语言之后会自动切换到对应路径

	    2. 标题和正文之间要空一行
	    3. 普通文本内容和列表之间要空一行
	    4. 二级列表前面要空4个空格
	    5. 同级列表之间的其他内容，都必须缩进4个空格，有序列表的编号才能连上

	- 修完完毕，本地运行检查没问题了，就可以提交并发起PR了！
