---
layout: default
title: DayName
parent: \FireHub\Support
grand_parent: TheCore v0.2
has_children: false
---

<link rel="stylesheet" type="text/css" href="/css/style.css" />

# DayName

```php
enum \FireHub\TheCore\Support\Enums\DateTime\DayName
```

### ### Day names notations enum

<sub>Fully Qualified Enum Name:  **\FireHub\TheCore\Support\Enums\DateTime\DayName**</sub><br>
<sub>This enum is part of package:  **\FireHub\Support**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/firehub.DayName.php#L25)**</sub><br>
<sub>Blame:  **[view blame](https://github.com/The-FireHub-Project/TheCore/blame/v1.0/src/support/enums/datetime/firehub.DayName.php)**</sub><br>
<sub>History:  **[view history](https://github.com/The-FireHub-Project/TheCore/commits/v1.0/src/support/enums/datetime/firehub.DayName.php)**</sub><br>

<sub>_This enum was created by Danijel Galić <danijel.galic@outlook.com>_</sub><br>
<sub>_2023 FireHub Web Application Framework_</sub><br>
<sub>_<https://opensource.org/licenses/OSL-3.0> OSL Open Source License version 3_</sub><br>
<sub>_GIT: $Id: 5889a29f661249739eec2f79b4600fc6fad7386c $ Blob checksum._</sub><br>

## Changelog
***

* **0.1.3.pre-alpha.M1** 
* **0.2.0.pre-alpha.M2** _Removed FIRST_DAY and LAST_DAY enums._


## Cases table
***

| Name  | Title | Value |
| :---  | :---  | :---  |
|<a href="#today">TODAY</a>|### Date is today and time is set to 00:00:00|&#039;today&#039;|
|<a href="#yesterday">YESTERDAY</a>|### Date is yesterday and time is set to 00:00:00|&#039;yesterday&#039;|


# Cases
***


<h2><a name="today"># TODAY</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\DateTime\DayName::TODAY = 'today'
```

### ### Date is today and time is set to 00:00:00

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\DateTime\DayName::TODAY**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/firehub.DayName.php#L31)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This case is used by:

* *To get current date.*


<h2><a name="yesterday"># YESTERDAY</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\DateTime\DayName::YESTERDAY = 'yesterday'
```

### ### Date is yesterday and time is set to 00:00:00

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\DateTime\DayName::YESTERDAY**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/datetime/firehub.DayName.php#L37)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This case is used by:

* *To get yesterday's date.*


