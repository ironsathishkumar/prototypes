# prototypes

Clickable product prototypes (HTML, CSS and JavaScript), managed with DevContext.

## Layout

Each project has its own branch and directory:

| Project | Branch | Directory |
| --- | --- | --- |
| ArivuVazhi AI | `arivuvazhi-ai` | `arivuvazhi-ai/` |

## How changes arrive

DevContext generates or uploads a project's prototype files and proposes them as a sync. After the proposal is approved, the files are committed to the project branch and a pull request into `main` is opened, so `main` only changes through reviewed pull requests.

## Viewing a prototype

Open `<directory>/index.html` in a browser, or serve the directory locally:

```sh
python3 -m http.server 8080 --directory arivuvazhi-ai
```
