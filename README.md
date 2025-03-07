<div align=center style="text-align: center;">
<h1> Stay in Tarkov </h1>
A SPT-Aki mod to be used with SPT-Aki Server to allow the Coop Module to communicate with the SPT-Aki Server.
</div>

---

## Summary

This is the SERVER modification of [SPT-Aki](https://www.sp-tarkov.com/) to allow the [Coop Module](https://github.com/paulov-t/SIT.Core) to communicate with the SPT-Aki Server.

## How to use this Repo?

* Install SIT via the Launcher (or manually)
* Download and Install the latest SPT-Aki Server
* Download this repo (see the Code button above)
* Install this repo into the server /user/mods/ folder

## How do I set up this mod?

### Coop Config JSON
* You must configure the file called coopConfig.json in your SITCoop/config folder. This file is auto generated on first run of the mod.

#### IF you are using PORT FORWARDING
* In the file you must use the following config, replacing `{enter your external IP here}` with your own IPv4 from https://www.whatismyip.com and set useExternalIPFinder to false 
* OR set useExternalIPFinder to true

#### IF you are using HAMACHI
* set useExternalIPFinder to false
* set externalIP to your desired IP

### Http.json

* Open Aki_Data\Server\configs\http.json with your favourite text editor
* Change the `ip` setting to your internal network IP of your Computer Primary Network (Ethernet or Wi-Fi)
* Change the `logRequests` setting to `false` to prevent log spam


## Installing SPT-Aki to Azure Web Services
https://learn.microsoft.com/en-us/azure/app-service/configure-language-nodejs
