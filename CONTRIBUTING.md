# Contributing

## Adding your app

The easiest way to submit is directly in the GitHub web interface — no git knowledge needed.

### Step by step

**1.** Go to [`urls.json`](./urls.json) in this repo and click the pencil ✏️ edit button in the top right of the file view.

**2.** Add your entry inside the `[` `]` array. Make sure to add a comma after the previous entry:

```json
[
  {
    "url": "https://existing-app.com",
    "tags": []
  },
  {
    "url": "https://your-app.com",
    "tags": []
  }
]
```

**3.** Scroll to the bottom and select **Create a new branch and start a pull request**, then click **Propose changes**.

**4.** You'll land on the pull request page. Check the checklist, then click **Create pull request**.

**5.** A maintainer will review and merge your PR. Your app will appear in the directory shortly after.

---

## Tips

- Check your JSON is valid before submitting — a missing comma will cause the PR to fail. You can paste it into [jsonlint.com](https://jsonlint.com) to check.
- Make sure your site has og tags set so the directory can display your app properly. See the [README](./README.md) for details.
- If you want to update your app's details (name, description, image) just update the og tags on your own site — no PR needed.
