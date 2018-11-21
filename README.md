# SealOS Secure IoT Releases Feed

SealOS Releases have different channels the most useful ones are:
Beta -> Stable.

If you are deploying to production it is recommended to use the Stable
Channel. For further support please email: support@opendevices.io

SealOS is Releases and Maintained by [Open
Devices](https://opendevices.io/) and integrates well with Modern IoT
Infrastructure [Ionoid IoT](https://ionoid.io/)


## Releases Notes

SealOS version numbers are set according to [Semantic
Versioning](https://semver.org/) standards.

Each Channel has its corresponding release file, example `Stable`
Releases are all included in `stable.json` feed.

Each Release entry contains the following:
```
{
        "version": {
                "release_date": "2018-11-21 09:21:17+00:00",
                "major_software": {
                        "majorsoftware1": "version",
                        "majorsoftware2": "version"
                },
                "release_notes": "New SealOS Release Notes\n",
                "url":"https://releases.seal-os.org/arch/currnet/sealos-version.img.zip"
        }
}
```

For an example You take a look at the `stable.json` file.
