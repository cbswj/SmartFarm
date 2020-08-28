# RaspberryPi

###  블루투스 기능 생성
#### [참고링크](https://gist.github.com/ihoneymon/652be052a0727ad59601)
```
//블루투스 라이브러리 설치
sudo apt-get update
sudo apt-get upgrade

sudo apt-get install bluetooth blueman bluez
sudo apt-get install python-bluetooth

sudo reboot
```

```
//아두이노 블루투스와 페어링
sudo bluetoothctl
scan on
pair (아두이노 디바이스 아이디)
agent on
default-agent
exit
```