# h5desktop
create html5 file,and let h5desktop.exe render it as a desktop application.

# step by step
## step 1
download and install webview2 runtime first manually https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/#download-section

clone this project or download it as zip file,and unzip it
## step 2
configure the title,width,height in config.json
## step 3
write your code in index.html
## step 4
click h5desktop.exe to see your page.
## step 5
take a look you screen to check if it works.

# demo1.bat
```shell
start h5desktop.exe D:\projects\site1\config.json
```

# thanks

	github.com/gonutz/w32/v2 v2.2.2 // indirect
	github.com/jchv/go-webview2 v0.0.0-20211023023319-977d8719321f // indirect
	github.com/jchv/go-winloader v0.0.0-20200815041850-dec1ee9a7fd5 // indirect
	golang.org/x/sys v0.0.0-20200814200057-3d37ad5750ed // indirect
  
