# Odin买单监控机器人

这是一个用于监控Odin平台买单并通过Telegram推送通知的机器人。

## 功能特点

- 自动监控Odin平台的买单信息
- 实时推送买单通知到Telegram
- 可配置的监控间隔
- 优雅的错误处理

## 安装步骤

1. 克隆项目到本地
2. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```

3. 配置环境变量：
   - 复制`.env.example`到`.env`
   - 在`.env`文件中填入您的Telegram Bot Token和Chat ID

## 配置Telegram机器人

1. 在Telegram中找到 @BotFather
2. 创建新机器人并获取Token
3. 将Token填入`.env`文件的`TELEGRAM_TOKEN`字段
4. 获取您的Chat ID并填入`CHAT_ID`字段

## 运行机器人

```bash
python odin_bot.py
```

## 注意事项

- 确保您的网络能够访问Odin平台
- 建议使用Python 3.7或更高版本
- 请遵守Odin平台的使用条款和API限制 