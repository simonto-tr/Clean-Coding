# Meaningful Names

## Avoid Abbreviations

What does the list represent?

{% hint style="danger" %}
usr
{% endhint %}

{% hint style="success" %}
user
{% endhint %}

## Use pronounceable names

How can you discuss it without sounding like crazy?

{% hint style="success" %}
class Customer
{% endhint %}

{% hint style="danger" %}
class CstmrRcrd
{% endhint %}

## Avoid disinformation

Of what type is the account list? String? Array of strings? Array of objects?

{% hint style="danger" %}
accountList
{% endhint %}

{% hint style="success" %}
accounts
{% endhint %}

## Avoid similar shapes

How long does it take to spot the subtle difference?

{% hint style="danger" %}
class ControllerForEfficientHandlingOfStrings\
class ControllerForEfficientStorageOfStrings
{% endhint %}

## Make meaningful distinctions

How do these different names convey different meanings?

{% hint style="danger" %}
class Product\
class ProductInfo\
class ProductData
{% endhint %}



## Add context by using prefixes

What does the state represent? Condition or country?

{% hint style="danger" %}
state
{% endhint %}

{% hint style="success" %}
addressState
{% endhint %}

{% hint style="info" %}
A better solution is to create a class named Address. If you need to differentiate between MAC addresses, port addresses, and Web addresses, consider PostalAddress, MAC, and URI.
{% endhint %}



## Methods should have verb names

{% hint style="success" %}
function postPayment()\
function deletePage()\
function save()
{% endhint %}

## Classes should have noun names

{% hint style="success" %}
class Customer\
class WikiPage\
class Account
{% endhint %}

## Avoid words (in the name of a class)

{% hint style="danger" %}
Manager\
Processor\
Data\
Info
{% endhint %}
