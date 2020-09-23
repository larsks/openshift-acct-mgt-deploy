To deploy using the `latest` tag:

- Run `oc apply -k base`

To deploy using a specific commit:

- Edit `prod/use_tagged_image.yml`

- Run `oc apply -k prod`
