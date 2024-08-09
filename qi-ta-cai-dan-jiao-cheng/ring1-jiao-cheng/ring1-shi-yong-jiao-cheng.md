# Ring-1使用教程

## Ring-1使用教程

所有的Ring-1项目仅支持INTEL CPU,不支持AMD CPU丨而注入大同小异,所以不做重复教程说明

### 购买前检查 <a href="#gou-mai-qian-jian-cha" id="gou-mai-qian-jian-cha"></a>

**你需要下载注入器,然后`运行注入器`,注入器会`自动检查`你是否可以使用Ring-1**

![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252FKZqRoeWHvaQCKAvpp7Tm%252Fimage.png%3Falt%3Dmedia%26token%3D3de40b64-3f58-41f2-b1fd-fa3f709c30e2\&width=768\&dpr=4\&quality=100\&sign=f3d5d078\&sv=1)**出现全部`绿色勾子`这样就是可以使用,反之不行**

### 注入前需看 <a href="#zhu-ru-qian-xu-kan" id="zhu-ru-qian-xu-kan"></a>

#### Bios: <a href="#bios" id="bios"></a>

**Bios面板设置：**

**驱动器必须格式化为 GPT 分区 丨**[**点击查看检查是否为GPT分区**](https://docs.hzz.im/g/cod/ring-1/gpt)

**引导模式必须在 UEFI 中**

**打开并启用英特尔虚拟化和所有相关选项，如 VT-d 和 VT-x**

**关闭安全启动/删除所有可启动密钥**

**禁用 TPM（可选）**

**百度/B站或者其他平台搜索：`XX主板关闭安全启动` 跟 `XX主板如何设置UEFI启动`**

**查看是否关闭安全启动/启动UEFI：**

**`Win`+`R` 输入msinfo32**

![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252FVn5svGNuBhvPbfPvrjAl%252Fimage.png%3Falt%3Dmedia%26token%3De293867a-436c-49fa-a8dd-1d3420607cb0\&width=768\&dpr=4\&quality=100\&sign=441b2420\&sv=1)

![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252FbMrBvtPRlucZxpnGD8xu%252Fimage.png%3Falt%3Dmedia%26token%3D60ec631c-8bc0-43fd-9d16-6dd1ba24b7c1\&width=768\&dpr=4\&quality=100\&sign=fab64418\&sv=1)**如图所示即可**

#### 下载运行库 <a href="#xia-zai-yun-xing-ku" id="xia-zai-yun-xing-ku"></a>

[![Logo](https://pan.baidu.com/m-static/base/static/images/favicon.ico)百度网盘 请输入提取码](https://pan.baidu.com/s/1-9mSHfrbeItll5GWZx7r3g)**提取码：byhz**

#### 电脑设置: <a href="#dian-nao-she-zhi" id="dian-nao-she-zhi"></a>

**卸载电脑里的所有`杀毒`软件(**~~**电脑管家 360 鲁大师**~~** 等等)**

**关闭电脑里的`自带杀毒`**

**使用`DX修复工具`修复**

**关闭退出所有覆盖层软件 例如:`GAME++`,`微星小飞机MSI`** **`Afterburner`,`NVIDIA GeForce`等等**

**关闭退出你电脑里的各种调试器 例如：`CE`**

### 下载 <a href="#xia-zai-1" id="xia-zai-1"></a>

**`2023.12.11`更新后,每次注入后,`注入器会自动删除`,`每次注入后都需要重下注入`**

### 注入 <a href="#zhu-ru" id="zhu-ru"></a>

> **管理员运行注入器,输入激活码登录**

![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252FfHkUl9ReQvBNAs3f7cSJ%252FR1%25E7%2599%25BB%25E5%25BD%2595.png%3Falt%3Dmedia%26token%3D9ae20164-e048-49e8-bc52-d2a9fa4837c4\&width=768\&dpr=4\&quality=100\&sign=a414432f\&sv=1)![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252FjdJyBQIIj00b96uHZf29%252Fring-1%25E9%2580%2589%25E6%258B%25A9%25E6%25B8%25B8%25E6%2588%258F.png%3Falt%3Dmedia%26token%3D9478374b-0c2c-4cf7-b893-6702a838fa25\&width=768\&dpr=4\&quality=100\&sign=9797a60c\&sv=1)

**登录后,选择你买的`游戏类型`,然后点击`Load selected cheats`注入,等待提示你`重启电脑`**

> **`Run Cleaner(after a ban)`是当你使用Ring-1被Ban后点击这个清理菜单文件**
>
> **`Lood spoofer only(no cheats)`是仅加载机器码,不加载菜单**
>
> **`Lood selected cheats`是加载菜单注入**

![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252FBAwnEtNblpPUNAtpY5xx%252Fring-1%25E6%25B3%25A8%25E5%2585%25A5.png%3Falt%3Dmedia%26token%3D1e747556-b7c5-486c-82f7-6587ef4f0a81\&width=768\&dpr=4\&quality=100\&sign=2c1e791b\&sv=1)

**等待出现`Restart PC`的提示后,点击`Restart PC`然后`重启你的电脑`,重启后直接进入`游戏`即可**

### **机器码** <a href="#ji-qi-ma" id="ji-qi-ma"></a>

**`Ring-1的机器码是免费使用`的,所以我`强烈推荐你开`,`这样即使你被Ban了,也不会Ban到你自身电脑`,不影响你以后游玩**

**`Ring-1机器码为免费使用,如果你看教程都不知道怎么使用,那么请你不要使用,避免浪费大家的时间~`**

**使用机器码可能会让你电脑`重启2-3`次,这是正常现象！**

> **注入器下方会有选项,你可以自行决定需不需开启过机器码**
>
> **如果需要开启,则点击`HWID Spoofer`旁边的`绿色按钮`(`绿色代表开启`)**
>
> **如果需要更换机器码，则点击`Change HWID Seed`**
>
> **`HWID Seed:`是现在你当前的机器码ID**

![](https://docs.hzz.im/\~gitbook/image?url=https%3A%2F%2F1382592200-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7YXEHggLzaiKwZjRSOD4%252Fuploads%252Ff4Fz6EQpSFRghhOgGNkl%252FRing-1%25E8%25BF%2587%25E6%259C%25BA%25E5%2599%25A8%25E7%25A0%2581.png%3Falt%3Dmedia%26token%3D26231daa-3d35-4806-a4b3-04b3a729fdef\&width=768\&dpr=4\&quality=100\&sign=7c19e043\&sv=1)

### **使用** <a href="#shi-yong" id="shi-yong"></a>

**点击 `DEL` 呼出/隐藏菜单**

**点击 `END` 卸载退出菜单**

**`鼠标点击` 操控菜单**

`0`**简洁透视/开启或关闭战斗模式**

> **期间游戏闪退,重新进入游戏即可,不需要重新注入,除非你重启或者按了`END`卸载退出菜单**

### **设置中文** <a href="#she-zhi-zhong-wen" id="she-zhi-zhong-wen"></a>

SOON

***

**2024.08.01：R6与Rust新增中文，在设置内可以选择改变菜单语言**
