<!--
  Profile README for github.com/randomwhitehat
  Lives in a PUBLIC repo named exactly: randomwhitehat
  Files in that repo:  README.md  +  banner.svg

  TODO: link NOLA's Devpost page (and the repo, if it goes public) in Side projects.
-->

<img src="./banner.svg" alt="Kent Tan · Backend tech lead · .NET · AI agents" width="100%" />

Backend engineer from Malaysia. I lead a team by day and build systems that are supposed to stay up.
Lately I've been building AI agents, mostly to find out where they break.

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" height="28" title="C#" alt="C#" />&nbsp;
  <img src="https://cdn.simpleicons.org/dotnet/512BD4" height="28" title=".NET" alt=".NET" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="28" title="Python" alt="Python" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" height="28" title="FastAPI" alt="FastAPI" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original.svg" height="28" title="SQL Server" alt="SQL Server" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" height="28" title="PostgreSQL" alt="PostgreSQL" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" height="28" title="Redis" alt="Redis" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-original.svg" height="28" title="Firestore" alt="Firestore" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" height="28" title="Azure / Entra ID" alt="Azure" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecloud/googlecloud-original.svg" height="28" title="Google Cloud" alt="Google Cloud" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" height="28" title="Docker" alt="Docker" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuredevops/azuredevops-original.svg" height="28" title="Azure DevOps" alt="Azure DevOps" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" height="28" title="GitHub Actions" alt="GitHub Actions" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" height="28" title="Linux" alt="Linux" />&nbsp;
  <img src="https://cdn.simpleicons.org/googlegemini/8E75B2" height="28" title="Gemini" alt="Gemini" />&nbsp;
  <img src="https://cdn.simpleicons.org/claude/D97757" height="28" title="Claude Code" alt="Claude Code" />&nbsp;
  <img src="https://cdn.simpleicons.org/githubcopilot/8b949e" height="28" title="GitHub Copilot" alt="GitHub Copilot" />
</p>

<sub>also: FastEndpoints · gRPC · Dapper · EF Core · IdentityServer · Google ADK · Pydantic · Codex · Antigravity</sub>

<img src="https://github-readme-stats-three-sigma-mzav07qkk4.vercel.app/api/top-langs/?username=randomwhitehat&layout=compact&hide_border=true&bg_color=0d1117&title_color=3fb950&text_color=c9d1d9&langs_count=6" height="140" alt="Most used languages" />

### Work

<sub>Closed source, names withheld.</sub>

- **Multi-tenant e-invoicing platform**: per-tenant isolation, SSO and caching. I led the architecture and backend.
- **Workflow & approval engine**: clients configure multi-level approval chains and rules without code changes.
- **AI document OCR**: extracts structured data from documents, with config-driven switching between models and API keys.
- **API gateway**: one entry point with a shared REST + gRPC model for the services behind it.
- **Self-service onboarding**: new client setup went from hours to minutes.

### Side projects

**NOLA** is an insurance-claims agent built for the *All Things Agentic Hackathon* (2026). I did the backend and the agent, and [@Vyvienne](https://github.com/Vyvienne) did the frontend.

It works from an email inbox. It reads the damage photos, checks the policy, and either settles a small claim or hands it to a human with its reasoning. It has no tool for denying a claim, and its payout cap is enforced in code.
<br><sub>Python · Google ADK · Gemini · Cloud Run · Firestore · Pub/Sub</sub>

### How I build

- Guardrails go in code, not in the prompt.
- Every write should be safe to retry.
- Pin what you depend on, including the model version.
- Write the decision down.

---

<sub>[LinkedIn](https://www.linkedin.com/in/tan-kent/) · break it, understand it, build it better.</sub>
