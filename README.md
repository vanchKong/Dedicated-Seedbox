# Changelog

## Version Update

- Commented out `disable_tso_` to enable TSO (TCP Segmentation Offload).

### Change Details

In this version, the configuration option `disable_tso_` has been commented out to enable TSO functionality. This ensures that TSO is enabled, which can improve network performance. Enabling TSO allows the system to split large data chunks into smaller packets during data transmission, improving network efficiency.

For the Chinese version, please refer to [简体中文](#).
