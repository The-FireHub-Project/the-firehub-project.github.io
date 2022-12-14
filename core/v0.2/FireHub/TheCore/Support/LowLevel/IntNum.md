---
layout: default
title: IntNum
parent: \FireHub\Support
grand_parent: TheCore v0.2
has_children: false
---

<link rel="stylesheet" type="text/css" href="/css/style.css" />

# IntNum

{: .note }
> This class is marked as **final** and can't be subclassed.


```php
final class \FireHub\TheCore\Support\LowLevel\IntNum()
```

### ### Integer low level class

<sub>Fully Qualified Class Name:  **\FireHub\TheCore\Support\LowLevel\IntNum**</sub><br>
<sub>This class is part of package:  **\FireHub\Support**</sub><br>
<sub>Parent class:  **[\FireHub\TheCore\Support\LowLevel\Num](/thecore/v0.2\FireHub\TheCore\Support\LowLevel\Num)**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.IntNum.php#L32)**</sub><br>
<sub>Blame:  **[view blame](https://github.com/The-FireHub-Project/TheCore/blame/v1.0/src/support/lowlevel/firehub.IntNum.php)**</sub><br>
<sub>History:  **[view history](https://github.com/The-FireHub-Project/TheCore/commits/v1.0/src/support/lowlevel/firehub.IntNum.php)**</sub><br>

<sub>_This class was created by Danijel Galić <danijel.galic@outlook.com>_</sub><br>
<sub>_2023 FireHub Web Application Framework_</sub><br>
<sub>_<https://opensource.org/licenses/OSL-3.0> OSL Open Source License version 3_</sub><br>
<sub>_GIT: $Id: f2bc9409b7c56b5f9b166c6935779068dbe5ee20 $ Blob checksum._</sub><br>

## Changelog
***

* **0.1.3.pre-alpha.M1** 


## Methods table
***

| Type  | Name  | Title |
| :---  | :---  | :---  |
|public static |<a href="#isint()">isInt</a>|### Checks if value is integer|
|public static |<a href="#divide()">divide</a>|### Integer division|
|inherited public static |<a href="#numeric()">numeric</a>|### Checks if value is numeric|
|inherited public static |<a href="#absolute()">absolute</a>|### Get absolute value|
|inherited public static |<a href="#round()">round</a>|### Rounds a float|
|inherited public static |<a href="#ceil()">ceil</a>|### Round fractions up|
|inherited public static |<a href="#floor()">floor</a>|### Round fractions down|
|inherited public static |<a href="#max()">max</a>|### Find highest value|
|inherited public static |<a href="#min()">min</a>|### Find lowest value|
|inherited public static |<a href="#power()">power</a>|### Exponential expression|


# Methods
***


<h2><a name="numeric()"># numeric()</a></h2>
***

```php
public static \FireHub\TheCore\Support\LowLevel\Num::numeric(mixed $value)
```

### ### Checks if value is numeric

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::numeric()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L54)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This method uses:

* [\FireHub\TheCore\Support\LowLevel\DataIs::numeric()](/thecore/v0.2\FireHub\TheCore\Support\LowLevel\DataIs#numeric()) _To check if value is numeric._

### Parameters:

* mixed $value _Value to check._

<h2><a name="absolute()"># absolute()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::absolute(int|float $number)
```

### ### Get absolute value

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::absolute()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L70)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### Parameters:

* int or float $number _The numeric value to process._

<h2><a name="round()"># round()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::round(int|float $number, int $precision, \FireHub\TheCore\Support\Enums\Number\RoundMode $round_mode = RoundMode::PHP_ROUND_HALF_UP)
```

### ### Rounds a float

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::round()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L94)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This method uses:

* [\FireHub\TheCore\Support\Enums\Number\RoundMode::PHP_ROUND_HALF_UP](/thecore/v0.2\FireHub\TheCore\Support\Enums\Number\RoundMode#php_round_half_up) _To round numbers away from zero when it is half way there._

### Parameters:

* int or float $number _The value to round._
* int $precision _[optional] 
Number of decimal digits to round to._
* [\FireHub\TheCore\Support\Enums\Number\RoundMode](/thecore/v0.2\FireHub\TheCore\Support\Enums\Number\RoundMode) $round_mode = RoundMode::PHP_ROUND_HALF_UP _[optional] 
Specify the mode in which rounding occurs._

<h2><a name="ceil()"># ceil()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::ceil(int|float $number):int
```

### ### Round fractions up

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::ceil()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L112)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This method is used by:

* *To get ceil value.*


### Parameters:

* int or float $number _The value to round up._

### Returns:

* int _Rounded number up to the next highest integer._

<h2><a name="floor()"># floor()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::floor(int|float $number):int
```

### ### Round fractions down

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::floor()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L128)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This method is used by:

* *To get floor value.*


### Parameters:

* int or float $number _The value to round down._

### Returns:

* int _Rounded number up to the next lowest integer._

<h2><a name="max()"># max()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::max(mixed $value, mixed ...$values):mixed
```

### ### Find highest value

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::max()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L147)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This method is used by:

* *To get max value.*


### Parameters:

* mixed $value _Any comparable value._
* variadic mixed $values _Any comparable values._

### Returns:

* mixed _Parameter value considered highest according to standard comparisons. If an empty array is passed, then false will be returned._

<h2><a name="min()"># min()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::min(mixed $value, mixed ...$values):mixed
```

### ### Find lowest value

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::min()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L166)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### Parameters:

* mixed $value _Any comparable value._
* variadic mixed $values _Any comparable values._

### Returns:

* mixed _Parameter value considered lowest according to standard comparisons. If an empty array is passed, then false will be returned._

<h2><a name="power()"># power()</a></h2>
***

```php
final public static \FireHub\TheCore\Support\LowLevel\Num::power(int|float $base, int|float $exponent):int|float
```

### ### Exponential expression

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\Num::power()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.Num.php#L185)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### Parameters:

* int or float $base _The base to use._
* int or float $exponent _The exponent._

### Returns:

* int or float _Base raised to the power of exponent. If both arguments are non-negative integers and the result can be represented as an integer, the result will be returned with int type, otherwise it will be returned as a float._

<h2><a name="isint()"># isInt()</a></h2>
***

```php
public static \FireHub\TheCore\Support\LowLevel\IntNum::isInt(mixed $value)
```

### ### Checks if value is integer

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\IntNum::isInt()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.IntNum.php#L46)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### This method uses:

* [\FireHub\TheCore\Support\LowLevel\DataIs::int()](/thecore/v0.2\FireHub\TheCore\Support\LowLevel\DataIs#int()) _To check if value is integer._

### Parameters:

* mixed $value _Value to check._

<h2><a name="divide()"># divide()</a></h2>
***

```php
public static \FireHub\TheCore\Support\LowLevel\IntNum::divide(int $dividend, int $divisor):int
```

### ### Integer division

<sub>Fully Qualified Method Name:  **\FireHub\TheCore\Support\LowLevel\IntNum::divide()**</sub><br>
<sub>Source code:  **[view source code](https://github.com/The-FireHub-Project/TheCore/blob/v1.0/src/support/lowlevel/firehub.IntNum.php#L65)**</sub><br>

### Changelog:

* **0.1.3.pre-alpha.M1** 

### Parameters:

* int $dividend _Number to be divided._
* int $divisor _Number which divides the $dividend._

### Returns:

* int _The integer quotient of the division of $dividend by $divisor._


