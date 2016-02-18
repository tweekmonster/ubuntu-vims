# Ubuntu Vims

Builds of Vim from different versions of Ubuntu.
See: [vim-testbed](https://github.com/tweekmonster/vim-testbed)

## Usage

```shell
docker pull tweekmonster/ubuntu-vims
docker run -it --rm tweekmonster/ubuntu-vims vim-precise --version
docker run -it --rm tweekmonster/ubuntu-vims vim-trusty --version
docker run -it --rm tweekmonster/ubuntu-vims vim-vivid --version
docker run -it --rm tweekmonster/ubuntu-vims vim-wily --version
docker run -it --rm tweekmonster/ubuntu-vims vim-xenial --version
```
