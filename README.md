# GitHub MCP with Copilot

**GitHub MCP = "USB-C for AI"** 🔌

## 🎯 핵심 메시지

GitHub MCP를 설정하면, **Copilot 에이전트가 Git 워크플로우를 자동으로 제어할 수 있습니다.**

```
자연어 명령 → Copilot 에이전트 → 자동 Git 작업 실행
```

## 🚀 MCP가 가능하게 하는 것

- 🔍 저장소 자동 검색
- 📊 프로젝트 코드 자동 분석
- 🐛 이슈 자동 생성
- 🌿 브랜치 자동 생성
- 💾 코드 자동 수정
- 📝 커밋 자동 생성
- 🔄 PR 자동 생성

## 💡 무엇이 다른가?

**MCP 없이:**
- 개발자가 수동으로 Git 명령어 실행
- AI와 Git 간 Context switching 필요

**MCP 있이:**
- 에이전트가 자동으로 전체 워크플로우 처리
- 개발자는 아이디어에만 집중

## 🛠️ 설정

`.vscode/mcp.json`에 GitHub MCP 서버 추가:

```json
{
  "servers": {
    "github": {
      "type": "http",
      "url": "https://api.githubcopilot.com/mcp/"
    }
  }
}
```

MCP 활성화 → Copilot 에이전트 자동으로 GitHub 액세스 가능

---

&copy; 2025 GitHub &bull; [MIT License](https://gh.io/mit)

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

