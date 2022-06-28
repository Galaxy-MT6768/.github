# Galaxy A31 & A41 MT6768
Only SM-A315G is actively mantained.
### Getting the right roomservice.xml
> Create an ``.xml`` file inside ``.repo/local_manifests/`` called ``roomservice`` & add this inside it:
> ```xml
> <manifest>
>   <project path="device/samsung/a31" name="Galaxy-MT6768/android_device_samsung_a31x" remote="github" revision="android-12"/>
>   <project path="device/samsung/a41" name="Galaxy-MT6768/android_device_samsung_a41nsxx" remote="github" revision="android-11"/>
> </manifest>
> ```
> And then sync the repos by
>```console
> repo sync --force-sync device/samsung/a31
> repo sync --force-sync device/samsung/a41
>```
