# GB Flashcarts



## MBC5 Short
*Uploaded to OshPark: https://oshpark.com/shared_projects/A7b5nxHa*

<img src="https://user-images.githubusercontent.com/2113065/159615189-64461b1b-f70a-46da-9f52-4699a35c1efe.png" alt="MBC5 Short Front in OshPark purple" width="360"/>&nbsp;<img src="https://user-images.githubusercontent.com/2113065/159615222-3ad6ad72-fb26-4137-be25-13f126ffcdeb.png" alt="MBC5 Short Back in OshPark purple" width="360"/>
<img src="https://user-images.githubusercontent.com/2113065/159615274-b4972128-583c-490e-995e-d71893d6eb7a.png" alt="MBC5 Short Front" width="360"/>&nbsp;<img src="https://user-images.githubusercontent.com/2113065/159615323-2b9672dc-95f1-4c90-b3b0-87fdc9c38b1a.png" alt="MBC5 Short Back" width="360"/>


This is my first try (plus updates) at routing the short version of an MBC5 flashcart, there certainly wasn't a lot of room!

Heavily inspired by [**HDR**](https://martinrefseth.com/)'s [updated MBC3](https://oshpark.com/shared_projects/YCtVNv4A) cart with clean borders and neat original/OEM features like the production date squares and (totally unnecessary) fiducial markings, as well as his own older [short MBC5 cart](https://oshpark.com/shared_projects/IOwfD0lC).

### Board features

\- GameBoy_GamePak_AGB-002 template from [github.com/**djedditt**/kicad-gamepaks](https://github.com/djedditt/kicad-gamepaks) (though I had to change all the rear shapes into netted pads)

\- Schematic mostly from [github.com/**HDR**/MBC5-Flashcart](https://github.com/HDR/MBC5-Flashcart)

\- Date markings and fiducials directly from [github.com/**HDR**/MBC3-Flashcart](https://github.com/HDR/MBC3-Flashcart) (though I tweaked the size a bit)

\- Some labels done via [github.com/gregdavill/KiBuzzard](https://github.com/gregdavill/KiBuzzard)

\- No traces connecting to the cart connector pins on the back side of the board, with a ground plane buffer - this seems to be a 'feature' on a lot of the OEM MBC3/MBC5 nintendo gameboy cartidges I've seen, though I don't know why. This restricted the routing on the board quite a bit!

### Bill of Materials
*Note*: need to order at a 0.8mm service (see OshPark's ["**2oz-0.8mm**"](https://docs.oshpark.com/services/two-layer-hhdc/)) for it to actually fit in a cart slot

| Reference | Part |
| :-- | :--: |
| U1 | TSOP-40/TSOP-48 MBM29F033C-90PTN, AM29F016B-90EC, or similar |
| U2 | MBC5 (from donor cart?) |
| U3 | 28-pin SOIC FM18W08 |
| C# | 100nF Capacitor 0603 |

### Changelog
\- **v1** around 2022-03-12

&emsp;First release, hoping for the best

\- **v2** around 2022-03-22

&emsp;Change from TSOP-40 to TSOP-48 to allow for more chip variants (including ones I bought of course)

&emsp;Fixed **wrong corner** marker on U1 (from lower-left to upper-right, specifically: the side with the **W**rite**E**nable pin should be facing south)

&emsp;Minor routing updates/cleanup
