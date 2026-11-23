# Third-Party Licenses

This repository contains QYVORA-authored Go source and archived TUI code. It
does not vendor third-party source trees, but it depends on third-party Go
modules. License texts for direct dependencies are copied from the local Go
module cache into `third_party/licenses/`.

## Direct Go module dependencies

| Component | Version | License | Local license copy |
|---|---|---|---|
| github.com/charmbracelet/bubbles | v1.0.0 | MIT | `third_party/licenses/github.com/charmbracelet/bubbles@v1.0.0/LICENSE` |
| github.com/charmbracelet/bubbletea | v1.3.10 | MIT | `third_party/licenses/github.com/charmbracelet/bubbletea@v1.3.10/LICENSE` |
| github.com/charmbracelet/lipgloss | v1.1.0 | MIT | `third_party/licenses/github.com/charmbracelet/lipgloss@v1.1.0/LICENSE` |
| github.com/mattn/go-isatty | v0.0.20 | MIT | `third_party/licenses/github.com/mattn/go-isatty@v0.0.20/LICENSE` |
| github.com/muesli/termenv | v0.16.0 | MIT | `third_party/licenses/github.com/muesli/termenv@v0.16.0/LICENSE` |
| github.com/spf13/cobra | v1.10.2 | Apache-2.0 | `third_party/licenses/github.com/spf13/cobra@v1.10.2/LICENSE.txt` |
| github.com/spf13/pflag | v1.0.9 | BSD-3-Clause | `third_party/licenses/github.com/spf13/pflag@v1.0.9/LICENSE` |
| golang.org/x/sys | v0.38.0 | BSD-3-Clause | `third_party/licenses/golang.org/x/sys@v0.38.0/LICENSE` |

Indirect dependencies are recorded in `go.mod`/`go.sum`; add their license texts
here if they are vendored or redistributed as source.
