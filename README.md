# NotifyMe
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
