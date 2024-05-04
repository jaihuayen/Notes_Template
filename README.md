# Note Template

Fork From: https://github.com/sleepymalc/LaTeX-Template

Step 1: Clone the repository:

```bash
git clone https://github.com/jaihuayen/Notes_Template.git
```

Step 2: Pull the docker image:

```bash
docker pull ghcr.io/xu-cheng/texlive-full:latest
```

Step 3: Setting the VSCode Enviornment:

Open the `settings.json` and add the following config:

```json
  "latex-workshop.docker.enabled": true,
  "latex-workshop.docker.image.latex": "ghcr.io/xu-cheng/texlive-full",
```