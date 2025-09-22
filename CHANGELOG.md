### 2025/09/22
Version "3.0.28" - Added option to use internal "supervisor" API to communicate with Home Assistant. Users should select this option unless they are updating a different HA instance to where this addon is installed. Existing users will not be affected by default, but can change their configuration if they wish.

### 2025/09/21
Version "3.0.27" - Fix hardcoded end-point hostname in gettoken.py

### 2025/09/18
Version "3.0.26" - Fix bad DOCKERFILE in 3.0.25

### 2025/09/17
Version "3.0.25" - Allow sending settings back to inverter in shortened format

### 2025/09/06
Version "3.0.24" - Added more entities, Base Inverter info are now also posted as an entity instead of just dumping the info in the log.

### 2025/09/02
Version "3.0.23" - Added All Inverter settings to be posted to entities.

### 2025/09/02
Version "3.0.22" - Fixed OAuth endpoint and request structure

### 2025/08/24
Version "3.0.21" - Added missing battery current.

### 2025/05/24
Version "3.0.20" - Corrections and added features
Corrected Load entitiy changed factor load_total_power from kWh to W
Corrected UPS Power (Previously named "Battery time") Now named "Load UPS Total Power"
Added functionality to update system mode settings, refer to documentation on how to use it.

### 2025/05/10
Version "3.0.19" - Added option to select pv.inteless.com as an alternative API endpoint for generic E-Linterbased inverters. (Experimental)

### 2025/03/22
Version "3.0.18" - Changed all energy entities to include "last_reset":"None" and "state_class":"total_increasing" attributes.

### 2025/03/24
Version "3.0.17" - Added ability to send battery settings back to inverter. the following settings can be changed.
"absorptionVolt","battMode","batteryCap","batteryEfficiency","batteryEmptyV","batteryImpedance","batteryLowCap","batteryLowVolt","batteryMaxCurrentCharge","batteryMaxCurrentDischarge","batteryOn","batteryRestartCap","batteryRestartVolt","batteryShutdownCap","batteryShutdownVolt","bmsErrStop","disableFloatCharge","equChargeCycle","equChargeTime","equVoltCharge","floatVolt","genChargeOn","genSignal","generatorBatteryCurrent","generatorForcedStart","generatorStartCap","generatorStartVolt","gridSignal","lithiumMode","lowNoiseMode","lowPowerMode","safetyType","sdBatteryCurrent","sdChargeOn","sdStartCap","sdStartVol","sdStartVolt","signalIslandModeEnable","sn","tempco"

### 2025/03/22
Version "3.0.16" - Fixed another typo in t he log.

### 2025/03/22
Version "3.0.15" - Fixed battery capacity typo in entity naming.

### 2025/03/22
Version "3.0.14" - Fixed EToday to entity which was showing the value of e-total.

### 2025/03/20
Version "3.0.2" - Removed ability to post settings back to inverter. Feature will be added later on.

### 2025/03/20
Version "3.0.1" - Major Update
