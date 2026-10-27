# NEXUM Hub

One hub for your AI assistants, shared memory and projects, running on your own Windows PC.

[Website](https://projectnexum.dev/) · [Download the latest Windows installer](https://github.com/Mackaboi/nexum-releases/releases/latest) · [Release history](https://github.com/Mackaboi/nexum-releases/releases) · [Privacy](https://projectnexum.dev/privacy.html) · [Terms](https://projectnexum.dev/terms.html)

## What NEXUM does

- Connect compatible local or hosted models and organize assistants with their own roles, skills and tools.
- Give assistants access to selected folders in a shared Markdown second brain, including an existing Obsidian vault.
- Chat directly, route a request to a suitable assistant, or gather up to eight bots in a crew discussion with a lead and roles.
- Organize projects, job chats and crew channels; schedule work, reminders and background helpers.
- Review Hub-mediated approvals, activity, model usage and estimated spending.
- Optionally connect Google for Gmail search and drafts, Calendar events and Drive reading, or configure Photon iMessage integration.

The Hub coordinates models you connect. It does not include a flagship model or make a small local model equivalent to one. Model quality, speed and memory requirements depend on the model and your hardware.

## Get started on Windows

1. Use Windows 10 or 11, 64-bit, and download the installer from the [latest release](https://github.com/Mackaboi/nexum-releases/releases/latest). Choose the `NEXUM-Setup-<version>.exe` asset, not `latest.yml` or the `.blockmap` update file.
2. Review the release notes and the [Terms](https://projectnexum.dev/terms.html). The early-access installer is not code-signed; Windows may show a SmartScreen or unknown-publisher warning. Check the download source before deciding whether to proceed.
3. Open NEXUM and add a compatible local model service, such as Ollama, LM Studio or llama.cpp, or your own hosted-model provider key.
4. Choose the brain folders, skills and tools each assistant may use. Connect optional services only if you need them. Start with a small task and review the result.

Closing the window leaves the app running in the system tray; use Quit to stop it. Scheduled work and iMessage require the app to be running and the PC awake. Installed copies check GitHub for updates on opening, subject to a short interval between checks, and about every six hours; updates can download automatically and install on quit or restart.

## Privacy: local storage and external processing

Your Hub stores chats, notes, settings and saved credentials on your PC. That does **not** mean all data stays on that device.

- Hosted-model requests can include your messages, relevant notes, tool results and conversation context. Routing services and model providers handle requests under their own terms and policies.
- Optional GitHub brain sync can upload vault content to the repository you configure. Its visibility and access settings matter. Skill browsing and installation also contact GitHub.
- Google and other enabled connectors receive requests for their features. Optional Photon iMessage exchanges message content and routing information with its service.
- Update and download requests contact GitHub and its delivery infrastructure, which receive technical information such as your IP address.
- Project Nexum does not automatically receive your Hub's chats, notes or saved credentials. If you send support messages, screenshots or logs, we receive what you include. Do not send secrets.

Local inference can keep the model's processing on your PC, but enabled tools, sync or your separate model software can still make network requests. Removing a local copy does not erase copies in backups, synced repositories or third-party services. Read the [privacy policy](https://projectnexum.dev/privacy.html) before connecting sensitive data.

## Controls and limits

Hub-mediated tools use a gateway with per-tool permissions and autonomy settings. Some operations ask for approval; internal learning, scheduling and delegation have their own policies. The Gmail integration has no send-email tool. Stop everything blocks further Hub-mediated work, but cannot recall completed actions or control an outside agent's independent tools. AI can still make mistakes; check important results and keep backups.

Built-in agents get up to **50 model/tool rounds per message by default**, and may finish earlier. A round can include several tool calls. Longer jobs can take more time, increase API spending, or use more local-model context and GPU resources.

Spend figures and limits depend on configured token prices and reported usage. Thresholds can undercount or overshoot, particularly during in-progress or concurrent work. Set spending limits with your providers too. Local inference avoids cloud-model API fees but still uses hardware and electricity; model licensing and connected-service fees may apply.

## Availability and support

The Windows app is in early access. The website's Portal dashboard is a sample-data preview, not a working account service. Public Portal accounts, a hosted cloud Hub and other desktop platforms have no announced release date. The preview is separate from your installed Hub.

This is the public product and release repository. The application and website source repositories are private; downloading a release does not grant access to their source. See the [Terms](https://projectnexum.dev/terms.html) for software use conditions.

Questions or bug reports: [support@projectnexum.dev](mailto:support@projectnexum.dev). Include your app/build version, Windows version, what you expected and what happened. Redact API keys, launch codes, email content, personal notes and other sensitive information before sharing logs or screenshots. Do not post sensitive information in public GitHub reports.

Documentation reviewed 27 October 2026. Features and availability may change; check the release you install.
