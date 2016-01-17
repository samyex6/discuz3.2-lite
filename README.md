# discuz3.2-lite

This update took me whole night... Full of incompatible functions and errors.. 
Most of the errors is because of the carelessness. (I suppose they didn't open the debugging mode at all...)
They really need get their shits together.

这个更新耗费了我整个晚上……各种不兼容和错误……大部分错误都是因为程序猿的粗心大意导致的（估计他们从来不开调试模式……），改得我不要不要的。

- Status: Done.
- This project aims to upgrade the latest version from DiscuzX3.2 to DiscuzX3.2-Lite, which supports PHP7.
- If any bug occurs, please submit an issue.
- Before using, please test locally to make sure everything works.
  
- 状态：完工
- 这个项目的目的是让DiscuzX3.2支持PHP7，代号为DiscuzX3.2-Lite。
- 如果出现任何问题，请提交到issues。
- 在应用到服务器之前请先在本地测试。

### Major changes
- `mysql` functions to `mysqli`.
- `preg_replace` functions with `e` modifier to `preg_replace_callback`.
- Other minor changes, fixed some stupid bugs.
  
### 主要更新内容
- `mysql`系列函数更换至`mysqli`.
- 附带`e`修饰符的`preg_replace`函数更换至`preg_replace_callback`。
- 其它小修改，修正了一些很逗比的bug。