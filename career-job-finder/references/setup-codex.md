# Guided Codex setup
Follow the linked official guides for your current app, operating system and account.

## The first question
"Do you already use Codex, and are you on Windows, a Mac, Linux, or only a phone/tablet?"

Then ask only the next question needed. If it is already installed, skip installation. Record the selected route and remaining capability gaps in records/STATE.md when writable. Otherwise keep a short note the candidate can copy.

## If Codex is not installed
1. Open the [official download page](https://chatgpt.com/download/). Choose the installer for the actual operating system and check its current requirements. The [desktop quickstart](https://learn.chatgpt.com/docs/quickstart?setup=app) gives the current route; Linux users should follow the linked Linux-specific guide.
2. Let the candidate download/install it and sign in with their own ChatGPT account. Ask what they see before giving the next step. Don't request credentials or require an API key for the ordinary ChatGPT-account route.
3. The current desktop app combines ChatGPT and Codex. An older Codex app may update into the combined app; ChatGPT Classic can look different. See [migration guidance](https://help.openai.com/en/articles/20001276-moving-to-the-new-chatgpt-desktop-app). Check the actual app before prescribing an update or reinstall.
4. Select Codex in the app's mode/menu, following the current quickstart. Extract the downloaded ZIP and open its folder as a local project in Codex. No repository or terminal tutorial is required for this route.
5. Paste START-ONBOARDING.txt. Ask the assistant to read the project instructions and summarize the next step.

If only a phone/tablet is available, begin the career handoff and preference interview in the existing chat. Explain that the local-folder setup needs a suitable computer, or choose another actually supported environment. Do not make a cloud/local folder claim without checking it.

## Account and access
Use the [current Codex plan/access guide](https://help.openai.com/en/articles/11369540-using-codex-with-your-chatgpt-plan). Check the candidate's actual access and usage limits; don't recommend a paid upgrade or purchase as a prerequisite without verifying the reason and discussing it. Workspace restrictions still apply.

The familiar ChatGPT and the new Codex conversation may expose different context. Use CHATGPT-HANDOFF-PROMPT.txt in the familiar conversation, review its answer, and save the corrected career material as records/CAREER-HANDOFF.md or paste it into the onboarding conversation for Codex to save. [Memory is incomplete and account-dependent](https://help.openai.com/en/articles/8590148-memory-in-chatgpt); a summary is reference material, not a full memory migration.

## Small capability check
Have the assistant list what it can observe, not just what the product might support:
- Read the kit's AGENTS.md and name the active workspace.
- With local-write permission, save a short setup note inside this folder and read it back. A write denial is an access issue, not missing candidate information. Keep onboarding moving in chat if necessary.
- If browsing is available, open an ordinary public employer careers page. Don't enter an application.
- Check document tools before promising final PDF/DOCX production. If unavailable, prepare accurate text and give the candidate an honest export/manual route.
- Check whether actual subagent tools are callable. Configure search workers only after the candidate's goals are known. [Subagent access and usage](https://learn.chatgpt.com/docs/agent-configuration/subagents) depend on the surface; using parallel workers can consume more usage.
- Connect job-search apps only if the candidate chooses and authorizes them. Neither Indeed nor mailbox access is required just to begin.

Project AGENTS.md carries the workflow, so no global skill installation is necessary. The assistant should read career-job-finder/SKILL.md directly. The UI prompt in agents/openai.yaml applies when the skill is installed. You can use the local starter prompt immediately. [Project instructions in Codex](https://learn.chatgpt.com/docs/agent-configuration/agents-md).

## If something fails
Record the exact observed error and the affected capability. Use the current official help or a safe manual fallback. Do not ask the candidate to disable safeguards, expose secrets, create another account, or repeat broad recovery loops.

Setup is ready enough to proceed when the candidate can use the chat, retain their records, and understand which actions the environment can perform. Delegation, document export and scheduling can be added as useful capabilities become available.
