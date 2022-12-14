---
layout: default
title: TimeZone
parent: \FireHub\Support
grand_parent: TheCore v0.2
has_children: false
---

<link rel="stylesheet" type="text/css" href="/css/style.css" />

# TimeZone

{: .note }
> This class is marked as **final** and can't be subclassed.


```php
final class \FireHub\TheCore\Support\LowLevel\TimeZone()
```

### ### TimeZone low level class

<sub>Fully Qualified Class Name:  **\FireHub\TheCore\Support\LowLevel\TimeZone**</sub><br>
<sub>This class is part of package:  **\FireHub\Support**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.TimeZone.php#L35)**</sub><br>
<sub>Blame:  **[view blame](https://github.com/The-FireHub-Project/TheCore/blame/v1.0/src/support/lowlevel/firehub.TimeZone.php)**</sub><br>
<sub>History:  **[view history](https://github.com/The-FireHub-Project/TheCore/commits/v1.0/src/support/lowlevel/firehub.TimeZone.php)**</sub><br>

<sub>_This class was created by Danijel Galić <danijel.galic@outlook.com>_</sub><br>
<sub>_2023 FireHub Web Application Framework_</sub><br>
<sub>_<https://opensource.org/licenses/OSL-3.0> OSL Open Source License version 3_</sub><br>
<sub>_GIT: $Id: f0140be515577fab17190af7886c2aa1e6cce3dd $ Blob checksum._</sub><br>

## Changelog
***

* **0.2.0.pre-alpha.M2** 


## Methods table
***

| Type  | Name  | Title |
| :---  | :---  | :---  |
|public static |<a href="#getdefaulttimezone()">getDefaultTimezone</a>|### Gets the default timezone used by all date/time functions in a script|
|public static |<a href="#setdefaulttimezone()">setDefaultTimezone</a>|### Sets the default timezone used by all date/time functions in a script|


# Methods
***


<h2><a name="getdefaulttimezone()"># getDefaultTimezone()</a></h2>
***

```php
public static \FireHub\TheCore\Support\LowLevel\TimeZone::getDefaultTimezone():\FireHub\TheCore\Support\Enums\DateTime\TimeZone|false
```

### ### Gets the default timezone used by all date/time functions in a script

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\TimeZone::getDefaultTimezone()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.TimeZone.php#L45)**</sub><br>

### Changelog:

* **0.2.0.pre-alpha.M2** 

### This method uses:

* [\FireHub\TheCore\Support\Enums\DateTime\TimeZone](/thecore/v0.2\FireHub\TheCore\Support\Enums\DateTime\TimeZone) _To check for valid timezone._

### This method is used by:

* *To get default timezone.*


### Returns:

* [\FireHub\TheCore\Support\Enums\DateTime\TimeZone](/thecore/v0.2\FireHub\TheCore\Support\Enums\DateTime\TimeZone) or false _Timezone, false if timezone doesn&#039;t exist._

<h2><a name="setdefaulttimezone()"># setDefaultTimezone()</a></h2>
***

```php
public static \FireHub\TheCore\Support\LowLevel\TimeZone::setDefaultTimezone(\FireHub\TheCore\Support\Enums\DateTime\TimeZone $time_zone):bool
```

### ### Sets the default timezone used by all date/time functions in a script

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\TimeZone::setDefaultTimezone()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.TimeZone.php#L63)**</sub><br>

### Changelog:

* **0.2.0.pre-alpha.M2** 

### This method is used by:

* *To set default timezone.*


### Parameters:

* [\FireHub\TheCore\Support\Enums\DateTime\TimeZone](/thecore/v0.2\FireHub\TheCore\Support\Enums\DateTime\TimeZone) $time_zone _The timezone identifier._

### Returns:

* bool _False if the timezone_identifier isn&#039;t valid, or true otherwise._


