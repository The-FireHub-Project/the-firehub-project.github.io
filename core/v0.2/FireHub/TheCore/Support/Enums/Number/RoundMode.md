---
layout: default
title: RoundMode
parent: \FireHub\Support
grand_parent: TheCore v0.2
has_children: false
---

<link rel="stylesheet" type="text/css" href="/css/style.css" />

# RoundMode

```php
enum \FireHub\TheCore\Support\Enums\Number\RoundMode
```

### ### Round mode number enum

<sub>Fully Qualified Enum Name:  **\FireHub\TheCore\Support\Enums\Number\RoundMode**</sub><br>
<sub>This enum is part of package:  **\FireHub\Support**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/number/firehub.RoundMode.php#L23)**</sub><br>
<sub>Blame:  **[view blame](https://github.com/The-FireHub-Project/TheCore/blame/v1.0/src/support/enums/number/firehub.RoundMode.php)**</sub><br>
<sub>History:  **[view history](https://github.com/The-FireHub-Project/TheCore/commits/v1.0/src/support/enums/number/firehub.RoundMode.php)**</sub><br>

<sub>_This enum was created by Danijel Galić <danijel.galic@outlook.com>_</sub><br>
<sub>_2023 FireHub Web Application Framework_</sub><br>
<sub>_<https://opensource.org/licenses/OSL-3.0> OSL Open Source License version 3_</sub><br>
<sub>_GIT: $Id: 128150c854fa07b205a4a5bfb9576f8d96d26fbe $ Blob checksum._</sub><br>

## Changelog
***

* **0.1.3.pre-alpha.M1** 


## Cases table
***

| Name  | Title | Value |
| :---  | :---  | :---  |
|<a href="#php_round_half_up">PHP_ROUND_HALF_UP</a>|### Rounds number away from zero when it is half way there, making 1.5 into 2 and -1.5 into -2|1|
|<a href="#php_round_half_down">PHP_ROUND_HALF_DOWN</a>|### Rounds number towards zero when it is half way there, making 1.5 into 1 and -1.5 into -1|2|
|<a href="#php_round_half_even">PHP_ROUND_HALF_EVEN</a>|### towards the nearest even value when it is half way there, making both 1.5 and 2.5 into 2|3|
|<a href="#php_round_half_odd">PHP_ROUND_HALF_ODD</a>|### Rounds number towards the nearest odd value when it is half way there, making 1.5 into 1 and 2.5 into 3|4|


# Cases
***


<h2><a name="php_round_half_up"># PHP_ROUND_HALF_UP</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_UP = 1
```

### ### Rounds number away from zero when it is half way there, making 1.5 into 2 and -1.5 into -2

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_UP**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/number/firehub.RoundMode.php#L29)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This case is used by:

* *To round numbers away from zero when it is half way there.*


<h2><a name="php_round_half_down"># PHP_ROUND_HALF_DOWN</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_DOWN = 2
```

### ### Rounds number towards zero when it is half way there, making 1.5 into 1 and -1.5 into -1

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_DOWN**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/number/firehub.RoundMode.php#L35)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

<h2><a name="php_round_half_even"># PHP_ROUND_HALF_EVEN</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_EVEN = 3
```

### ### towards the nearest even value when it is half way there, making both 1.5 and 2.5 into 2

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_EVEN**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/number/firehub.RoundMode.php#L41)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

<h2><a name="php_round_half_odd"># PHP_ROUND_HALF_ODD</a></h2>
***

```php
\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_ODD = 4
```

### ### Rounds number towards the nearest odd value when it is half way there, making 1.5 into 1 and 2.5 into 3

<sub>Fully Qualified Case Name:  **\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_ODD**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/enums/number/firehub.RoundMode.php#L47)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

