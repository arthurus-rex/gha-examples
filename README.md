# gha-examples

This repo includes examples of how to use GitHub Actions with Cosign for signing Containerfile images, and is provided as an educational resource.

The `image.yml` workflow signs a single image built from `Dockerfile` using the SHA digest generated by `docker/build-push-action`, and then uploads it to the `quay.io` registry.




