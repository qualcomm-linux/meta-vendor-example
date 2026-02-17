# meta-vendor-example

Template meta-layer for building on top of meta-qcom with KAS.

## Quick build

Please refer to the [Yocto Project Reference Manual](https://docs.yoctoproject.org/ref-manual/system-requirements.html)
to set up your Yocto Project build environment.

Please follow the instructions below for a KAS-based build. The KAS tool offers
an easy way to setup bitbake based projects. For more details, visit the
[KAS documentation](https://kas.readthedocs.io/en/latest/index.html).

1. Install kas tool

    ```
    sudo pip3 install kas
    ```

2. Clone meta-vendor layer

    ```
    git clone https://github.com/qualcomm-linux/meta-vendor-example.git
    ```

3. Build using the KAS configuration for one of the supported boards

    ```
    kas build meta-vendor-example/ci/qcs9100-ride-sx.yml:meta-vendor-example/ci/qcom-distro.yml
    ```
