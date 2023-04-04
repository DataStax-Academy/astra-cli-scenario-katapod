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

**✅ Show your databases list:**

```
astra db list
```

**✅ Create a Database `demo`** (~ 1 min)

```
astra db create demo
```

<details><summary>ℹ️ Informations:</summary>
<li>With no options the free tier will be used. Cloud is <span style="color:blue;font-family:courier new">GCP</span> and region <span style="color:blue;font-family:courier new">us-east-1</span>. 
<li>Blocking by default, the prompt will be back when the database turned <span style="color:#008800;font-family:courier new">ACTIVE</span>
<li>You can make the command asynchronous with option <span style="color:blue;font-family:courier new">--async</span>
<li>All options available with <span style="color:blue;font-family:courier new">astra help db create</span>
</details>
&nbsp;

**✅ Show your active db :**

```
astra db describe demo
```

**✅ List available keyspaces:**

```
astra db list-keyspaces demo
```

**✅ Create a new keyspace `ks2`:**

```
astra db create-keyspace demo -k ks2
```

**✅ List available regions:**

```
astra db list-regions demo
```

<details><summary>ℹ️ Informations:</summary>
<li>Free tier allows single region DB. Upgrade to _pay-as-you-go_ to access new regions.
<li>When creating region all existing data is replicated
</details>
&nbsp;

**✅ List available commands for db:**

```
astra help db
```

**✅ Connect with CQLSH to keyspace `demo`:**

```
astra db cqlsh demo -k demo
```

**✅ Create a table:**

```
CREATE TABLE cities_by_country (
 country_name text,
 name       text,
 id         int,
 state_id   text,
 state_code text,
 state_name text,
 country_id text,
 country_code text,
 latitude double,
 longitude double,
 wikiDataId text,
 PRIMARY KEY ((country_name), name)
);

describe table cities_by_country;

quit
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
