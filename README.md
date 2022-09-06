# Rust 디자인 패턴 

(🚧 Work in progress)

이 프로젝트는 Rust 프로그래밍 언어에서 자주 쓰이는 관용구와 디자인 패턴을 모아둔 [Rust 비공식 오픈소스 책 프로젝트](https://github.com/rust-unofficial/patterns)를 한국어로 번역하였습니다.
번역본은 [이곳](https://vlwkaos.github.io/patterns/)에서 읽으실 수 있습니다. 

## 기여하는 법

만약 도움이 될만한 내용을 알고 있거나, 그런 방법을 다른 사람들과 나누는 열정이 있다면 항상 환영입니다.
설명을 보충하거나 내용을 더 정확하게 고치는 것도 포함합니다. 
(역: 이 레포지터리의 목적은 upstream의 내용을 번역하는 것이므로 실제 내용의 추가를 원하는 경우 [원본 레포지터리](https://github.com/rust-unofficial/patterns)에 기여하시면 됩니다.)

아직 추가되지 않은 패턴, 안티패턴, 관용구는 [Umbrella issue](https://github.com/rust-unofficial/patterns/issues/116)을 확인하세요.

기여하기 전에 [Contribution guide](./CONTRIBUTING.md)를 읽어보시는 것을 추천합니다.

## mdbook 빌드하는 법

이 책은 [mdbook](https://rust-lang.github.io/mdBook/)을 사용하여 만들었습니다. 
`cargo install mdbook`를 입력하여 설치할 수 있습니다.

로컬에서 빌드하고 싶은 경우 아래 두 커맨드를 입력하세요.

- `mdbook build`

  `/book` 경로에 html 정적페이지를 만들어 배치합니다.

- `mdbook serve`

  `http://localhost:3000`(포트 변경가능)에 이 책을 서빙합니다. 변경점이 있을 때 브라우저가 자동으로 새로고침됩니다.

## License

The content of this repository is licensed under **MPL-2.0**; see [LICENSE](./LICENSE).
