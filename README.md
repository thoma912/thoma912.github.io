# thoma912.github.io
this is my homepage.

## Local preview with Live Server

This project is intended to be previewed with the VS Code Live Server extension.

- Workspace settings pin Live Server to port `5500`.
- In remote environments such as WSL, SSH, or Dev Containers, `Go Live` may start the server without opening a local browser automatically.
- If `Port: 5500` appears in VS Code, open `http://127.0.0.1:5500/` manually or open port `5500` from the `Ports` / `Forwarded Ports` panel.

Recommended VS Code user settings:

- `Live Server: Custom Browser` should be empty.
- `Live Server: No Browser` should be disabled.

If browser auto-open still does not work in a remote session, treat that as a VS Code environment limitation rather than a site issue. The server is working as long as `http://127.0.0.1:5500/` loads.
