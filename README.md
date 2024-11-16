### NODEPAY AUTO REFERRAL BOT

Automatic Referral script for Nodepay Account using captcha solver and proxies.

### Tools and Components Required

1. Nodepay Account | Register: [https://app.nodepay.ai/register](https://app.nodepay.ai/register?ref=ZUCBuJaIoBXLE6J)

2. Proxies Static Residental | [FREE 10 PREMIUM PROXIES](https://www.webshare.io/?referral_code=p7k7whpdu2jg) | [Free 100 Premium Proxies](https://proxyscrape.com/?ref=odk1mmj) | Good Premium Proxies (paid): [922proxy](https://www.922proxy.com/register?inviter_code=d03d4fed), [proxy-cheap](https://app.proxy-cheap.com/r/JysUiH), [infatica](https://dashboard.infatica.io/aff.php?aff=544)

3. Captcha Solvers API keys | [2captcha.com](https://2captcha.com/?from=24541144) | [capmonster.cloud](https://capmonster.cloud/) | [anti-captcha.com](https://getcaptchasolution.com/83xoisyxvn)

4. VPS or RDP (OPTIONAL)

5. Python version 3.10

## Installation

- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)

- For Unix:
```bash
apt install python3 python3-pip -y
```
1. Clone project repository
```bash
git clone https://github.com/Rambeboy/nodepay-autoreferral-bot.git && cd nodepay-autoreferral-bot
```

2. Install dependencies
- Install requirements for Windows:
```bash
pip install -r requirements.txt
```
- Unix:
```bash
pip3 install -r requirements.txt
```
### Run the Bot

Replace the proxies example in ```proxies.txt``` to your own proxies with format:

```bash
http://host:port
http://user:pass@host:port
```
**only http proxies support for now**

#### Run Command

- Windows:
```bash
python main.py
```
- Unix
```bash
python3 main.py
```

- Insert your referral code, example: ``https://app.nodepay.ai/register?ref=XXXXXXXXXX`` this is your code: ``XXXXXXXXXX``
- Enter how many referrals you want, more referrals will result in more use of your captcha solver api credits
- Select your captcha solver service (Make sure you have credits, you can topup first)
- Select proxy usage yes or no
- Result account generated will be saved to ``accounts.txt``

## Notes

- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- This bot have delays for sending request to Nodepay API server to avoid rate limiting.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
