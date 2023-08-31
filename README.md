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

## Donate

Brazilian users can send a PIX to the project's email address listed above.

```
Bitcoin   [BTC]     33AuPJ7Fg3MDX78vpKZB9xSnp3i1y4Dd7T
Ethereum  [ETH]     0x1a47Ed0C52b07DFE329858D3aA1847Eccc2c105a
Litecoin  [LTC]     M9Nex8ecVSpnyf1XamjHEmsZDhqF74cWPX
Dogecoin  [DOGE]    DRWTE1wNxBTHxKy5Pek1rFHEqpqjPFTbZb
Nano      [XNO]     nano_1pwu549afgpnkx4x97ad6c1nbszfuhcx8z55reowo71g78cb6cppz9r5yrqt
```
