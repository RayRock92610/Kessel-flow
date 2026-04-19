KesselFlow
Infrastructure that doesn't need a babysitter.
KesselFlow is a modular AI orchestration framework built for high-veracity automation and forensic system auditing using a Truth-First logic model. Designed and maintained by @RayRock92610.
Agent Architecture
KesselFlow coordinates 18 specialized agents across the following domains:
CI/CD pipeline management
Security scanning & vulnerability auditing
Log parsing & anomaly detection
Zero-day threat detection
Self-healing deployments
Agents operate in Termux and GitHub repo environments, ensuring tamper-proof, pragmatic workflows for complex mobile/server DevOps tasks.
Core Stack
Runtime: Python 3, FastAPI, Uvicorn
AI: Gemini (gemini-2.5-flash) via GENAI_API_KEY
Database: MongoDB (pinned)
Tunnel: Cloudflare
Platform: Android/Termux (aarch64, non-root)
Workers: ARES, FENRIS, CERBERUS
Key Strengths
Built for security engineers. KesselFlow delivers precise, reliable automation — ideal for production-ready systems running on unconventional hardware.
