
> 自动登录 ClawCloud，保持账户活跃，支持设备验证 + 两步验证

## 🔐 Secrets 配置

| Secret 名称 | 必需 | 说明 |
|-------------|------|------|
| `GH_USERNAME` | ✅ | GitHub 用户名 |
| `GH_PASSWORD` | ✅ | GitHub 密码 |
| `GH_TOTP` | ✅ | TOTP 密钥 |
| `REPO_TOKEN` | ✅ | GitHub PAT（用于自动更新 Cookie） |
| `TG_BOT_TOKEN` | ✅ | Telegram Bot Token |
| `TG_CHAT_ID` | ✅ | Telegram Chat ID |
| `GH_SESSION` | ❌ | 自动生成，无需手动添加 |

---
