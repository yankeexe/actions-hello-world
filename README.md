## 👋 Hello World Action

Composite Action to greet someone.

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
