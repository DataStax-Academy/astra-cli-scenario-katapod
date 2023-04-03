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

### Installation 
<hr>

**✅ Install the CLI (linux):**

> To install on MacOS you can either reuse the same command or leveraging brew with `brew install datastax/astra-cli/astra-cli`

```
### astra
curl -Ls "https://dtsx.io/get-astra-cli" | bash
source /home/gitpod/.astra/cli/astra-init.sh
```

**✅ Validate installation:**

```
astra
```

**✅ Setup your token:**

- Enter your token in the prompt when asked.

```
astra setup
```

> `astra setup --token AstraCS:...` is also available as a command with no prompt.

**✅ Validate your settings:**

```
astra org
```

**✅ Show configurations:**

```
astra config list
```

- The CLI allows you to work on multiple organizations.

```
astra help config
```

- Your configuration will saved in `~/.astrarc` file

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
