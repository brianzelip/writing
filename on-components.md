# On components

## in general

John Otander via MDX writing has expressed well, with the clarity of learning from lots of others' ideas on the subject already, some insights into the reaches of component thinking, going so far as to impact markdown even.

- [Authorable Format](https://johno.com/authorable-format)
- (something else he wrote, which were his own notes about setting up Vue and mdx, but I can't find the linnk!)

## in js

Webpack is certainly a cornerstone of this movement.

[@jantimon/html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) has docs that are written _about_ complex topics, but _in a way_ that I can understand. It shows componentness.

## in css

Great article by Giuseppe Gurgone, [Margins and Composability in CSS](http://giuseppegurgone.com/margins-and-composability-in-css/):

> "Treat code like Lego. Break code into the smallest little blocks possible." — @csswizardry (via @stubbornella) #btconf
> May 27, 2013
> via https://twitter.com/smashingmag/status/339024926197559296

> _Reusability_ and _composabilty_ are the key to success.

> UI components instead should be self-contained. The component root should be free of any rule that may affect composability, specifically:
>
> - margins
> - layout rules like position (absolute or fixed), float, transform, etc
> - width

> My suggestion is to always reset peripheral margins and to not set margins on the component root at all.
