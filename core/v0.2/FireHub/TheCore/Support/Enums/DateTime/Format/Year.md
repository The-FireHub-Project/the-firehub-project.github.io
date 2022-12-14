---
layout: default
title: Year
parent: \FireHub\Support
grand_parent: TheCore v0.2
has_children: false
---

<link rel="stylesheet" type="text/css" href="/css/style.css" />

# Year

```php
enum \FireHub\TheCore\Support\Enums\DateTime\Format\Year
```

### ### Year format enum

<sub>Fully Qualified Enum Name:  **\FireHub\TheCore\Support\Enums\DateTime\Format\Year**</sub><br>
<sub>This enum is part of package:  **\FireHub\Support**</sub><br>
<sub>Implements:  **[](/thecore/v0.2)**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/format/firehub.Year.php#L23)**</sub><br>
<sub>Blame:  **[view blame](https://github.com/The-FireHub-Project/TheCore/blame/v1.0/src/support/enums/datetime/format/firehub.Year.php)**</sub><br>
<sub>History:  **[view history](https://github.com/The-FireHub-Project/TheCore/commits/v1.0/src/support/enums/datetime/format/firehub.Year.php)**</sub><br>

<sub>_This enum was created by Danijel Galić <danijel.galic@outlook.com>_</sub><br>
<sub>_2023 FireHub Web Application Framework_</sub><br>
<sub>_<https://opensource.org/licenses/OSL-3.0> OSL Open Source License version 3_</sub><br>
<sub>_GIT: $Id: 6c7873c3efa0003f280612d00c53a4d1b60265da $ Blob checksum._</sub><br>

## Changelog
***

* **0.2.0.pre-alpha.M2** 


## Cases table
***

| Name  | Title | Value |
| :---  | :---  | :---  |
|<a href="#long">LONG</a>|### Full numeric representation of a year, at least 4 digits, with - for years BCE|&#039;Y&#039;|
|<a href="#short">SHORT</a>|### Two digit representation of a year|&#039;y&#039;|
|<a href="#leap">LEAP</a>|### 1 if it is a leap year, 0 otherwise|&#039;L&#039;|


# Cases
***


<h2><a name="long"># LONG</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\DateTime\Format\Year::LONG = 'Y'
```

### ### Full numeric representation of a year, at least 4 digits, with - for years BCE

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\DateTime\Format\Year::LONG**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/format/firehub.Year.php#L34)**</sub><br>

### Changelog:

* **0.2.0.pre-alpha.M2** 

### This case is used by:

* *As format type.*


### Examples:

```php
-0055, 0787, 1999, 2003, 10191
```



<h2><a name="short"># SHORT</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\DateTime\Format\Year::SHORT = 'y'
```

### ### Two digit representation of a year

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\DateTime\Format\Year::SHORT**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/format/firehub.Year.php#L45)**</sub><br>

### Changelog:

* **0.2.0.pre-alpha.M2** 

### Examples:

```php
99 or 03
```



<h2><a name="leap"># LEAP</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\DateTime\Format\Year::LEAP = 'L'
```

### ### 1 if it is a leap year, 0 otherwise

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\DateTime\Format\Year::LEAP**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/format/firehub.Year.php#L56)**</sub><br>

### Changelog:

* **0.2.0.pre-alpha.M2** 

### This case is used by:

* *As format type.*


### Examples:

```php
1 or 0
```



