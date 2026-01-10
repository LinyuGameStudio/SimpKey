# SimpKey · 简幻通

让 Minecraft 玩家「微信扫码一键登录」——无需密码、零成本、高安全。

## 特性
- ✅ 微信扫码即绑定，3 秒完成
- ✅ 进服强制验证：未绑定自动踢出 + 倒计时提示
- ✅ 自助解绑 `/simpkey unbind`
- ✅ 数据本地存储 (`bindings.yml`)，重启不丢
- ✅ 支持 Bukkit / Spigot / Paper / Arclight 1.13-1.20+

## 安装
1. 向 QQ **2836068358** 申请开发者 UUID
2. 把 UUID 填进 `plugins/SimpKey/config.yml`
3. 将 **SimpKey-*.jar** 扔进 `plugins` 文件夹
4. 启动服务器，进服输入 `/simpkey` 扫码即可

## 玩家命令
| 命令 | 说明 |
|---|---|
| `/simpkey` | 领取绑定二维码 |
| `/simpkey unbind` | 解除当前绑定 |

## 权限节点
- `simpkey.use` - 允许使用扫码绑定（默认拥有）

## 配置文件
```yaml
# 开发者 UUID（向官方申请）
developer-uuid: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx 这里直接写的我的 要二次发布一定要记得改
api-host: https://pass.simpfun.cn
# 二维码有效期 (秒)
qr-timeout: 120
# 轮询间隔 (秒)
poll-interval: 1

```
### 必读
偷我uuid的人司马司爸司全家司亲戚司的最惨的偷我uuid的人
