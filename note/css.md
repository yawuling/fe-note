# CSS 杂记

1. 在移动端中，垂直居中问题

在iOS和Android中，小于12px的文本，垂直居中在android中会偏上移动，因此对于小于12px的文本，使用scale进行设置。

2. box-sizing 和 line-height 垂直居中

box-sizing 设置为 border-box，并通过 height 和 line-height 进行垂直居中，在 mac os(ios) 和 windows（android）上表现形式不一致，前者需要将line-height减去上下边框。对于这种情况，可以使用 button 按钮，button 默认支持垂直居中，不同平台表现形式一致。
