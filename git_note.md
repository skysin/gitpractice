# <center>**git practice**</center>
*<h4 style = "text-align:right">from &lt;pro _git></h4>*

----------------------------
<body style= "font-family:STKaiti"></body>

#### git配置
>git config是用来读取和配置工作环境变量的工具<br>
 环境变量的存储位置决定了Git的行为
 >>/etc/gitconfig：对系统中所有用户均适用的配置。通过`git config --system`命令读写<br>
 ~/.gitconfig:用户目录下的配置文件只适用于该用户。通过`git config --global`命令读写<br>
 .git/config:当前项目的配置文件仅对当前项目有效<br>
 >>ps:每一级别的配置都会覆盖上层的相同配置

>基础操作：<br>
 配置用户名:<br>
 `git config --global user.name "xxx"`
 配置用户邮箱:<br>
 `git config --global user.name xxx@xxx.xxx`
 配置文本编辑器:<br>
 `git config --global core.editor emacs/vi/vim`
 配置差异分析工具:<br>
 `git config --global merge.tool vimdiff`
 查看配置信息:<br>
 `git config --list`
 获取帮助:<br>
 `git help <verb>`<br>
 `git <verb> --help`<br>
 `man git-<verb>`<br>
 >>ps:--global命令可以根据需要更改为--system或者不写

#### Git基础
>初始化:<br>
 `git init`<br>
 克隆仓库:<br>
 `git clone [url] [name]`<br>
 查看文件状态:<br>
 'git status'<br>
 跟踪新文件:<br>
 `git add xxx`<br>
 忽略文件（建立.gitignore文件）:<br>
 `touch .gitignore`<br>
 提交更新:<br>
 `git commit -m "xxxx"`<br>
 



