# Comments

## Explain yourself in code

Rather than spend your time writing the comments that explain the mess you’ve made, spend it cleaning that mess.

{% hint style="danger" %}
```php
```
{% endhint %}

{% hint style="success" %}
```php
```
{% endhint %}

## Avoid redundant comments

A comment is redundant if it describes something that adequately describes itself. Comments should say things that the code cannot say for itself.

{% hint style="danger" %}
```php
```
{% endhint %}

## Give up mandated comments

It is just plain silly to have a rule that says that every function and variable must have a comment. Comments like this just clutter up the code.

{% hint style="danger" %}
```php
```
{% endhint %}

## Don't make noise

Noise comments restate the obvious and provide no new information.

{% hint style="danger" %}
```php
```
{% endhint %}

## Avoid closing brace comments

If you find yourself wanting to mark your closing braces, try to shorten your functions instead.

{% hint style="danger" %}
```php
```
{% endhint %}

## Avoid position markers

There are rare times when they make sense, but in general they are clutter that should be eliminated.

{% hint style="danger" %}
```php
```
{% endhint %}

## Avoid HTML comments

It makes the comments hard to read in the one place where they should be easy to read—the editor/IDE.

{% hint style="danger" %}
```php
```
{% endhint %}

## There is no need for attributions and journal comments

Nowadays we have source code control systems that does it for us.

{% hint style="danger" %}
```php
```
{% endhint %}

## Don't give too much information

Don’t put interesting historical discussions or irrelevant descriptions of details into your comments.

{% hint style="danger" %}
```php
// The encoding process represents 24-bit groups of input bits as
// output strings of 4 encoded characters. Proceeding from left to right
// a 24-bit input group is formed by concatenating 3 8-bit input groups.
// These 24 bits are then treated as 4 concatenated 6-bit groups ...
```
{% endhint %}

## Don’t offer systemwide information

If you must write a comment, then make sure it describes the code it appears near.

{% hint style="danger" %}
```php
```
{% endhint %}
