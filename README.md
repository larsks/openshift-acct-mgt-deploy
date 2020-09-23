To change the image name:

- Edit `base/deployment.yml`

- Change the value of `image` in the container template

To deploy using the `latest` tag:

- Run `oc apply -k base`

To deploy using a specific commit:

- Edit `prod/use_tagged_image.yml`

- Run `oc apply -k prod`
