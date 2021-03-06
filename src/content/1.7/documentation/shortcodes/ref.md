---
title: Internal and cross links
weight: 1
---

# Internal and cross links

## Cross links

To link to another page in the documentation, use `ref`:

    [This is a link to Configuration]({{</* ref "1.7/basics/configuration.md" */>}})

Rendered code:

[This is a link to Configuration]({{< ref "1.7/basics/installation/configuration.md" >}})

{{% notice tip %}}
Don't forget to put the link between double quotes.
{{% /notice %}}

## Internal links

To a link that points to a specific point in the current page, use `relref`:

    [This is a link to the first title]({{</* relref "#cross-links" */>}})
    
Rendered code:

[This is a link to the first title]({{< relref "#cross-links" >}})

{{% notice info %}}
**Internal links need to be "slugified" to work.**<br>
If you feel lost, here's a [tool that will slugify your titles](https://you.tools/slugify/).
{{% /notice %}}
