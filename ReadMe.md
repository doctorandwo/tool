### 包管理工具
名称：fnm
安装文档：https://storm-ice-649.notion.site/node-306913882d0e805e8a20e44952a82cdb
# 下载并解压
$url = "https://github.com/Schniz/fnm/releases/latest/download/fnm-windows.zip"
$output = "$env:TEMP\fnm-windows.zip"
Invoke-WebRequest -Uri $url -OutFile $output
Expand-Archive -Path $output -DestinationPath "$env:USERPROFILE\fnm"
