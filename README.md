# HOW-TO-SETUP-A-GEMMA4-LOCALLY-ON-YOUR-PC

## REQUIREMENTS
- hardware (ram spec)
  a. Gemma 4 E2B (Smallest): Needs ~4GB to 8GB of RAM. (Runs on most modern laptops).
  b. Gemma 4 E4B (Small): Needs ~8GB to 12GB of RAM. (Great for high-end laptops/standard PCs).
  c. Gemma 4 26B / 31B (Large): Needs 24GB to 32GB+ of RAM/VRAM. (Requires a powerful gaming PC or workstation).
<img width="643" height="299" alt="image" src="https://github.com/user-attachments/assets/0afce5bb-f7f9-4610-83d7-2453b568169d" />
  check your compatible model [here](https://ollama.com/library/gemma4)
  
- powershell/any terminal

## We can use 2 methods (ollama and Lm studio)

# OLLAMA METHOD (BEST)
# STEP 1; INSTALL OLLAMA
- open your terminal/powershell and run
  <pre>
    irm https://ollama.com/install.ps1 | iex
  </pre>

<img width="921" height="439" alt="ollama for wndows" src="https://github.com/user-attachments/assets/d0349913-575d-4e87-be70-3b4f1f65838a" />


  for mac users, installing on terminal using brew

- install homebrew first
  <pre>
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  </pre>

- install ollama finally
  <pre>
    brew install ollama
  </pre>

  - check version to confirm
    <pre>
      ollama --version
    </pre>

    # STEP 2: pull gemma4 image based on your hardware specs
    i am using gemma4:26b due to my hardware

    run,
    <pre>
      ollama pull gemma4:26b
    </pre>

    note: these files are large, up to 20gb of size because they are offline models.

    ![Uploading pull 426b .png…]()

# STEP 3: RUN AI
after pulling image, run with

<pre>
  ollama run gemma4:26b
</pre>

<img width="1114" height="531" alt="run gemma" src="https://github.com/user-attachments/assets/29807817-b488-4952-b8f6-e6f709483854" />

a chat interface shows up so you can interact with the model

# LM STUDIO METHOD
# step 1: download Lm studio ai software
- visit [lm studio ai site](https://lmstudio.ai/)
- click on download to download the app
- install and use gemma3
- gemma4 is not yet on this platform

that makes methos one best

## GOODLUCKL USING GEMMA4
