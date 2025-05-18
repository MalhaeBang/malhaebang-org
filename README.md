# 🗣️ 말해방 팀 (MalhaeBang)

> 크롤링으로 수집한 부동산 데이터를 기반으로, 자연어 질문에 응답하는 AI 챗봇 시스템을 구축하고 있습니다.

---

## 👥 Team Members

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/sssyyysss109.png" width="80px;" alt="송선유"/><br />
      <strong>송선유</strong><br/>
      팀 리더 / AI<br/>
      <a href="https://github.com/sssyyysss109">GitHub</a>
    </td>
    <td align="center">
      <img src="https://github.com/weonyee.png" width="80px;" alt="허정원"/><br />
      <strong>허정원</strong><br/>
      AI<br/>
      <a href="https://github.com/weonyee">GitHub</a>
    </td>
    <td align="center">
      <img src="https://github.com/seongjju.png" width="80px;" alt="정성주"/><br />
      <strong>정성주</strong><br/>
      백엔드<br/>
      <a href="https://github.com/seongjju">GitHub</a>
    </td>
    <td align="center">
      <img src="https://github.com/jihyee0e.png" width="80px;" alt="고지혜"/><br />
      <strong>고지혜</strong><br/>
      AI<br/>
      <a href="https://github.com/jihyee0e">GitHub</a>
    </td>
    <td align="center">
      <img src="https://github.com/roddms.png" width="80px;" alt="김경은"/><br />
      <strong>김경은</strong><br/>
      AI<br/>
      <a href="https://github.com/roddms">GitHub</a>
    </td>
  </tr>
</table>

> 💡 팀원 소개는 프로젝트 역할 기준이며, 개발 및 운영은 전원 협업 형태로 진행됩니다.

---

## 🔧 Repository Structure

| Repo Name             | Description                                       |
|-----------------------|---------------------------------------------------|
| `malhaebang-ai`       | LLM 기반 응답 생성, 모델 학습 및 추론 모듈         |
| `malhaebang-backend`  | REST API 서버, 사용자 인증 및 DB 연동 핵심 로직     |
| `malhaebang-data`     | 데이터 수집, 전처리 파이프라인 및 분석 코드         |

---

## 🛠️ Tech Stack

- **AI / NLP**: PyTorch, Transformers, Elastic Search
- **Data Pipeline**: Python, Selenium, Pandas, MySQL
- **Infrastructure**: Kubernetes(k3s), Docker, Jenkins
- **Monitoring / Alerting**: Prometheus, Grafana, Alertmanager
- **Backend**: Spring Boot, FastAPI, Flask  
- **Frontend**: HTML/CSS/JS, Bootstrap, Thymeleaf
- **External APIs**: Kakao Maps API, Social Login API (Kakao, Naver, Google), Slack Webhook
  
---

## 💻 Team Git Convention

> 말해방 팀의 Git 커밋 메시지 컨벤션입니다.  
> 기능 개발, 버그 수정, 문서화 등 모든 커밋에 일관된 형식을 사용하여 협업의 효율성과 변경 이력을 명확히 합니다.

---

### 📌 커밋 타입 (Conventional Commits 기반)

| 타입       | 설명                                  |
|------------|----------------------------------------|
| `feat`     | ✨ 새로운 기능 추가                     |
| `fix`      | 🐛 버그 수정                            |
| `docs`     | 📚 문서 수정          |
| `style`    | 💅 코드 스타일 수정  |
| `refactor` | ♻️ 기능 변경 없는 코드 구조 개선         |
| `test`     | ✅ 테스트 코드 추가/수정                |
| `chore`    | 🔧 설정, 빌드, 기타 작업                |
| `ci`       | 🛠️ CI/CD 설정 변경                     |
| `perf`     | ⚡ 성능 개선                             |

---

### 📌 커밋 작성 가이드

- `type:` 뒤에는 공백 한 칸
- 메시지는 명확하고 간결하게 작성
- 본문에 상세 설명 추가 가능 (여러 작업 시)

---

### 📌 Issue & PR 작성 규칙

- **이슈 제목**: `[type] 요약`
  - 예시: `[feat] 사용자 로그인 기능 구현`
- **PR 제목**: 이슈 번호 포함 → `[#123] feat: 로그인 기능 추가`
- **라벨(Label)**: 커밋 타입과 동일 (`feat`, `fix`, `docs` 등)

---

## 📬 Contact

- **GitHub**: [github.com/MalhaeBang](https://github.com/MalhaeBang)
