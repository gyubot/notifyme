# NotifyMe
## !! 서비스 개편 안내 !!
notifyme 서비스를 [heyo.io](https://heyo.io)라는 이름과 함께 새롭게 시작합니다. 안정적인 서비스와 함께 새로운 기능을 제공하기 위해, 봇과 도메인 이름을 변경하게 되었습니다. 이미 서비스를 사용하고 계신 분들은 [여기](https://heyo.io)에서 봇을 추가, 링크를 새로 발급받아 교체해주세요. 이용에 불편을 드려 죄송합니다. 편리한 알림 서비스를 위해 앞으로도 노력하겠습니다. 감사합니다.
(기존 NotifyMe서비스는 2017년 4월 14일까지 운영됩니다.)

## NotifyMe?
 - 나에게 메시지를 쉽게 보낼 수 있는 서비스입니다.
 - 생성된 링크를 호출하면, 내가 사용하는 메신저로 메시지를 받을 수 있습니다.
 - 시스템 스크립트나 프로그램 코드에 간단히 넣어 손쉽게 각종 알림을 받아보세요.

## HOW TO WORK
 - 원하는 메신저에서 NotifyMe bot을 [찾아](#지원-메신저)보세요.
 - 대화창을 열어 "도움말"로 사용방법을 확인해 보세요.
 - 생성된 링크를, 원하는 곳에 넣어 알림을 받아보세요.

## CURL example
 - GET
```
curl https://notify.gyubot.com/send/abcd1234abcd?message=hello+world
```
 - GET (token을 파라미터로 받기)
``` 
curl https://notify.gyubot.com/send?token=abcd1234abcd&message=hello+world
```
- POST
```
curl -d "token=abcd1234abcd" --data-urlencode "message=hello world" https://notify.gyubot.com/send
```

## 지원 메신저
* [line](https://line.me/R/ti/p/%40tqz0592h)
* [telegram](https://telegram.me/notifyme_telegram_bot)
* [facebook](https://www.facebook.com/notifymechatbot)
* [slack](https://slack.com/oauth/authorize?scope=bot&client_id=35489583686.130266917922)
