# ha-aiui-bridge
适用于 Rokid Glasses 的 Home Assistant AIUI 应用，本仓库为接入 Home Assistant 的桥接器。

## 使用方法
1. `git clone https://github.com/xiaoheiCat/ha-aiui-bridge.git`
2. 将 `ha-aiui-bridge` 目录上传到 Home Assistant 的 `config/` 目录的 `www/` 文件夹下。若 `www` 不存在，请新建文件夹。最终应该得到 `.../config/www/ha-aiui-bridge` 的结构。
3. 访问 `http://你的公网实例地址:8123/local/ha-aiui-bridge/index.html`，按照页面提示完成眼镜端的授权认证。
