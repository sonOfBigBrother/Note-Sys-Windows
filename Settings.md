## 设置
### 手动添加git选项到右键菜单中
- 打开“运行”并输入“regedit”打开注册表
- 在注册表中找到目录[HKEY_CLASSES_ROOT\Directory\Background]
- 通常该目录下有个目录[shell]，若无，自行新建一个。
- 在[shell]下右键——新建项[open in Git]，其值为“Git Bash Here”——右键菜单显示名称。
- 在[shell]下右键——新建字符串值[Icon],设定其值为[directory-to-git\mingw64\share\git\git-for-windows.ico]——右键菜单显示图标
- 在[open in Git]下右键——新建项[command]，其值为[directory-to-git\git-bash.exe]

### 电脑运行ss代理的情况下，cmd命令窗口无法访问google服务器
Solution：在命令窗口中输入
> set http_proxy 127.0.0.1:1080
> set https_proxy 127.0.0.1:1080

即可正常访问google服务器

### win10系统自带输入法无法切换成中文

打开命令行输入`ctfmon`命令重启输入法进程即可。