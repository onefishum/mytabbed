# mytabbed

## 加载st
`tabbed -c -r 2 st -w ''`

## 设置默认terminal为st
> -p s+1 新建标签id+1  

`gsettings set org.gnome.desktop.default-applications.terminal exec "/usr/local/bin/tabbed -p s+1 -c -r 2 /usr/local/bin/st -w ''"`

## 快捷键
- Alt-Shift-t  
	打开一个新标签
- Alt-Shift-h  
	打开上一个标签
- Alt-Shift-l  
    打开下一个标签
- Alt-Shift-j  
	选择左边标签
- Alt-Shift-k  
	选择右边标签
- Alt-t  
	列表选择标签
- Alt-q  
	关闭标签
- Alt-[0..9]  
	跳转到标签
- Alt-Enter  
	全屏切换

