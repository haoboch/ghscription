
# GhScription
Geliştiriciler İçin Dünyanın İlk Inscription Sistemi

Token'lar: [https://github.com/ghscr/ghscription/blob/main/tokens.json](https://github.com/ghscr/ghscription/blob/main/tokens.json)

Inscription'lar: [https://github.com/ghscr/ghscription/tree/main/inscriptions](https://github.com/ghscr/ghscription/tree/main/inscriptions)

Telegram Grubuna Katıl: [https://t.me/ghscription](https://t.me/ghscription)

Nasıl Çalışır?
Bu repoya aşağıdaki gösterildiği şekilde bir issue ekleyin. Daha sonra bot konu otomatik olarak bir JSON dosyasına kaydedecek.

**Token Deploy Etmek için:**

```json
{
 "p": "GRC20",
 "op": "deploy",
 "tick": "GitHub",
 "max": "1000000000",
 "lim": "2000"
}
```
Örnek: [#8](https://github.com/ghscr/ghscription/issues/8)

**Token Mint Etmek İçin:**

```json
{  
  "p": "GRC20", 
  "op": "mint", 
  "tick": "GitHub", 
  "amt": "2000"
}
```
Örnek: [#9](https://github.com/ghscr/ghscription/issues/9)

Örnek Inscription: [https://github.com/ghscr/ghscription/blob/main/inscriptions/2.json](https://github.com/ghscr/ghscription/blob/main/inscriptions/2.json)

Ratelimit nedeniyle indekslemek birkaç dakika sürebilir. Issue'lar gerçek kaynaktır.

**Token Transferi:**
Yakında gelecek
