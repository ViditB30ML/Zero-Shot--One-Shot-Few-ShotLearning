Welcome !
Here we have various ML learning techniques from verified sources. This repository will help us to dive into core concepts of Machine Learning.

# Source - https://stackoverflow.com/a/69921468
# Posted by VonC, modified by community. See post 'Timeline' for change history
# Retrieved 2026-08-28, License - CC BY-SA 4.0

name: Mixed inputs

on:
  workflow_dispatch:
    inputs:
      name:
        type: choice
        description: Who to greet
        options: 
        - monalisa
        - cschleiden
      message:
        required: true
      use-emoji:
        type: boolean
        description: Include 🎉🤣 emojis
      environment:
        type: environment

jobs:
  greet:
    runs-on: ubuntu-latest

    steps:
    - name: Send greeting
      run: echo "${{ github.event.inputs.message }} ${{ fromJSON('["", "🥳"]')[github.event.inputs.use-emoji == 'true'] }} ${{ github.event.inputs.name }}"


