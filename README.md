---
title: First Agent Template
emoji: ⚡
colorFrom: pink
colorTo: yellow
sdk: gradio
sdk_version: 5.23.1
app_file: app.py
pinned: false
tags:
- smolagents
- agent
- smolagent
- tool
- agent-course
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

Setup the packages
```
pip install -r requirements.txt
pip install 'smolagents[gradio]'
```

Run the huggingface cli
`huggingface-cli login # set the access token from the huggingface`

## Run the app
`python app.py`