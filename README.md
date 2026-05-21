# glados-pages

A GitHub Pages repo for viewing AI-generated HTML documents on the go.

Files are pushed here automatically from **glados** (my self-hosted home server at self-hosted server) by Claude Code agents. The typical workflow:

1. Claude generates an infographic or doc (usually via `/md-to-infographic`) on glados
2. Claude offers to push it here
3. It's immediately viewable at `https://zhiyi-zhang-duke.github.io/glados-pages/<filename>.html` from any device

## Contents

Files here are generated artifacts — research notes, plans, infographics, and other documents rendered as self-contained dark-mode HTML pages. Not manually authored.

## Setup notes

- Source machine: glados (Ubuntu, `jzhanglsw`)
- Push method: SSH key (`~/.ssh/id_ed25519_github`), cloned at `~/glados-pages/`
- Pages config: deploy from `master` branch, root `/`
