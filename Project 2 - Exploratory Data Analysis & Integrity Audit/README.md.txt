---

### Step 2: Push the README to GitHub

Once you save the `README.md` file inside your `Project 2 - Exploratory Data Analysis & Integrity Audit` folder, run these commands in Command Prompt to push everything:

<Steps>
  <Step subtitle="Command Prompt" title="Stage the README file">
    Run this command inside your repo folder:
    ```cmd
    git add .
    ```
    *Verification:* Command Prompt returns smoothly to the prompt line with no error messages.
  </Step>

  <Step subtitle="Command Prompt" title="Commit the README">
    Commit the documentation update:
    ```cmd
    git commit -m "Add README documentation for Project 2"
    ```
    *Verification:* Terminal displays output confirming `README.md` was created or updated.
  </Step>

  <Step subtitle="Command Prompt" title="Push to GitHub">
    Send your final project folder and documentation up to GitHub:
    ```cmd
    git push origin main
    ```
    *Verification:* Terminal outputs transfer status ending with `main -> main`.
  </Step>
</Steps>

<ElicitationsGroup message="If you need anything else before finishing:">
  <Elicitation label="Check GitHub display" query="How will this README display when someone opens my Project 2 folder on GitHub?"/>
  <Elicitation label="Fix git push error" query="I got an error when I tried running git push."/>
</ElicitationsGroup>