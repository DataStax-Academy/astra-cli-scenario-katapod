<!-- TOP -->
<div class="top">
  <img class="scenario-academy-logo" src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-2023.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Getting Started with Astra CLI</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:cedrick.lunven@datastax.com">email</a> or <a href="https://dtsx.io/cedrick">LinkedIn</a>.</span>
  </div>
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"intro"}]' 
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 1 of 2</span>
 <a href='command:katapod.loadPage?[{"step":"step2"}]' 
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Installation and Setup</div>
<hr>

**✅ Install the CLI (linux):**

```
### astra
curl -Ls "https://dtsx.io/get-astra-cli" | bash
source /home/gitpod/.astra/cli/astra-init.sh
```

<details><summary>ℹ️ Informations:</summary>
<li>To install on <span style="color:blue;font-family:courier new">MacOS</span> you can either reuse the same command or leveraging brew with <span style="color:blue;font-family:courier new">brew install datastax/astra-cli/astra-cli</span>.
<li>To install on <span style="color:blue;font-family:courier new">Windows</span> reuse the script leveraging WSL2.
</details>
&nbsp;

**✅ Validate installation:**

```
clear
astra
```

**✅ Setup your token:** (_Enter your token when prompted_)**

```
astra setup
```

<details><summary>ℹ️ Informations:</summary>
<li>Command <span style="color:blue;font-family:courier new">astra setup --token AstraCS:...</span> is also available to avoid prompting.
</details>
&nbsp;

**✅ Validate your settings:**

```
astra org
```

**✅ Show configurations:**

```
astra config list
```

**✅ Show configuration file:** (_Your configuration will saved in `~/.astrarc` file_)

```
cat ~/.astrarc
```

<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"intro"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step2"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>
