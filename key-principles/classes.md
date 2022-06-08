# Classes

## Classes should have one responsibility—one reason to change

Consider a class that compiles and prints a report. Such a class can be changed for two reasons. First, the content of the report could change. Second, the format of the report could change. These two things change for different causes. These two aspects of the problem are two separate responsibilities, and should be in separate classes.

{% hint style="danger" %}
```php
```
{% endhint %}

## Classes should be cohesive—cohesion results in many small classes

Classes should have a small number of instance variables. The more variables a method manipulates the more cohesive that method is to its class. Try to separate the variables and methods into many small classes such that the classes are more cohesive.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Follow the Law of Demeter

The Law of Demeter says that a method _f_ of a class _C_ should only call the methods of these:

1. _C_
2. An object created by _f_
3. An object held in an instance variable of _C_
4. An object passed as an argument to _f_

{% hint style="success" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Use data abstraction

Abstraction gives the freedom to change implementation.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Incorporate new features by extending the class

Incorporate new features by extending the class, not by making modifications to existing class, to reduce the risk of change.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Treat the Active Record as a data structure

Create separate objects that contain the business rules. Data structures expose their data. Objects expose functions that operate on data.

{% hint style="success" %}
```php
```
{% endhint %}
