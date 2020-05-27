# Simplified Chinese Cangjie input code on macOS, iOS, iPadOS
**施工中: 100/2553**

由于 macOS, iOS, iPadOS 等 Apple Device 上的仓颉简体字编码跟五代仓颉有所差异，从而也导致了速成输入法有差别。

差异例如:

```
「车」 五代仓颉:「大手」  苹果仓颉:「十手」  苹果速成:「十手」
```

也有些没有按规则的特例汉字
```
「链」 五代仓颉:「人心卜大手」  苹果仓颉:「金卜大手」 苹果速成:「金手」
```
但同为「钅」部的「锂」和其它「钅」部的字一样取「人心」字码
```
「锂」  五代仓颉:「人心田土」  苹果仓颉:「人心田土|难金田土」 苹果速成:「人土」

// 苹果速成不能打成「金土|难土」
```

目前共收录 2553 个常用简体字，如有错误或遗漏，可以在 [https://github.com/bexonpak/Simplified-Chinese-Cangjie-input-code-on-Mac/issues](issues) 中提出。