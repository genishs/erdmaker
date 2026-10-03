# ERDmaker - Feedback & Issues

**English** | [한국어](#한국어)

This repository is the **public feedback and bug-report tracker** for
**[ERDmaker](https://marketplace.visualstudio.com/items?itemName=genishs.erdmaker)**,
a VS Code extension for drawing and generating entity-relationship diagrams
(Marketplace ID: `genishs.erdmaker`).

> **The source code of ERDmaker is not hosted in this repository.**
> This repo only contains the issue tracker and its templates.

## How to send feedback

### If you have a GitHub account

Open an issue in this repository:

- **[Report a bug](https://github.com/genishs/erdmaker/issues/new?template=bug_report.yml)**
- **[Request a feature](https://github.com/genishs/erdmaker/issues/new?template=feature_request.yml)**

Please search the [existing issues](https://github.com/genishs/erdmaker/issues)
first, in case someone has already reported the same thing.

### If you do not have a GitHub account

Use the **Q&A** tab on the
[Marketplace page](https://marketplace.visualstudio.com/items?itemName=genishs.erdmaker&ssr=false#qna).

### From inside VS Code (version 0.5.1 or later)

Run the command **`ERDmaker: Report Issue / Send Feedback`** from the Command
Palette. It opens a pre-filled report form with diagnostic information already
filled in (extension version, VS Code version, OS, and so on). Review the text
before you submit it.

## What to include in a report

- **Extension version** (shown in the Extensions view)
- **VS Code version** (`Help > About`)
- **Operating system**
- **Steps to reproduce** the problem, and what you expected to happen

Screenshots, log excerpts, and a small example that reproduces the problem are
very welcome.

## Privacy notice

**This is a public repository. Everyone on the internet can read what you post.**

Do **not** post:

- database connection details or passwords (host names, user names, connection strings, tokens, API keys)
- schemas, table or column names, or ERD contents that you are not allowed to make public

To reproduce a problem, please use a **reduced, anonymized example** (a few
generic tables such as `table_a`, `table_b` that still trigger the problem)
instead of your real schema.

---

## 한국어

이 레포는 VS Code 확장
**[ERDmaker](https://marketplace.visualstudio.com/items?itemName=genishs.erdmaker)**
(마켓 ID: `genishs.erdmaker`)의 **사용자 피드백·버그 신고 전용 공개 레포**입니다.

> **ERDmaker의 소스 코드는 이 레포에 없습니다.**
> 이 레포에는 이슈 트래커와 신고 양식만 있습니다.

### 피드백 남기는 방법

**GitHub 계정이 있으면** 이 레포의 Issues로 버그 신고·기능 요청을 남길 수 있습니다.

- **[버그 신고](https://github.com/genishs/erdmaker/issues/new?template=bug_report.yml)**
- **[기능 요청](https://github.com/genishs/erdmaker/issues/new?template=feature_request.yml)**

같은 내용이 이미 올라와 있을 수 있으니 [기존 이슈](https://github.com/genishs/erdmaker/issues)를
먼저 검색해 주세요.

**GitHub 계정이 없다면** 마켓 페이지의
[Q&A 탭](https://marketplace.visualstudio.com/items?itemName=genishs.erdmaker&ssr=false#qna)을
이용해 주세요.

**확장 안에서 바로 신고하기 (0.5.1 버전부터)**: 명령 팔레트에서
**`ERDmaker: Report Issue / Send Feedback`** 명령을 실행하면 진단 정보(확장 버전,
VS Code 버전, OS 등)가 미리 채워진 신고 화면이 열립니다. 제출하기 전에 내용을 한 번 확인해 주세요.

### 신고에 넣어 주실 것

- **확장 버전** (확장 보기에서 확인)
- **VS Code 버전** (`도움말 > 정보`)
- **운영체제**
- **재현 절차**와 기대했던 결과

스크린샷, 로그 일부, 문제를 재현하는 작은 예제가 있으면 큰 도움이 됩니다.

### 개인정보 주의

**이 레포는 공개 레포입니다. 올린 내용은 누구나 볼 수 있습니다.**

다음은 **올리지 마세요**.

- DB 접속 정보와 비밀번호 (호스트 이름, 사용자 이름, 접속 문자열, 토큰, API 키 등)
- 공개하면 안 되는 스키마, 테이블·컬럼 이름, ERD 내용

문제를 재현할 때는 실제 스키마 대신 **축소하고 익명화한 예제**(문제가 그대로 재현되는
`table_a`, `table_b` 같은 몇 개의 일반적인 테이블)를 사용해 주세요.
