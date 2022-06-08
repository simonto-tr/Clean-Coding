# Methods (Functions)

## Functions should be small

Functions should hardly ever be 20 lines long.

{% hint style="success" %}
```php
```
{% endhint %}

## Functions should do one thing

Function is doing more than "one thing" if you can extract another function from it with a name that is not merely a restatement of its implementation.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Follow the stepdown rule

We want every function to be followed by those at the next level of abstraction so that we can read code from top to bottom.

{% hint style="success" %}
```php
```
{% endhint %}

## Avoid nested structures

The blocks within if statements, else statements, while statements should ideally be one line long. That line can be a function call.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Use descriptive names

Don’t be afraid to make a name long. A long descriptive name is better than a short enigmatic name. A long descriptive name is better than a long descriptive comment.

{% hint style="danger" %}
```php
CreateIALOrder()
```
{% endhint %}

{% hint style="success" %}
```php
CreateInterArchivalLoanOrder()
```
{% endhint %}

## Use few arguments

The ideal number of arguments for a function is zero. Three arguments should be avoided where possible.

{% hint style="danger" %}
```php
Create(Int id=null, String csv=null, String token=null)
```
{% endhint %}

{% hint style="info" %}
Arguments are even harder from a testing point of view. Imagine the difficulty of writing all the test cases to ensure that all the various combinations of arguments work properly.
{% endhint %}

## Avoid flag arguments

Function with flag argument does more than one thing. It does one thing if the flag is true and another if the flag is false!

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Have No Side Effects

The side effect is the call to session\_start(). The checkPassword function, by its name, says that it checks the password. The name does not imply that it initializes the session.

{% hint style="danger" %}
```php
```
{% endhint %}

## Separate command from query

Functions should either do something or answer something, but not both.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Prefer exceptions to returning error codes

Returning error codes from command functions leads to deeply nested structures.

{% hint style="danger" %}
```php
```
{% endhint %}

If you use exceptions instead of returned error codes, then the error processing code can be separated from the happy path code.

{% hint style="success" %}
```php
```
{% endhint %}

## Put all code inside try block

If the keyword try exists in a function, it should be the very first word in the function and there should be nothing after the catch/finally blocks.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Write, test and refine

> When I write functions, they come out long and complicated. But I also have unit tests that cover every one of those clumsy lines of code. So then I massage and refine that code, splitting out functions, changing names, eliminating duplication.
>
> — Robert C. Martin
