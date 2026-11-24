# AIM the SPACE — 앱 안내 사이트

하루와 랠리, 랩포토 세 앱의 소개 · 지원 · 개인정보 처리방침을 한 페이지에서 탭으로 제공합니다.
GitHub Pages로 배포됩니다.

| 용도 | 주소 |
| --- | --- |
| 하루 지원 · 마케팅 | `https://aimthespace.github.io/apps/#haru` |
| 하루 개인정보 처리방침 | `https://aimthespace.github.io/apps/haru/privacy.html` |
| 랠리 지원 · 마케팅 | `https://aimthespace.github.io/apps/#rally` |
| 랠리 개인정보 처리방침 | `https://aimthespace.github.io/apps/rally/privacy.html` |
| 랩포토 지원 · 마케팅 | `https://aimthespace.github.io/apps/#labphoto` |
| 랩포토 개인정보 처리방침 | `https://aimthespace.github.io/apps/labphoto/privacy.html` |

기존 `haru-privacy` 저장소는 이미 심사에 제출된 주소라 그대로 둡니다.

## 구조

```
index.html        탭 세 개(하루 · 랠리 · 랩포토). 주소 끝에 #haru / #rally / #labphoto 로 바로 열 수 있다.
style.css         세 앱 공통. 색은 CSS 변수로, 다크 모드 대응.
haru/privacy.html
rally/privacy.html
labphoto/privacy.html
```

고칠 일이 생기면 `index.html`의 해당 `<section class="panel">` 안만 손보면 됩니다.
