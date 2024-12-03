# 更新日志

## 版本更新

- 注释掉了 `disable_tso_`，以便于启用 TSO（TCP Segmentation Offload）。

### 变更说明

在本版本中，为了启用 TSO，已将原先禁用 TSO 的配置项 `disable_tso_` 注释掉。这样可以确保 TSO 功能被启用，优化网络性能。通过启用 TSO，系统可以在数据传输过程中将较大的数据块分割为多个较小的数据包，提高了网络效率。

