# Gracielle Li: research website

This folder is the whole website. GitHub turns it into a live site for free.

## Putting it online (one time, about 15 minutes)

1. **Make a GitHub account** at github.com if you don't have one. Your username becomes part of your web address, so pick something like `gracielleli`.
2. **Create the repository.** Click the **+** in the top right corner, then **New repository**.
   - Name it exactly `yourusername.github.io` (for example, `gracielleli.github.io`).
   - Set it to **Public**.
   - Click **Create repository**.
3. **Upload the files.** On the next page, click the link that says **uploading an existing file**.
   - Unzip the folder I sent you, open it, select everything inside it (the files and the folders), and drag it all into the browser window.
   - Wait for the uploads to finish, then click the green **Commit changes** button at the bottom.
4. **Turn on the website.** Go to **Settings** (top of the repository), then **Pages** in the left menu.
   - Under "Build and deployment," set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then click **Save**.
5. **Wait a minute or two**, then visit `https://yourusername.github.io`. Your site is live.

## Updating the site later

Every change works the same way: open a file on GitHub, click the **pencil icon** (top right of the file), make your change, and click **Commit changes**. The live site updates within a minute or two.

| To change...                | Open this file              |
|-----------------------------|-----------------------------|
| A research project          | `_data/projects.yml`        |
| A publication               | `_data/publications.yml`    |
| Policy work                 | `_data/policy.yml`          |
| Your bio                    | `about.html`                |
| Contact links or email      | `_config.yml`               |

**Adding a publication:** in `_data/publications.yml`, copy an existing entry (from `- citation:` down to its last line), paste it below, and change the words. Keep the same spaces at the start of each line. The `status` line decides which section it appears in: `published`, `in press`, or `under review`.

**Adding a research project:** in `_data/projects.yml`, copy a project (from `- title:` down to the end of its description), paste it inside the right folder, and change the words. Again, keep the spaces at the start of each line the same.

**Replacing your CV:** open the `assets/cv` folder, click **Add file > Upload files**, and upload your new PDF named exactly `Gracielle-Li-CV.pdf`. It replaces the old one.

**Replacing your photo:** same steps in `assets/img`, with the file named exactly `headshot.jpg`.

If something looks broken after an edit, it is almost always a missing or extra space at the start of a line in a `.yml` file. You can always undo a change from the file's **History** button.
