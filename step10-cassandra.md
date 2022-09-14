<!-- TOP -->
<div class="top">
  <img src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-logo.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Tables with Multi-Row Partitions in Apache Cassandra®</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:aleksandr.volochnev@datastax.com">email</a> or <a href="https://dtsx.io/aleks">LinkedIn</a>.</span>
  </div>
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"step9-cassandra"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 10 of 12</span>
 <a href='command:katapod.loadPage?[{"step":"step11-cassandra"}]'
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Working with tables</div>

Try the following CQL shell commands and CQL statements that are applicable to tables. 

✅ List the names of all tables in the current keyspace:
```
DESCRIBE TABLES;
```

✅ Output all CQL statements that can be used to recreate the given table:
```
DESCRIBE TABLE movies;
```

✅ Alter the given table:
```
ALTER TABLE movies ADD country TEXT;
```

✅ Delete all rows from the table:
```
TRUNCATE movies;
```

✅ Remove the given table:
```
DROP TABLE movies;
```

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"step9-astra"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step11-astra"}]'
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>
