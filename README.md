# PyLogDc

PyLogDc is Python package, you can log actions of your code / alert to your Discord server using webhook. 
You can use color that you want (using HEX code) or use some of prepared colors.
## Prepared colors
Success = #5cb85c
Info = #5bc0de
Warning = #f0ad4e 
Danger = #d9534f

## Install
For install, run this command in your console / powershell

```bash
pip install pylogdc
```

## Usage
```python
import PyLogDc
webhookURL = "https://discord.com/api/webhooks/......." # Replace with your actual Discord webhook URL
PyLogDc.log_this('Test Header', 'Test message', 'info', webhookURL) # Without footer
PyLogDc.log_this('Test Header', 'Test message', 'info', webhookURL, "Test Footer") # With footer
```
Remember to replace webhookURL with your actual Discord webhook URL.
