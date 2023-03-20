<div align="center">
    <h1>boj-user-translation</h1>
    <p><a href="https://github.com/kiwiyou/boj-user-translation/blob/main/README.md">English</a> / 한국어</p>
</div>

백준 온라인 저지 문제를 위한 유저 번역 저장소입니다.

번역물을 실제 문제에 적용하고 싶으시다면 [o-ey](https://github.com/kiwiyou/o-ey)를 참조해 주세요.

## 번역 참여 방법

Git과 Python 3이 필요합니다.

이 저장소를 포크(페이지 오른쪽 위)하시고, 로컬에 클론(페이지 위쪽 녹색 버튼)하신 뒤에,
Git Bash에서 클론한 저장소로 들어가 아래 명령어를 입력해 주세요.

```bash
python3 new-tr.py <문제 번호> <언어 코드> <번역자명>
```

- `<언어 코드>` 자리에는 [IETF language tag](https://www.wikiwand.com/en/IETF_language_tag)를 삽입하되, `-`는 `_`로 바꿔 주세요. (예: 한국어라면 `ko_KR`, 영어라면 `en_US`).

`src/<문제번호>/<언어 코드>-<번역자명>.json` 파일이 생성되고, `index` 파일이 수정됩니다.

생성된 파일을 번역하시고 푸시하신 뒤에 Pull Request를 보내 주세요.