<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [gatsby-plugin-next-seo](./gatsby-plugin-next-seo.md) &gt; [BaseSeoProps](./gatsby-plugin-next-seo.baseseoprops.md) &gt; [twitter](./gatsby-plugin-next-seo.baseseoprops.twitter.md)

## BaseSeoProps.twitter property

The twitter configuration object.

<b>Signature:</b>

```typescript
twitter?: Twitter;
```

## Remarks

Twitter will read the `og:title`<!-- -->, `og:image` and `og:description` tags for their card, this is why `gatsby-plugin-next-seo` omits `twitter:title`<!-- -->, `twitter:image` and `twitter:description` so not to duplicate.

Some tools may report this an error. See \[Issue \#14\](https://github.com/garmeeh/gatsby-plugin-next-seo/issues/14)
