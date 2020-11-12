# The Idempotency HTTP Request Header Field

The HTTP Idempotency request header field can be used to signal to a URI-identified resource that the client expects the operation invoked to be idempotent with provided key.

## Published draft

The latest published draft can always be found [on the IETF site](https://tools.ietf.org/html/draft-idempotency-header).

## Providing Feedback

If the draft you want to make a comment on specifies an e-mail list for feedback, please use this address. Usually, it's in the abstract.

Otherwise, feel free to [open an issue on GitHub](https://github.com/sdatspun2/idempotency-header/issues/).

## Making Contributions

If you want to submit a pull request against the draft, modify `draft.md` only. We use [kramdown-rfc2629](https://github.com/cabo/kramdown-rfc2629) to verify the content and generate markdown, plain text, and XML versions.

```
kramdown-rfc2629 draft.md
```

or

```
kdrfc draft.md
```

Then use [xml2rfc](https://xml2rfc.tools.ietf.org) to generate .html, .pdf, etc. to see results of your work.

```
xml2rfc draft.xml —html
```
