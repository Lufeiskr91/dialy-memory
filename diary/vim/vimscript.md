# 变量

## 选项变量
可以通过`&`将`选项`作为变量
```vim
  :set textwidth=80
  :echo &textwidth
  :let &textwidth=100
```

## 作为变量的寄存器
你可以将`寄存器`作为变量来读取或设置。
```
  let @a = "hello!"
  echo @a
```

`"`寄存器为未命名（unnamed)寄存器，在复制的时候没有指定寄存器的文本都会放到这里。

在`set`可以搞定的时候，永远不要用`let`，这是因为`let`更难于阅读。 


