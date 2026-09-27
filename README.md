# Godot-VsCode-Chinese-Highlight-Patch
一个用于VsCOde插件“Godot Tools”的JSON配置表 ，在VsCode中编写GSD脚本，需通过一个"Godot tools"插件实现，此插件无法高亮中文变量名、函数名、类名等自定义中文名称，通过本仓库JSON配置表替换插件的JSON配置表，即可正常高亮中文字符。

## 使用方法
作为配置复制使用<br>
在VsCode插件路径下，找到指定的“Godot Tools”插件，并在“syntaxes”文件夹下替换“GDScript.tmLanguage”JSON文件<br>
默认路径：<br>
C:\Users\UserName\\.vscode\extensions\geequlim.godot-tools-version number\syntaxes\GDScript.tmLanguage.json

## 效果演示
原始画面01<br>
<img width="1179" height="727" alt="无01" src="https://github.com/user-attachments/assets/64478673-db5c-4815-8e92-2c9bc62e3a8d" />
JSON文件替换后效果01<br>
<img width="1180" height="727" alt="JSON更改01" src="https://github.com/user-attachments/assets/3b84ff94-f115-4f63-88fb-9565b5b95f4e" />

原始画面02<br>
<img width="1179" height="727" alt="无02" src="https://github.com/user-attachments/assets/f0ddc916-60f0-4b4b-bd1c-72b92a417eb4" />
JSON文件替换后效果02<br>
<img width="1177" height="727" alt="JSON更改02" src="https://github.com/user-attachments/assets/4d7a091f-a36f-4a71-ac2f-48be47254f93" />

### 附加提示
此JSON文件替换后加入主题插件会更好用，优先推荐“True Godot Theme”插件<br>
<img width="285" height="100" alt="Snipaste_2026-09-28_01-52-11" src="https://github.com/user-attachments/assets/19c71276-8b13-4024-bab2-764010fa89f1" /><br>
只添加插件画面01<br>
<img width="1179" height="727" alt="纯插件01" src="https://github.com/user-attachments/assets/cbe0bdee-7776-4194-bff6-7f2adabd162e" />
插件+JSON文件替换01<br>
<img width="1180" height="727" alt="插件+JSON更改01" src="https://github.com/user-attachments/assets/435560e3-f121-41ec-a413-dcc0c2dd6eed" />
只添加插件画面02<br>
<img width="1179" height="727" alt="纯插件02" src="https://github.com/user-attachments/assets/5ec7e905-f289-484e-af79-a838fec71fd3" />
插件+JSON文件替换02<br>
<img width="1177" height="727" alt="插件+JSON更改02" src="https://github.com/user-attachments/assets/654e1476-c59f-49ae-99ba-893605b8041a" />




