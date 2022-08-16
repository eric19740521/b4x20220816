# b4x20220816
B4X實驗:  telegram Bot機器人製作教學, 開發一個鸚鵡機器鳥Echo Bot(B4J)

B4X實驗:  telegram Bot機器人製作教學, 開發一個鸚鵡機器鳥Echo Bot(B4J)
參考資料:
http://slashview.com/archive2020/20200319.html
 


https://github.com/eric19740521/b4x20220816

1.建立一個 bot
@BotFather
/newbot    取得API token (https://core.telegram.org/bots/api)
@eric20220815_bot
5610237179:AAFBwR2TFKPOf53z9AXJRugGAD4bNvVu52o

/mybots

產生之後.要先去對話...(重要)

2.https://api.telegram.org/bot{$token}/getUpdates

https://api.telegram.org/bot5610237179:AAFBwR2TFKPOf53z9AXJRugGAD4bNvVu52o/getUpdates

{"ok":true,"result":[{"update_id":87047117,
"message":{"message_id":1,"from":{"id":5785196288,"is_bot":false,"first_name":"eric","last_name":"ho","language_code":"zh-hans"},"chat":{"id":5785196288,"first_name":"eric","last_name":"ho","type":"private"},"date":1660544704,"text":"/start","entities":[{"offset":0,"length":6,"type":"bot_command"}]}},{"update_id":87047118,
"message":{"message_id":2,"from":{"id":5785196288,"is_bot":false,"first_name":"eric","last_name":"ho","language_code":"zh-hans"},"chat":{"id":5785196288,"first_name":"eric","last_name":"ho","type":"private"},"date":1660544707,"text":"test"}},{"update_id":87047119,
"message":{"message_id":3,"from":{"id":5785196288,"is_bot":false,"first_name":"eric","last_name":"ho","language_code":"zh-hans"},"chat":{"id":5785196288,"first_name":"eric","last_name":"ho","type":"private"},"date":1660544843,"text":"HI"}}]}

https://api.telegram.org/bot{token}/sendMessage?chat_id={chat_id}&text=sendMsgTest 
https://api.telegram.org/bot5610237179:AAFBwR2TFKPOf53z9AXJRugGAD4bNvVu52o/sendMessage?chat_id=5785196288&text=sendMsgTest


https://api.telegram.org/Bot{5610237179:AAFBwR2TFKPOf53z9AXJRugGAD4bNvVu52o}/sendMessage?chat_id=@MyTesting&text=你的文字



3.telegram Webhook 設定
	'設定https://api.telegram.org/bot{token}/setWebhook?url={url}


	'設定https://api.telegram.org/bot5610237179:AAFBwR2TFKPOf53z9AXJRugGAD4bNvVu52o/setWebhook?url=b234.top



