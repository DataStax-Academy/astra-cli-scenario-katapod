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
 <a href='command:katapod.loadPage?[{"step":"step3"}]' 
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 3 of 4</span>
 <a href='command:katapod.loadPage?[{"step":"finish"}]' 
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Connecting to Databases</div>

**✅ Show status of your db:**

```
astra db status demo
```

**✅ After 48 of inactivity, in free tier, DB are hibernated. To resume use the following:**

```
astra db resume demo
```

**✅ Download the cloud secure bundle to connect with drivers:**

```
astra db download-scb demo -f /workspace/scenario-astra-cli/demo-scb.zip
ls -l /workspace/scenario-astra-cli/demo-scb.zip
```

<details><summary>ℹ️ What is the secure connect bundle ?</summary>
A Secure Connect Bundle for Datastax Astra is a zip file containing the necessary certificates, configuration files, and drivers to establish a secure connection between an application and a DataStax Astra database. It contains a set of credentials and settings for authentication, encryption, and access control. The Secure Connect Bundle ensures secure communication between the application and the database by using Transport Layer Security (TLS) and verifying the identity of both parties.
</details>
&nbsp;

**✅ Show playground for graphQL API:**

```
astra db playground demo
```

**✅ Show swagger for REST API:**

```
astra db swagger demo
```

<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"step2"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"finish"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>



