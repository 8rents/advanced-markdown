## Using Liquid Tags inside GFM markdown

> *On GitHub it’s possible to use Liquid tags (aka shopify’s quick tags) inside markdown documents.*
>
> For a full guide see the [GitHub Docs doc](https://docs.github.com/en/contributing/writing-for-github-docs/using-markdown-and-liquid-in-github-docs)

---

## Links

- [GitHub Doc on Markdown & Liquid](https://docs.github.com/en/contributing/writing-for-github-docs/using-markdown-and-liquid-in-github-docs)

## Alerts

### A Tip

*Input:*

```
> [!Tip]
> This is a tip!
```

*Output:*

> [!Tip]
>
> This is a tip!

---

### A Note

*Input:*

```
> [!Note]
> This is a note
```

*Output:*

> [!Note]
>
> This is a note

---

## Operating Systems

```text
{% mac %}

These instructions are pertinent to Mac users.

{% endmac %}
```

```text
{% linux %}

 These instructions are pertinent to Linux users.

{% endlinux %}
```
