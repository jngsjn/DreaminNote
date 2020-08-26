# #3 Multi Tasking & SandBox

Date: Aug 23, 2020

차수: 3주차

# Multi tasking

UNIX → 어플리케이션, ~~백그라운드프로세스~~ → 보안상의 이유로 제한

### [multi tasking ]

⇒ 여러 작업이 동작한다고 느끼게끔

- Apple Push Notification System & Local Notification
- Task Completion
- Background Audio
- Background Location
- VoIP
- Background Download

---

# Sandbox

UNIX chroot = 자신이 포함되어있는 디렉토리를 root 디렉토리로 인식 = sandbox

api를 통해 사용자가 허락하는 한도 내에서 스마트하게 사용 가능

---
# Git Branch

1. 새로운 브랜치 생성

2. 동시에 A와 B의 동일한 부분의 내용을 수정해서 conflic 의도적으로 발생시키기

3. head가 해당하는 branch의 내용

4. 둘 중 한가지를 선택하여 불필요한 내용을 제거하여 commit 

5. pull request 활성화 → confirm merge를 하고 branch를 delete
