## Recovery Device Tree for the Samsung Galaxy S20 Ultra 5G (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_z3s-eng
make recoveryimage
```

Kernel source:
https://github.com/Nico170420/android_kernel_samsung_universal9830-990
