# Abyss Depth Wiki — GitHub Pages package

This folder is ready to become a GitHub Pages site.

## Upload it to GitHub

1. Create a **public** repository named `abyss-depth-wiki`.
2. Open the repository and choose **Add file → Upload files**.
3. Upload the **contents of this folder**, not the outer folder itself. The repository root must directly contain `_config.yml`, `index.md`, and the other folders.
4. Commit the uploaded files to the `main` branch.
5. Go to **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Choose branch **main**, folder **/(root)**, then press **Save**.
8. Wait a few minutes, then use the **Visit site** button shown on that page.

The address will normally be:

`https://YOUR-USERNAME.github.io/abyss-depth-wiki/`

## One required edit after uploading

Open `_config.yml` and set:

```yaml
url: "https://YOUR-USERNAME.github.io"
baseurl: "/abyss-depth-wiki"
```

Replace `YOUR-USERNAME` with your GitHub username. The `baseurl` is already set correctly if your repository is named `abyss-depth-wiki`. This makes navigation, SEO metadata, and the sitemap use the correct public address.

If you choose a different repository name, use that name for `baseurl` instead.

## Editing later

Every article is a normal Markdown file. Click a file in GitHub, click the pencil icon, edit the text, and commit the change. GitHub Pages will publish the update automatically.

Do not remove the `---` metadata block at the top of an article. It controls the page title, description, layout, and permanent URL.

## Source status

This first package was reorganized from the pasted DeviantArt journal. It includes all prose found in that file. Subjects named in its table of contents but absent from the pasted body are marked as awaiting source material rather than invented.
