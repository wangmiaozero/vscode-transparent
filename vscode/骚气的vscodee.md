插件 
https://juejin.im/post/5cdbe78cf265da034d2a3910
https://juejin.im/post/5cdbe78cf265da034d2a3910#heading-2
透明化

 + `SynthWave '84`
 + `Custom CSS and JS Loader`
		 +  /Applications/Visual Studio Code.app/Contents/MacOS/Electron, on MacOS;
		/Applications/Visual Studio Code - Insiders.app/Contents/MacOS/Electron, on MacOS when using Insiders branch;
		/usr/share/code, on most Linux;
		/opt/visual-studio-code/ on Arch Linux.

+ `Quokka (JS/TS ScratchPad)`


一、安装插件(安装失败的自己爬墙吧)：
	1.SynthWave '84 
	2.Custom CSS and JS
	3.GlassIt-VSC
二、下载配置文件(两个方法二选一)：
	1.git命令安装
		git clone https://github.com/Jinkeycode/vscode-transparent-glow.git
	2.浏览器访问
		https://codeload.github.com/Jinkeycode/vscode-transparent-glow/zip/master
三、修改vscode的配置文件setting.json(在setting.json文件中加入下面代码):
	"vscode_custom_css.imports":[
        "file:///C:/Users/Administrator/AppData/Roaming/Code/User/vscode-transparent-glow-master/synthwave84.css",
    ]
    
    "C:/Users/Administrator/AppData/Roaming/Code/User/vscode-transparent-glow-master/"这个替换成你步骤二中下载到的文件所在位置
四、使配置生效
	按下 Ctrl + Shift + P，运行 "Reload Custom CSS and JS", 重启 vscode 即可。