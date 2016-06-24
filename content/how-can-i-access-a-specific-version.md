---
search_keywords: ["content", "version", "commit"]

---

GitBook provides URLs to access the content of every successful update for a book directly:

```
<book-access-url>/v/<book-version>
```


#### What is a version?

On GitBook, a version can either be a branch, a tag or a version/commit sha of an update.

The version for an update can be found in the *Report infos*, at the bottom of an update details page.


#### What is my book access URL?

`<book-access-url>` is the access URL to the online version of your book.
It can be found in your book's settings page, under the *Domains* tab.

When using a custom domain, it is the URL you provided. For instance, this FAQ access URL is `https://help.gitbook.com`.
Otherwise, it will always look like: `https://<username>.gitbooks.io/<book-name>/content`.


#### Accessing a specific version

When accessing the URL `<book-access-url>/v/<book-version>`, GitBook will try to find the `<book-version>` as, in order:

##### A branch name

If this FAQ had a branch named `new-article`, one could access it at the URL: `https://help.gitbook.com/v/new-article`.

##### A tag name

Provided we tagged a version of this FAQ to `1.0.0`, and no branch is called the same, one could access it at the URL: `https://help.gitbook.com/v/1.0.0`.

##### A version/commit sha

Finally, one can access the very first published version of this FAQ at: `https://help.gitbook.com/v/5ff309ae0384a021ce60ffb56246c4f08ad28d05`.