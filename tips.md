```diff 
+ 注意事项:
- jumkey 仅支持 7.0及以下, pocopico&jun 也仅支持7.0及以下. 
- 只有 DS3615xs 和 DS918+ 支持 6.2.4 版本. jumkey 不支持 DVA1622 和 DVA3221.
- dtb 没有制作就不要写, 不要再只填个 .zip, 或者复制示例的地址了. 更多信息参考 Issues页的置顶Issue. 四盘位以下可尝试不填写, 将自动编译.
- DS3615xs/DS3617xs 现有驱动全选会编不过, 空间不足.
- DS918+ 7.1.1 在dev模式下才会包含 virtio 扩展.
- 不用关注Action页面报的 Warnings, 不影响编译.
```
