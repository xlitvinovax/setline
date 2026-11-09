# Setline prototype

Setline is a mobile-friendly strength training log. It lets you create workout plans, log and edit sets, use a rest timer, and review completed workouts.

## Run locally

Open `index.html` for a quick preview. For consistent browser storage, run this command from the folder containing the file and open [localhost:8000](http://localhost:8000):

```sh
python3 -m http.server 8000
```

The prototype runs as a single HTML file without dependencies or a build step. Use the same browser and URL to keep accessing your local records. Data is stored under the `setline-demo-v1` key. Setline sign-up, cloud sync, and offline page loading are part of the MVP scope.

## Make changes

`index.html` contains the markup, styles, and JavaScript. Change the text or CSS, save the file, and refresh the browser. The built-in workout plans are defined in `legs` and `upper`, and `sample` contains the sample history. You can also create or edit a workout plan directly in **Plans**.

## Publish on GitHub Pages

1. Create a repository and upload the extracted `index.html` and `README.md` to the root of its `main` branch.
2. Open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Open the address shown in **Pages** once the deployment finishes. Changes merged into `main` publish automatically.

[GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
