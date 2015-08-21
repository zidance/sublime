# sublime
Sublime text拓展插件整理，间断更新补全中...

##安装Sublime Text 2插件的方法：

### 1. 直接安装	
> 安装Sublime text 2插件很方便，可以直接下载安装包解压缩到Packages目录（菜单->preferences->packages）。

### 2. 使用Package Control组件安装
也可以安装package control组件，然后直接在线安装：	
> * 按 Ctrl+调出 `console`		
> * 粘贴以下代码到底部命令行并回车：	
> `import urllib2,os;pf='Package Control.sublime-package';ipp=sublime.installed_packages_path();os.makedirs(ipp) if not os.path.exists(ipp) else None;open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read())  `	
> * 重启Sublime Text。				
> * 如果在Perferences->package settings中看到package control这一项，则安装成功。	


大名鼎鼎的
Zen Coding: A Speedy Way To Write HTML/CSS Code