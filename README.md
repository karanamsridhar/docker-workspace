## Setup

```
set WORKING_DIR = PATH_TO_WORKING_DIR_WTHOUT_QUOTES
docker run -it --rm -v %WORKING_DIR%:/terraform-eks -w /terraform-eks --entrypoint /bin/sh amazon/aws-cli:2.0.43
yum install -y jq gzip nano tar git unzip wget

```

