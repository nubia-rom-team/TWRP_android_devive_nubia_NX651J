# TWRP_android_devive_nubia_NX651J
nubia Play 5G Twrp recovery 设备树

![OFRP](https://image.ibb.co/cTMWux/logo.jpg "OFRP")

OrangeFox Recovery Project (OFRP) R11.1 for nubia Play 5G (NX651J)
======================================

# How to build

```bash
<?xml version="1.0" encoding="UTF-8"?>
<manifest>

<!-- QCOM decryption -->
  <project name="TeamWin/android_device_qcom_twrp-common" path="device/qcom/twrp-common" remote="github" revision="android-11"/>
</manifest>
```

Then go to the source folder and run:

```bash
. build/envsetup.sh && lunch omni_NX651J-eng && mka recoveryimage
```

