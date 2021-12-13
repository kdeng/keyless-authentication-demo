# Keyless Authentication Demo from Github Actions

This is a simple experiment about enabling keyless authentication from github Actions.

The reference is https://cloud.google.com/blog/products/identity-security/enabling-keyless-authentication-from-github-actions.

## Problems

In this experiment, `gsutil list` doesn't work as expected.

```bash

ServiceException: 401 Anonymous caller does not have storage.objects.list access to the Google Cloud Storage bucket.

```