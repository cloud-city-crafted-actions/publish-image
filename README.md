# Cloud City Crafted GitHub Action: Publish Image

A GitHub composite action to publish @cloud-city-crafted-images to the GitHub Container Registry.

## ⌨️ Usage

```yaml
permissions:
  contents: read
  packages: write

steps:
  - name: Build and Publish Cloud City Crafted Image
    uses: cloud-city-crafted-actions/publish-image@v1
    with:
      github-token: ${{ secrets.GITHUB_TOKEN }}
      image-version: 1.0.0
```

## 🪪 License

This repository is [MIT licensed](./LICENSE).
