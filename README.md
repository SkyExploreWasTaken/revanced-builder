# ReVanced Builder

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/j-hc/revanced-magisk-module/releases) or the [Obtainium configuration file](https://github.com/SkyExploreWasTaken/revanced-builder/blob/main/obtainium-config.json).

You want to use Obtainium? 
You can install it on [F-Droid](https://f-droid.org/fr/packages/dev.imranr.obtainium.fdroid/) or directly from [Obtainium website](https://obtainium.imranr.dev/).
You can then go in the import section and click "Obtainium import". Finally, select the Obtainium configuration file above. You are now ready to go!

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced and <a href="https://github.com/inotia00/revanced-patches">ReVanced Extended</a> apps</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
</details>

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./bui``
