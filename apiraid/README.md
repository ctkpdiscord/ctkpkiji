**Checkerの作り方** <br>
今回はCheckerを作る方法を教えます<br>
**まずAPIとは**<br>
> 人の体で言えば筋肉ですかねぇ<br>
> 脳が信号(REQUEST)を発して<br>
> 筋肉がそれを実行する<br>
> そして体が動く
> みたいな感じ
こんなこと言ってても進まないので始めます<br>
# コードの内容
> discordのapiにリクエストしていて<br>
> ステータスコードとコンテンツを取得します<br>
```py
import requests
TOKEN = "自分のトークン"
print("""
discordのトークン操作プログラム！
""")
r = requests.get("https://discord.com/api/v10/users/@me/library",headers={"authorization": TOKEN}).status_code
if r == 200:
  print("[+] WorkingToken "  + token)
else:
  print("[-] NotWorkingToken " + token)
```
# 最後に
> 筆者からのアドバイス？です<br>
> このプログラムの意味が分からないなら<br>
> そこまでセンスがないです**諦めろ**<br>
> でもここまで言われても諦めたくないなら<br>
> 地べたを這いずり<br>
> 血が滲む様な努力をし上に這い上がりましょう<br>
> まぁ規約違反してる奴に言われても心に響かないだろうけど<br>
> ここまでみてくれてありがとうございました
