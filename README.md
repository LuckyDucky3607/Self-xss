# Self-XSS v1.2
## Author: github.com/thelinuxchoice/self-xss
## Twitter: twitter.com/linux_choice

Self-XSS attack using bit.ly to grab cookies tricking users into running malicious code

![80316591-0501a880-87d5-11ea-95f0-b8d4fc529bc4](https://user-images.githubusercontent.com/100312261/159116908-e7c45958-ddad-4842-88d7-41bee65a4594.png)

### How it works?

Self-XSS is a social engineering attack used to gain control of victims' web accounts by tricking users into copying and pasting malicious content into their browsers. Since Web browser vendors and web sites have taken steps to mitigate this attack by blocking pasting javascript tag, I figure out a way of doing that using Bit.ly, so we can create a redirect pointing to "website.com/javascript:malicious_code". If the user is tricked to run the code after "website.com/" the cookies of its authenticated session of website.com will be sent to the attacker.

### Features:

Port Forwarding using Serveo or Ngrok

## Legal disclaimer:

Usage of Self-XSS for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

### Usage:
```
git clone https://github.com/thelinuxchoice/self-xss
cd self-xss
bash self-xss.sh
```

### Donate!
Support the authors:
### Paypal:
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CLKRT5QXXFJY4&source=url
### LiberaPay:
<noscript><a href="https://liberapay.com/thelinuxchoice/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
