# Venom-Tweaks
## Description
This module is a bunch of my favorite build.prop "Tweaks" that can now be installed seamlessly and systemlessly via Magisk.

## What it does
This module uses the tool "resetprop" to modify the default values found in build.prop to:

ro.secure=0
dalvik.vm.execution-mode=int:jit
dalvik.vm.dexopt-flags=m=y
ro.vold.umsdirtyratio=20
ro.home_app_adj=1
debug.kill_allocating_task=0
debug.enabletr=true
debug.overlayui.enable=1
debug.qctwa.preservebuf=1
debug.qc.hardware=true
debug.egl.hw=1
debug.qctwa.statusbar=1
debug.performance.tuning=1
ro.kernel.checkjni=0
ro.kernel.android.checkjni=0
ro.lge.proximity.delay=25
mot.proximity.delay=25
ro.tether.denied=false
pm.sleep_mode=1
ro.ril.disable.power.collapse=0
ro.config.hw_menu_unlockscreen=false
ro.mot.buttonlight.timeout=0
ro.config.disable_hw_accel=false 
ro.config.hw_quickpoweron=true
ro.configure.nocheckin=1
dev.bootcomplete=0
hwui.render_dirty_regions=false
hwui.disable_vsync=true
ro.wmt.blcr.enable=0
ro.ril.fast.dormancy.rule=2
profiler.force_disable_err_rpt=1
profiler.force_disable_ulog=1
ro.telephony.call_ring.delay=0
ro.mot.eri.losalert.delay=1000
ro.telephony.sms_segment_size=160
dev.pm.dyn_samplingrate=1
debug.kill_allocating_task=0
ro.config.disable.hw_accel=false
ro.fb.mode=1
ro.sf.compbypass.enable=0
boot.fps=20
ring.delay=0
ro.config.dha_tunnable=1
ro.config.hw_power_saving=1 
debugtool.anrhistory=0
profiler.debugmonitor=false
profiler.launch=false
profiler.hung.dumpdobugreport=false
debug.gr.swapinterval=59
debug.egl.profiler=1
debug.composition.type=gpu
debug.composition.type=c2d
ro.min_pointer_dur=1
video.accelerate.hw=1 
touch.presure.scale=0.001
ro.max.fling_velocity=12000
ro.min.fling_velocity=8000
ro.product.gpu.driver=1
hw3d.force=1
hw2d.force=1
wifi.supplicant_scan_interval=220
persist.sys.ui.hw=1
persist.sampling_profiler=0
persist.radio.lteon=false
persist.sys.NV_PROFVER=15
persist.sys.NV_STEREOCTRL=0
persist.sys.NV_STEREOSEPCHG=0
persist.sys.NV_STEREOSEP=20
persist.sys.NV_FPSLIMIT=60
persist.sys.NV_POWERMODE=1
persist.sys.use_dithering=1
persist.android.strictmode=0
persist.service.adb.enable=1
persist.sys.use_16bpp_alpha=1
persist.wifi_scan_interval=220
persist.sys.purgeable_assets=1
persist.service.pcsync.enable=0 
persist.service.lgospd.enable=0
persist.telephony.support.ipv6=1
persist.telephony.support.ipv4=1
persist.sys.composition.type=gpu
persist.sys.composition.type=c2d
persist.sys.shutdown.mode=hibernate
persist.splitwindow.support_all=true
net.dns1=8.8.8.8
net.dns2=8.8.4.4
net.rmnet0.dns1=8.8.8.8
net.rmnet0.dns2=8.8.4.4
net.ppp0.dns1=8.8.8.8
net.ppp0.dns2=8.8.4.4
net.wlan0.dns1=8.8.8.8
net.wlan0.dns2=8.8.4.4
net.eth0.dns1=8.8.8.8
net.eth0.dns2=8.8.4.4
net.gprs.dns1=8.8.8.8
net.gprs.dns2=8.8.4.4
net.ipv4.ip_no_pmtu_disc=0
net.ipv4.route.flush=1
net.ipv4.tcp_ecn=0
net.ipv4.tcp_fack=1
net.ipv4.tcp_mem=187000 187000 187000
net.ipv4.tcp_moderate_rcvbuf=1
net.ipv4.tcp_no_metrics_save=1
net.ipv4.tcp_rfc1337=1
net.ipv4.tcp_rmem=4096 39000 187000
net.ipv4.tcp_sack=1
net.ipv4.tcp_timestamps=1
net.ipv4.tcp_window_scaling=1
net.ipv4.tcp_wmem=4096 39000 18700
net.ipv6.ip_no_pmtu_disc=0
net.ipv6.route.flush=1
net.ipv6.tcp_ecn=0
net.ipv6.tcp_fack=1
net.ipv6.tcp_mem=187000 187000 187000
net.ipv6.tcp_moderate_rcvbuf=1
net.ipv6.tcp_no_metrics_save=1
net.ipv6.tcp_rfc1337=1
net.ipv6.tcp_rmem=4096 39000 187000
net.ipv6.tcp_sack=1
net.ipv6.tcp_timestamps=1
net.ipv6.tcp_window_scaling=1
net.ipv6.tcp_wmem=4096 39000 18700
persist.radio.ap.phonetype=1
ro.telephony.gsm-routes-us-smsc=0
ro.config.combined_signal=false
persist.cust.tel.eons=1
ro.config.hw_fast_dormancy=1
ro.ril.gprsclass=32
ro.ril.hep=1
ro.ril.hsxpa=2
ro.ril.enable.dtm=1
ro.ril.hsdpa.category=28
ro.ril.enable.a52=1
ro.ril.enable.a53=1
ro.ril.enable.3g.prefix=1
ro.ril.htcmaskw1.bitmask=4294967295
ro.ril.htcmaskw1=268449905
ro.ril.hsupa.category=9
ro.ril.def.agps.mode=2
ro.ril.def.agps.feature=1
ro.ril.enable.sdr=1
ro.ril.enable.gea3=1
ro.ril.enable.fd.plmn.prefix=23402,23410,23411 
ro.ril.enable.amr.wideband=1 
persist.ril.uart.flowctrl=10
persist.ril.mux.noofchannels=10 
net.tcp.buffersize.default=6144,87380,1048576,6144,87380,524288
net.tcp.buffersize.wifi=524288,1048576,2097152,524288,1048576,2097152
net.tcp.buffersize.umts=6144,87380,1048576,6144,87380,524288
net.tcp.buffersize.gprs=6144,87380,1048576,6144,87380,524288
net.tcp.buffersize.edge=6144,87380,524288,6144,16384,262144
net.tcp.buffersize.hspa=6144,87380,524288,6144,16384,262144
net.tcp.buffersize.lte=524288,1048576,2097152,524288,1048576,2097152
net.tcp.buffersize.hsdpa=6144,87380,1048576,6144,87380,1048576
net.tcp.buffersize.evdo_b=6144,87380,1048576,6144,87380,1048576  
media.stagefright.enable-player=true
media.stagefright.enable-record=true
media.stagefright.enable-meta=true
media.stagefright.enable-scan=true
media.stagefright.enable-http=true
media.stagefright.enable-rtsp=true


## Requirements
* Magisk v15.0 or higher

## Changelog 
* Initial Release v1.0


