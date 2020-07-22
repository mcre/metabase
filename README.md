# Metabase with AWS Athena support

Thanks to [metabase/metabase](https://github.com/metabase/metabase), [dacort/metabase-athena-driver](https://github.com/dacort/metabase-athena-driver) and [quintoandar/metabase](https://github.com/quintoandar/metabase)!

This repository was created with reference to [quintoandar/metabase](https://github.com/quintoandar/metabase).

## Local Check

```
docker build -t metabase-test .
docker run -d -p 3000:3000 --name metabase metabase-test
```