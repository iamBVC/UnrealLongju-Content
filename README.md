# UnrealLongju Content

Unreal Engine 5 content for the [UnrealLongju project](https://github.com/iamBVC/UnrealLongju). This repository is checked out as the parent project's `Content` submodule.

## Third-party assets and rights

Some files intended for this repository are conversions or technical adaptations of original Metin2 assets into Unreal Engine 5-compatible formats. Those original assets are copyrighted material associated with Gameforge, Ymir, and/or their respective rights holders. All rights in the original assets, including their underlying artwork, models, textures, animations, audio, and other protected material, remain with their respective owners.

This project does not claim ownership of, authorship of, or copyright in those original assets. Its stated purpose is a noncommercial technical reworking of existing material for Unreal Engine 5, not to misrepresent the original creators or appropriate their intellectual property. File-format conversion and technical modification do not transfer ownership or remove existing intellectual-property rights.

UnrealLongju is an independent project. It is not affiliated with, endorsed by, sponsored by, or an official product of Gameforge or Ymir. Metin2 and any third-party names, logos, and trademarks remain the property of their respective owners.

## Permissions and redistribution

This notice is an attribution and statement of project intent, not a license from the original rights holders, proof of authorization, or a claim that the use is legally permitted. Public availability, attribution, and noncommercial intent do not by themselves establish permission to convert, copy, publish, or redistribute protected assets.

The parent project's software license does not grant rights to third-party assets in this repository. Unless an asset-specific license or written authorization explicitly provides otherwise, no permission to use or redistribute third-party material is granted by the project maintainers. Any rights in original project contributions are separate from rights in pre-existing material; no repository-wide asset license is granted by this notice.

Before adding, publishing, or distributing assets, contributors must establish the applicable permissions and document the source, rights holder, license or authorization, and any redistribution restrictions. Do not upload material for which the necessary rights have not been established. Preserve applicable notices and keep documented permissions available for review.

Rights holders with concerns may contact the repository maintainer through their [GitHub profile](https://github.com/iamBVC) to identify the material and request review, correction, or removal. Such a contact process does not replace the need for appropriate authorization before publication.

## Working with the submodule

From the parent repository:

```powershell
git submodule sync --recursive
git submodule update --init --recursive
```

The parent repository records a specific content commit. Commit and push authorized content changes in this repository before updating and committing the parent repository's submodule pointer. Do not commit Unreal-generated caches, intermediate files, or local build output as content.
