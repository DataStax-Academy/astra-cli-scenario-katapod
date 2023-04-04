<!-- TOP -->
<div class="top">
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
<span class="step-count"> Step 1 of 4</span>
 <a href='command:katapod.loadPage?[{"step":"step2"}]' 
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Installation and Setup</div>

**✅ Install the CLI (linux):**

```
curl -Ls "https://dtsx.io/get-astra-cli" | bash
source /home/gitpod/.astra/cli/astra-init.sh
```

<details><summary>ℹ️ Informations:</summary>
<li>To install on <span style="color:blue;font-family:courier new">MacOS</span>, reuse same command or <span style="color:blue;font-family:courier new">brew install datastax/astra-cli/astra-cli</span>.
<li>To install on <span style="color:blue;font-family:courier new">Windows</span> reuse the script leveraging <span style="color:blue;font-family:courier new">WSL2</span>
</details>
&nbsp;

**✅ Validate installation:**

```
clear
astra --version
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
clear
astra
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
