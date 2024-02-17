# LightSwitch3.5
This is a ESP32 Smart Light Switch with 3.5 Inch TFT Display, compatible with OpenHASP https://www.openhasp.com

The light switch is available in 2 configurations and  replaces standard mechanical switches for single / double gang.

## Vertical single-gang 
  
<img width="558" alt="image" src="https://github.com/lbarrosoneto/LightSwitch3.5/assets/7077968/dfb1297a-01ec-48b7-98d0-3833161f6b73">

## Horizontal Double Gang
  
<img width="830" alt="image" src="https://github.com/lbarrosoneto/LightSwitch3.5/assets/7077968/cd505e50-5239-46ae-b379-188f47ed30aa">



# Disclaimer
==========================================WARNING==================================================

THIS PROJECT INVOLVES MONKEYING WITH HIGH VOLTAGE AND YOU COULD KILL YOURSELF 
AND/OR SET YOUR HOUSE ON FIRE

The end result is a thing that connects to live voltage and will be placed into 
your wall for years to come. It will not carry any sort of UL/CE/etc certification. 
Proceed with extreme caution.

EXCLUSION AND LIMITATION OF LIABILITY 
The developer shall, to
the maximum extent permitted by law, have no liability for
direct, indirect, special, incidental, consequential, exemplary,
punitive or other damages of any character including, without
limitation, procurement of substitute goods or services, loss of
use, data or profits, or business interruption, however caused
and on any theory of contract, warranty, tort (including
negligence), product liability or otherwise, arising in any way
in relation to the Covered Source, modified Covered Source
and/or the Making or Conveyance of a Product, even if advised of
the possibility of such damages, and You shall hold the
Licensor(s) free and harmless from any liability, costs,
damages, fees and expenses, including claims by third parties,
in relation to such use.
      
=========================================WARNING==================================================


# Hardware Design

2 PCBs compose the hardware design, that is available from https://github.com/lbarrosoneto/LightSwitch3.5/tree/main/HWDesign

## ESP32 Display Controller

  <img width="713" alt="image" src="https://github.com/lbarrosoneto/LightSwitch3.5/assets/7077968/f726bf63-5662-4d50-8caa-3ec88a5a434e">


## Relay and Power Board
  
  <img width="661" alt="image" src="https://github.com/lbarrosoneto/LightSwitch3.5/assets/7077968/96738b18-1a9f-42d8-813d-ace2a7ad3329">

# 3D Print Files
3D print design files for single and double gang versions is available from https://github.com/lbarrosoneto/LightSwitch3.5/tree/main/3DPrintCase


# Programming the LightSwitch3.5
Follow the instructions from https://www.openhasp.com/0.7.0/firmware/compiling/local/#native-windows-build

Lightswitch3.5 is compatible with the esp32-touchdown https://github.com/DustinWatts/esp32-touchdown

<img width="901" alt="image" src="https://github.com/lbarrosoneto/LightSwitch3.5/assets/7077968/35ab6684-7bf6-4d6a-b014-b31c441da480">


The Relays are connected to IO12 and IO13, so, those ports need to be configured "Pin Output" in the Light Switch Web Interface (Under Configuration->GPIO Settings): 

<img width="630" alt="image" src="https://github.com/lbarrosoneto/LightSwitch3.5/assets/7077968/8c0028f4-35ad-4061-b45e-96fbb7411561">




This work is copyright (c) Luiz Oliveira Neto <lboneto@gmail.com> and licensed under [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](https://github.com/lbarrosoneto/LightSwitch3.5)
