# Visual Studio IDE Logo in VTuber Logos Style

Everything here shares the same principle as the [main repo](https://github.com/Aikoyori/ProgrammingVTuberLogos) by [Aikoyori](https://github.com/Aikoyori), so don't use anything here comercially.

> [!NOTE]
> I am not the creator of this logo. The designer is [**Manhkbrady**](https://www.behance.net/Manhkbrady). I posted it on his behalf because he is not familiar with GitHub
> ## [Original work](https://www.behance.net/gallery/196715739/Logofolio)

## Visual Studio IDE Logo
Origin: https://visualstudio.microsoft.com/vs/

New Style: 

<img width="400" src="VisualStudio/VisualStudioLogo.png">
<img width="400" src="VisualStudio/VisualStudioLogoShadow.png">

## Replace Guide
Assume that your Visual Studio installation is under `D:\Microsoft Visual Studio\2022\Community`. Paths below are relative to this directory.

1. Navigate to `Common7\IDE\2052`, find `MsEnvMui_Brand_708_0.dll` and back up it (You may need administrator privilege to do this).

2. Use tools like [Resource Hacker](https://www.angusj.com/resourcehacker/) to open `MsEnvMui_Brand_708_0.dll`.

3. Replace the three images under PNG with the ones in this repo, you may need to adjust the resolution (pre-modified images are listed under the [ModifiedForSplash](VisualStudio/ModifiedForSplash/) folder).
    + 101: 680x420px
    + 111: 1360x840px
    + 116: 1020x630px

4. Save the modified file (Again, you may need to use `Save As` function to save it and replace the original file, because of the administrator privilege requirement).

5. Fire up Visual Studio and enjoy :).

## License
Licensed under [CC-BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)

<img src="CC-BY-NC-SA-4.0.jpg" width="200" height="80" alt="CC-BY-NC-SA-4.0">

You may:
- Share, modify, redistribute under the same license
- Credit **Manhkbrady**
- Use the resources noncomercially

You may **NOT**:
- Sell without permission
