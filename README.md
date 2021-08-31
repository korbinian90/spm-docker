# SPM Containers

## [Dockerfile](https://docs.docker.com/engine/reference/builder/) for [SPM12](https://www.fil.ion.ucl.ac.uk/software/spm12/)

* [Dockerfile](https://github.com/spm/spm-docker/blob/main/matlab/Dockerfile) using [SPM Standalone](https://www.wikibooks.org/wiki/SPM/Standalone) and [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html)
* [Dockerfile](https://github.com/spm/spm-docker/blob/main/octave/Dockerfile) using [GNU Octave](https://www.octave.org/)

## [Singularity Definition File](https://sylabs.io/guides/3.5/user-guide/definition_files.html) for [SPM12](https://www.fil.ion.ucl.ac.uk/software/spm12/)

* [singularity.def](https://github.com/spm/spm-docker/blob/main/matlab/singularity.def) using [SPM Standalone](https://www.wikibooks.org/wiki/SPM/Standalone) and [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html)
* [singularity.def](https://github.com/spm/spm-docker/blob/main/octave/singularity.def) using [GNU Octave](https://www.octave.org/)

## Container Registries

* [GitHub Packages Container registry](https://ghcr.io/)

```
docker pull ghcr.io/spm/spm-docker:docker-matlab
docker pull ghcr.io/spm/spm-docker:docker-octave
```

```
singularity pull oras://ghcr.io/spm/spm-docker:matlab
singularity pull oras://ghcr.io/spm/spm-docker:octave
```

* [Docker Hub](https://hub.docker.com/r/spmcentral/spm/) (deprecated)

```
docker pull spmcentral/spm:latest
docker pull spmcentral/spm:octave
```

## See also

* [Documentation](https://www.wikibooks.org/wiki/SPM/Docker)
