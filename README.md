# 이성현 포트폴리오

게임 클라이언트 프로그래머 이성현의 포트폴리오입니다 → **https://mintpink0.github.io**

- [INSTRUCTION](projects/instruction.html) — Unity 6 1인칭 공포 게임, 성과공유회 우수상 (참여 팀 중 1위)
- [Code Dungeon](projects/code-dungeon.html) — C++ · DirectX 12 자체 엔진 3D 던전 액션 (졸업작품)

---

## 사이트 구조

빌드 도구 없이 바로 올리는 정적 사이트(GitHub Pages)입니다. `.nojekyll` 이 있어 GitHub이 파일을 그대로 보여 줍니다.

## 올리는 법
1. GitHub에 `<아이디>.github.io` 이름으로 **공개** 저장소를 만듭니다 (예: `mintpink0.github.io`).
2. 이 폴더의 내용 전부(숨김 파일 `.nojekyll` 포함)를 저장소 맨 위에 올리고 `main` 에 커밋합니다.
3. 저장소 Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `(root)`.
4. 1–2분 뒤 `https://<아이디>.github.io` 에서 확인합니다.

| 파일 | 내용 |
|---|---|
| `index.html` | 첫 화면 (소개 · 프로젝트 · 기술 스택) |
| `projects/instruction.html` | INSTRUCTION 상세 |
| `projects/code-dungeon.html` | Code Dungeon 상세 |
| `assets/css/site.css` | 디자인 (맨 위 `:root` 의 색 · 글꼴 값) |
| `assets/img/` | 이미지 · 영상 |

## PDF 만들기
각 프로젝트 페이지를 크롬에서 열고 인쇄(Ctrl+P) → 대상 `PDF로 저장`, 용지 A4, **배경 그래픽 켜기**.
인쇄할 때는 목차 · 버튼 · 영상이 빠지고 링크 주소가 글자로 들어갑니다.
