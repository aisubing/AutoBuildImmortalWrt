1. 去掉自带文件管理

   ```
   位置：/x86-64/build24.sh
   
   # 文件管理器
   # PACKAGES="$PACKAGES luci-i18n-filemanager-zh-cn"
   ```

2. 启用quickfile文件管理

   ```
   位置： /shell/custom-packages.sh
   
   # 新增非常好用的文件管理器 sbwml/luci-app-quickfile （luci 23版本不支持 勿集成）
   CUSTOM_PACKAGES="$CUSTOM_PACKAGES bash quickfile luci-app-quickfile luci-i18n-quickfile-zh-cn"
   ```