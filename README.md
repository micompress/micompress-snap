# MiCompress snap

Snap packaging for the [MiCompress CLI](https://github.com/micompress/micompress-cli) —
compress images, PDFs, video, audio, documents & archives via
[micompress.com](https://micompress.com/?utm_source=snap&utm_medium=cli&utm_campaign=extend).

```bash
sudo snap install micompress
micompress photo.jpg
```

The snap is built from the CLI's tagged release (`snap/snapcraft.yaml`). Every push to `main` builds and
smoke-tests it in GitHub Actions; store releases are built by the Snapcraft build service from this repo.
