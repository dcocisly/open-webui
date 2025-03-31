FROM mcr.microsoft.com/devcontainers/python:3.12

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
# fix [Installing gmpy2](https://github.com/langgenius/dify/issues/9355) macos 出现该错误，winodws 暂未出现该错误
RUN apt-get update \
    && apt-get install -y --no-install-recommends gcc g++ libc-dev libffi-dev libgmp-dev libmpfr-dev libmpc-dev
