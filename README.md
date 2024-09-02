![Phishing Pot](https://github.com/rf-peixoto/phishing_pot/blob/main/img/phishing_pot.png)

[![rf-peixoto - Phishing Pot](https://img.shields.io/static/v1?label=rf-peixoto&message=PhishingPot&color=yellow&logo=github)](https://github.com/rf-peixoto/phishing_pot)
[![stars - Phishing Pot](https://img.shields.io/github/stars/rf-peixoto/phishing_pot?style=social)](https://github.com/rf-peixoto/phishing_pot)
[![forks - Phishing Pot](https://img.shields.io/github/forks/rf-peixoto/phishing_pot?style=social)](https://github.com/rf-peixoto/phishing_pot)

Phishing Pot is a collection of real phishing samples collected via honey pots. The purpose of this repository is to provide a reliable database for researchers and developers of detection solutions. **Pentesters and Red Teamers: This is not a repository of phishing templates!**


## Contribute

You can contribute samples to this repository, however, remember to anonymize the files hiding information that could identify the address of your Honey Pot. All sensitive information should be replaced with ```phishing@pot```. Sometimes the email address is contained within the content, either in the body of the message or in malicious URL arguments. Be sure to check these fields. If the content is encoded in base64, decode it, change the necessary values, re-encode it in base64 (respecting the indentation). You can use the command below to remove the original addresses of all files in a directory:

```
sed -i 's/your@email.com/phishing@pot/' *.eml
```

Also, follow the filename convention. You can redirect phishing messages to ``` phish.me.again@gmail.com ``` so that they are indexed too.
___
### FAQ

#### An email from my company was cataloged as phishing in this repository.
* Your website or platform allows users to register any email and there is no validation.
* Your marketing team is using leaked email lists and sending spam.
* Your servers are not configured correctly and allow attackers to carry out email spoofing attacks.
#### Can I integrate this repository into my feeds?
See ![LICENSE](https://github.com/rf-peixoto/phishing_pot/blob/main/LICENSE)

## Donate

If you found the Phishing Pot data useful, please consider donating some satoshis to keep the project going:

```
31v7bD1FkBLGhHxMQ1tmWGHyjF2wMqSSqC
```
