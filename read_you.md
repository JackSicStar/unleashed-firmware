git clone --recursive -b unl_dev_all_apps https://github.com/JackSicStar/unleashed-firmware.git


cd unleashed-firmware


git submodule update --init --recursive


.\fbt.cmd -j1 COMPACT=1 DEBUG=0 fap_dist updater_package copro_dist
