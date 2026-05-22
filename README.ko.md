<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI 음성 받아쓰기 크롬 확장프로그램" />
</p>

<h3 align="center">LinguaVox — AI 음성 받아쓰기 크롬 확장프로그램 · 21개 이상 언어 · 실시간 번역</h3>

<p align="center">
  단축키를 누르고 · 말하면 · 자동으로 텍스트 입력 · 실시간 회의 자막<br>
  OpenAI Whisper · 21+ 언어 · 6가지 AI 개선 모드 · 회의 모드 · API 키 불필요
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/라이선스-MIT-blue.svg" alt="라이선스" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/웹사이트-linguavox-brightgreen" alt="웹사이트" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-무료%20설치-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/대시보드-열기-orange" alt="대시보드" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/버전-3.0.0-green" alt="버전" /></a>
</p>

---

## LinguaVox란?

LinguaVox는 일상 업무에서 언어 장벽을 제거하는 크롬 확장프로그램입니다. 모국어로 자연스럽게 말하면 — OpenAI Whisper가 음성을 인식하고, 21개 이상의 언어로 번역하여, 작성 중인 웹 필드에 완성된 텍스트를 자동으로 삽입합니다. 복사-붙여넣기 없음, 앱 전환 없음, 문법 걱정 없음.

Gmail, Slack, Notion, Jira, Asana, Salesforce — 텍스트 필드가 있는 모든 웹사이트에서 작동합니다. 무료 플랜은 설정 없이 하루 20개 요청을 제공합니다. 파워 유저와 팀은 자체 OpenAI 키를 연결하여 무제한 사용할 수 있습니다.

**v3.0 — 회의 모드:** Google Meet, Zoom, Teams 등 브라우저 기반 통화의 실시간 번역 자막. 탭 오디오를 Chrome API로 캡처 → Deepgram으로 전송 → 자막이 플로팅 오버레이로 표시됩니다.

## 사용 방법

**LinguaVox 이전:** 별도 앱 실행 → 녹음 → 복사 → 브라우저로 전환 → 붙여넣기  
**LinguaVox 사용:**

```
1. 웹 필드 클릭 (Slack, Gmail, Notion, Jira…)
2. Ctrl+Space 누르고 유지  →  말하기
3. 놓기  →  ~3초 후 텍스트 자동 삽입  ✓
```

복사-붙여넣기 없음. 앱 전환 없음. 모든 사이트에서 작동.

## 지원 플랫폼

| 플랫폼 | 상태 | 비고 |
|--------|------|------|
| Slack (브라우저) | ✅ | 브라우저 레벨 단축키로 Slack 키 캡처 우회 |
| Gmail | ✅ | 작성 및 답장 필드 |
| Notion | ✅ | 모든 contenteditable 블록 |
| Jira | ✅ | 이슈 필드, 댓글, 설명 |
| Asana | ✅ | 작업 및 댓글 필드 |
| Salesforce | ✅ | CRM 입력 필드 |
| 모든 `<input>` / `<textarea>` | ✅ | 범용 |
| 모든 `contenteditable` | ✅ | React, Draft.js, Quill 호환 |
| Google Docs | ⚠️ | 제한적 — 커스텀 캔버스 에디터 |

## 주요 기능

- **API 키 불필요** — 공유 풀에서 하루 20개 무료 요청
- **자체 키 사용** — OpenAI 비용으로 무제한 사용
- **조직 계정** — 공유 키 풀, 멤버 관리, 사용량 분석
- **21+ 언어** — 한 번에 음성 인식 + 번역
- **6가지 AI 개선 모드** — 문법 교정, 비즈니스 스타일, 학술, 캐주얼, 창의적, 스마트 폴리싱
- **회의 모드** — Deepgram 기반 실시간 자막
- **개인정보 보호** — 음성 데이터 저장 없음
- **3초 이내** — 음성부터 텍스트 삽입까지
- **95%+ 정확도** — OpenAI Whisper

## AI 개선 모드

| 모드 | 기능 |
|------|------|
| 스마트 폴리싱 | 문법 교정, 명확성 개선, 의미 보존 |
| 비즈니스 스타일 | 전문적인 공식 어조 |
| 문법 교정 | 문법·맞춤법만 수정 |
| 창의적 스타일 | 생동감 있고 매력적인 문체 |
| 캐주얼 스타일 | 친근한 대화체 |
| 학술 스타일 | 공식 학술 언어 |

## 요금제

| 플랜 | 요청/일 | 조건 |
|------|---------|------|
| 무료 | 20 | Google 계정 (OAuth 로그인) |
| 자체 키 | 무제한 | Google 계정 + 개인 OpenAI API 키 |
| 조직 | 무제한 | Google 계정 + 팀 공유 API 키 |

## 자주 묻는 질문

**Slack에서도 작동하나요?**  
네. Slack은 페이지 레벨에서 키보드 이벤트를 가로챕니다. LinguaVox는 `chrome.commands.onCommand`로 브라우저 레벨에 단축키를 등록하여 Slack의 캡처를 우회합니다.

**OpenAI API 키가 필요한가요?**  
아니요. 무료 사용자는 공유 풀에서 하루 20개 요청을 받습니다. 대시보드에서 자체 키를 추가하면 무제한 사용 가능합니다.

**음성이 녹음·저장되나요?**  
아니요. 오디오는 Whisper가 실시간으로 처리 후 즉시 삭제합니다. 음성 데이터는 어디에도 보관되지 않습니다.

**지원 언어는?**  
21개 이상: 한국어, 영어, 우크라이나어, 러시아어, 스페인어, 프랑스어, 독일어, 일본어, 중국어, 아랍어, 포르투갈어, 이탈리아어, 폴란드어, 네덜란드어, 터키어, 스웨덴어, 루마니아어, 그리스어, 타갈로그어, 우르두어, 펀자브어 등.

## 커뮤니티 & 지원

| | |
|--|--|
| 📺 YouTube | [데모 영상 및 튜토리얼](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox 커뮤니티 채널](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [linguavox.slack.com 참여](https://linguavox.slack.com) |

## 데모 영상

| 사용 사례 | 시청 |
|----------|------|
| Gmail — 음성으로 이메일 작성 | [▶ 시청](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — 음성 메시지 전송 | [▶ 시청](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — 음성 받아쓰기 | [▶ 시청](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — 음성으로 게시물 작성 | [▶ 시청](https://youtube.com/watch?v=xdbDBEPWKW8) |
| 회의 모드 — 실시간 자막 | [▶ 시청](https://youtube.com/watch?v=agcMJVPKlxE) |

## 설치

**옵션 A — Chrome Web Store (권장):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — "Chrome에 추가" 클릭
2. LinguaVox 아이콘 클릭 → "Google로 로그인"
3. 어디서든 Ctrl+Space를 눌러 말하기 시작

**옵션 B — 수동 설치 (ZIP):**
1. [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)에서 `linguavox-3.0.0.zip` 다운로드
2. 폴더에 압축 해제
3. Chrome → `chrome://extensions` → "개발자 모드" 활성화 → "압축 해제된 확장 프로그램 로드" → 폴더 선택

## 링크

| | |
|--|--|
| 🌐 웹사이트 | https://linguavox.uk |
| 📊 대시보드 | https://linguavox.uk/login |
| 🔒 개인정보처리방침 | https://linguavox.uk/privacy/ |
| 🤖 AI 문서 (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 지원 | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## 라이선스

MIT — [LICENSE](LICENSE) 참조