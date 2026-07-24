# 온천천 아카이브

부산 온천천의 역사·생태·지도·시민 참여를 소개하는 정적 웹사이트입니다.

## 페이지 구성

| 페이지 | 파일 |
|---|---|
| 홈 | `index.html` |
| 역사 타임라인 | `온천천의_역사.html` → `온천천의_역사_상세.html` |
| 지도 (스토리맵) | `storymap.html` |
| 안내책자 | `온천천 아카이브.html` |
| 수생생물 도감 | `온천천의_수생생물.html` |
| 시민 참여 | `온천천의_시민참여.html` |
| AI에게 질문 | `온천천의_AI질문.html` |

빌드 과정이 필요 없는 순수 정적 사이트(HTML/CSS/JS)라 별도 설정 없이 그대로 호스팅하면 됩니다.

## GitHub Pages로 배포하기

1. GitHub에서 새 저장소를 만듭니다 (Public).
2. 이 폴더를 그 저장소에 push 합니다.
3. 저장소 **Settings → Pages**에서 Branch를 `main`(또는 `master`) / `root`로 설정합니다.
4. 잠시 후 `https://<사용자명>.github.io/<저장소명>/`에서 접속할 수 있습니다.

```bash
git remote add origin <저장소 URL>
git branch -M main
git push -u origin main
```
