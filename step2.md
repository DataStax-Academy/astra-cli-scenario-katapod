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
 <a href='command:katapod.loadPage?[{"step":"step1"}]' 
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 1 of 2</span>
 <a href='command:katapod.loadPage?[{"step":"step3"}]' 
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Working with Databases</div>

**✅ Create a Database `demo`**

> __

```
astra db create demo
```

<details><summary>ℹ️ Informations:</summary>
<li>As no options provided the free tier region will be used: <span style="color:blue;font-family:courier new">GCP</span> in region <span style="color:blue;font-family:courier new">us-east-1</span>. 
<li>Default behaviour is a blocking command. The prompt will be back when the database turned <span style="color:#008800;font-family:courier new">ACTIVE</span>
</details>
&nbsp;

**✅ Show your active db :**

```
astra db describe demo
```



<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"step1"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step3"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>
