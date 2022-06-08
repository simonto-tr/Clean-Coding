# Naming Matters

What does the list represent?

{% hint style="danger" %}
`List<decimal> p = new List<decimal>() {5.50m, 1.48m};`

`decimal t = 0;`

`foreach(var i in p)`

`{`

&#x20; `t += i;`

`}`

`return t;`
{% endhint %}

{% hint style="success" %}
`List<decimal> prices = new List<decimal>() {5.50m, 1.48m};`

`decimal total = 0;`

`foreach(var price in prices)`

`{`

&#x20; `total += price;`

`}`

`return total;`
{% endhint %}

