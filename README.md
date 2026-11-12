# 성혜정의 포트폴리오

창의적으로 AI 콘텐츠를 만드는 마케터 성혜정의 포트폴리오 웹페이지입니다.

## 파일 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 포트폴리오 본문 (HTML, CSS, JavaScript 포함) |
| `404.html` | 없는 주소로 들어왔을 때 보이는 화면 |
| `.nojekyll` | GitHub Pages가 파일을 그대로 보여주도록 하는 빈 파일 |
| `README.md` | 이 설명 문서 |

## GitHub Pages로 공개하기

1. GitHub에서 **New repository**를 눌러 저장소를 만듭니다.
   - 주소를 `https://내아이디.github.io`로 쓰려면 저장소 이름을 `내아이디.github.io`로 만듭니다.
   - 그 외 이름이면 주소는 `https://내아이디.github.io/저장소이름/`이 됩니다.
   - 저장소는 **Public**으로 만듭니다.
2. 저장소 화면에서 **uploading an existing file**을 눌러 이 폴더의 파일을 모두 끌어다 놓습니다.
   - 폴더째가 아니라 **파일들**을 올리고, `index.html`이 맨 바깥에 있어야 합니다.
   - `.nojekyll`은 점으로 시작하는 숨김 파일이라 안 보일 수 있으니 함께 올라갔는지 확인합니다.
3. **Commit changes**를 누릅니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Build and deployment**의 Source를 **Deploy from a branch**로 두고, Branch를 `main`, 폴더를 `/ (root)`로 선택한 뒤 **Save**를 누릅니다.
6. 1~3분 뒤 같은 화면 위쪽에 사이트 주소가 나타납니다.

## 내용 수정하기

- 저장소에서 `index.html`을 열고 연필 아이콘(Edit)을 눌러 고친 뒤 **Commit changes**를 누르면 몇 분 안에 반영됩니다.
- 사진을 넣으려면 `index.html`에서 `class="photo"`가 있는 줄을 찾아 아래처럼 바꾸고, 사진 파일(예: `profile.jpg`)을 같은 위치에 올립니다.

```html
<img src="profile.jpg" alt="성혜정 프로필 사진" style="width:100%;aspect-ratio:4/5;object-fit:cover;border-radius:16px">
```

## 참고

- 글꼴 Pretendard는 CDN으로 불러오므로 인터넷에 연결되어 있어야 합니다.
- 별도 도메인을 쓰려면 Settings → Pages의 **Custom domain**에 입력하면 됩니다.
