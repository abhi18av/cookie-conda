## ReadMe

Export `conda` environment

```
conda env export -n root > cookie-conda.yml

```




A [cookiecutter](http://cookiecutter.readthedocs.io/en/latest/readme.html) template

```yaml
- clojure_version = "1.9.0-beta1"

```



Creating `conda env` from a `.yml` file
RESOURCE

https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file


## How to use

**NOTE**: For all pre/post hooks to work need to recreate the `conda-env`

1. Install `cookiecutter` 

```sh
cookiecutter https://github.com/abhi18av/cookiecutter-chromatica

```




