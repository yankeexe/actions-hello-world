## 👋 Hello World Action

Composite Action to greet someone.

> This action is part of the following blog:


<a href="https://yankee.dev/cicd-with-github-composite-actions">
<img src="https://i.imgur.com/yOtKXSe.jpg"  width="500" />
</a>

## 🧩 Usage

```yaml
name: Some Action

on:
  push:
    branches:
      - main

jobs:
  hello-world:
    runs-on: ubuntu-latest
    steps:
      - name: Greet someone
        uses: yankeexe/actions-hello-world@main
        with:
          who-to-greet: "everyone"
```
