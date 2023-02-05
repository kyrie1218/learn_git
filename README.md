# git教程

## Git软件信息查看

- 查看git软件版本: `git --version`
- 查看git帮助文档: `git --help`

## Git默认配置
一般来说，Git运行时，外观和行为的默认配置存储在如下三个文件:

- `/etc/gitconfig`文件: 系统级的git配置;
- `~/.gitconfig`文件: 用户级的git配置;
- 项目目录下的`.git/config`文件: 项目级的git配置。

!!! note 
	1. 配置文件并没在Git安装后自动创建, 前两个仅仅在使用`git config`语句配置信息后生成; 第三个在git项目创建时生成。
	2. 运行Git时，配置信息会自动覆盖上一级别的配置，即优先使用`.git/config`中的信息作为该项目的配置信息。

### 常用配置参数






## Git

- 初始化仓库: `git init`

- 创建新分支: 
