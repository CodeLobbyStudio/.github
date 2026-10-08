# CodeLobbyStudio

**CodeLobby** is a collaborative live-coding platform for university laboratories, programming workshops and coding sessions.

Any account can create a lobby and become its **Host**. Other users join using a code or link as **Participants**. Host and Participant are roles within a specific lobby — there are no separate student and teacher account types.

The Host defines tasks and selects the programming languages available for each task. For every enabled language, the Host provides the corresponding starter code and tests. Participants solve tasks in a browser-based editor and submit their code to CodeLobby's isolated execution infrastructure for automatic evaluation.

## Repositories

- [codelobby-backend](https://github.com/CodeLobbyStudio/codelobby-backend) — API, authentication, lobbies, tasks, submissions and real-time events
- [codelobby-web](https://github.com/CodeLobbyStudio/codelobby-web) — browser UI and code editor
- [codelobby-runner](https://github.com/CodeLobbyStudio/codelobby-runner) — isolated compilation, execution and assessment of submitted code
- [codelobby-infra](https://github.com/CodeLobbyStudio/codelobby-infra) — local infrastructure, deployment and runtime configuration

## Development workflow

Work is organized in the **CodeLobby Development** GitHub Project.

1. Create a focused Issue.
2. Move it to **Ready** when it is prepared for implementation.
3. Create a feature branch linked to the Issue.
4. Open a Pull Request into `main`.
5. Get at least one review before merging.
6. Keep `main` in a working state.

The first milestone is a Java-only end-to-end MVP:

**Create Lobby → Join Lobby → Create Java Task → Solve in Browser → Submit → Compile → Test → Result**

> CodeLobby is under active development.
