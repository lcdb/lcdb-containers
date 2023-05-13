Bootstrap: library
From: ubuntu:20.04
Stage: build

%post
    apt update && apt install -y wget
    wget https://raw.githubusercontent.com/bioconda/bioconda-common/master/install-and-set-up-conda.sh
    BIOCONDA_DISABLE_BUILD_PREP=1 bash install-and-set-up-conda.sh
