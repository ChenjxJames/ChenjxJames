# WSL 2 与 docker的安装

1. 在控制面板>程序与功能>启用或关闭Windows功能中打开适用于Linux的Windows子系统
2. 在应用商店中安装一个Linux发行版，这里我安装的是Ubuntu-18.04LTS
3. 输入命令```bash wsl -l ```就可以看到已经安装的子系统
4. 输入命令```bash wsl --set-version Ubuntu-18.04 2 ```将安装的Ubuntu子系统的wsl版本改为wsl2，wsl2相比wsl1具有完整的Linux内核。

5. pass



> [(知乎)【WSL+Docker】新手Win10下的WSL Ubuntu18并使用Docker（两种方式）](https://zhuanlan.zhihu.com/p/61542198)  
> [(简书)如何在 Windows 10 中安装 WSL2 的 Linux 子系统](https://www.jianshu.com/p/6da235905657)