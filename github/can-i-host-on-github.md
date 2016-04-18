GitBook integrates perfectly with [GitHub](https://github.com) as a hosting solution for the source of your book. When configured correctly, this has several effects:

- The Editor will make changes directly to the GitHub repository
- GitBook will watch for update on GitHub and trigger website/pdf updates accordingly

Integrating with GitHub is done in 3 steps:

1. Setting up [permissions](#setting-up-permissions)
2. [Linking your book](#hosting-your-book-on-github) to a GitHub repository
3. Setting up [webhooks](#webhooks)

### 1. Setting up permissions

To integrate your book with GitHub, you need to authorize GitBook to access your GitHub account to some extent. From your [account's settings](https://www.gitbook.com/settings), connect your GitHub account and choose what you will allow:

- **Default permissions**: Allows you to authenticate with GitHub on GitBook.
- **Access to public repositories**: Allows editing books on your public GitHub repositories from the GitBook Web editor.
- **Access to private repositories**: Same as above, but for private repositories too.
- **Access to webhook**: Allows GitBook to create webhooks on your book repositories to trigger builds automatically.
