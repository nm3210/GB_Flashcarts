# GB Flashcarts



## MBC5 Short
*Uploaded to OshPark: https://oshpark.com/shared_projects/VMSFCe2c*

<img src="https://user-images.githubusercontent.com/2113065/158044971-642bab8c-a5e2-40cb-a73b-bde5c176bbb7.png" alt="MBC5 Short Front in OshPark purple" width="360"/>&nbsp;<img src="https://user-images.githubusercontent.com/2113065/158044974-2df0d466-08ab-4a5f-8450-73d3070ace09.png" alt="MBC5 Short Back in OshPark purple" width="360"/>
<img src="https://user-images.githubusercontent.com/2113065/158045170-bcb606c9-b4c9-4cf6-bc19-46a3bfe7e261.png" alt="MBC5 Short Front" width="360"/>&nbsp;<img src="https://user-images.githubusercontent.com/2113065/158045176-9c16197f-b99c-41db-aebe-6c0d9a05409c.png" alt="MBC5 Short Back" width="360"/>


This is my first try at routing the short version of an MBC5 flashcart, there certainly wasn't a lot of room!

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
| U1 | TSOP-**40** (not 48) MBM29F033C-90PTN, or similar |
| U2 | MBC5 (from donor cart?) |
| U3 | 28-pin SOIC FM18W08 |
| C# | 100nF Capacitor 0603 |

### Changelog
\- **v1** around 2022-03-12: First release, hoping for the best
