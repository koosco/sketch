# sketch

설계를 공부하면서 정리한 노트를 모아 두는 저장소.

- 문서 원본: [`docs/`](docs/)
- 사전 저장 방식과 패턴: [`docs/dictionary-storage/`](docs/dictionary-storage/README.md)

## 문서 사이트

`docs/` 폴더가 그대로 GitHub Pages 사이트가 된다. 빌드 단계가 없는 정적 사이트(Docsify)라서 Markdown 파일만 고치면 반영된다.

로컬에서 보려면 다음 명령을 실행한 뒤 `http://localhost:4173` 을 연다.

```bash
python3 -m http.server 4173 --directory docs
```

문서를 추가할 때는 `docs/` 아래에 Markdown 파일을 만들고 `docs/_sidebar.md` 에 링크를 한 줄 추가한다.
