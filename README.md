# ba-jp-aprilfools-minigame-2025-archive

```shell
# Sync assets
cd public
aria2c -x16 -s16 -c -i ../vendor.list
# Update checksum
find public -type f -exec sha256sum {} + > assets.sha256
```
