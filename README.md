# static

Static content storage for Python Discord assets

## Deployment

A GitHub Actions workflow is configured to automatically deploy static assets to production.

**S3 Bucket**: `pydis-static-assets.eu-central-1.linodeobjects.com`

The workflow syncs the contents of the `content/` folder directly to the root of the bucket.
