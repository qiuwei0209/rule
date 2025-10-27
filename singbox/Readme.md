
# 1. sing-box 后端
- momofake.json: 带fakeip功能
- momo.json

1. 安装后端: dockerhub16/sing-box-subscribe:latest
2. 组合连接: http://192.168.2.33:5000/config/机场订阅地址&file=配置文件地址


# 2. substore 后端
sub-momofake.json

1. 安装后端: xream/sub-store
2. 在substore-订阅管理: 添加订阅，或组合订阅
3. 在substore-文件管理: (订阅和配置文件组合)
  - 文件配置sub-momofake.json
  - 脚本-链接: https://raw.githubusercontent.com/xream/scripts/main/surge/modules/sub-store-scripts/sing-box/template.js#type=组合订阅&name=singbox&outbound=🕳ℹ️🤚 手动选择|♻️ 自动选择🏷ℹ️^(?!.*(?:官网|剩余|流量|套餐|免费|订阅|到期时间|全球直连|GB|Expire Date|Traffic|ExpireDate)).*🕳ℹ️🇭🇰 香港自动🏷ℹ️^(?!.*(?:us)).*(🇭🇰|HK|hk|香港|港|HongKong)🕳ℹ️🇯🇵 日本自动🏷ℹ️^(?!.*(?:us)).*(🇯🇵|JP|jp|日本|日|Japan)🕳ℹ️🇸🇬 狮城自动🏷ℹ️^(?!.*(?:us)).*(新加坡|坡|狮城|SG|Singapore)🕳ℹ️🇩🇪 德国自动🏷ℹ️^(?!.*(?:us)).*(德国|德|DE|Germany)🕳ℹ️🇺🇸 美国自动🏷ℹ️^(?!.*(?:AUS|RUS)).*(🇺🇸|US|us|美国|美|United States)
  
  - 🕳ℹ️🤚 手动选择|♻️ 自动选择🏷ℹ️^(?!.*(?:官网|剩余|流量|套餐|免费|订阅|到期时间|全球直连|GB|Expire Date|Traffic|ExpireDate)).*
  - 🕳ℹ️🇭🇰 香港自动🏷ℹ️^(?!.*(?:us)).*(🇭🇰|HK|hk|香港|港|HongKong)
  - 🕳ℹ️🇯🇵 日本自动🏷ℹ️^(?!.*(?:us)).*(🇯🇵|JP|jp|日本|日|Japan)
  - 🕳ℹ️🇸🇬 狮城自动🏷ℹ️^(?!.*(?:us)).*(新加坡|坡|狮城|SG|Singapore)
  - 🕳ℹ️🇩🇪 德国自动🏷ℹ️^(?!.*(?:us)).*(德国|德|DE|Germany)
  - 🕳ℹ️🇺🇸 美国自动🏷ℹ️^(?!.*(?:AUS|RUS)).*(🇺🇸|US|us|美国|美|United States)

  - 脚本说明: https://github.com/xream/scripts/blob/main/surge/modules/sub-store-scripts/sing-box/template.js

# 3. fork分支内核（支持机场订阅）
内核下载: https://t.me/sing_box_reF1nd
fork-momofake.json

# 3. 仅内核
config.json

# 4. 自建节点（单节点，也可以使用substore组合自建节点）
zijian-momofake.json

# 5. iphone 1.12.x
iphone.json
