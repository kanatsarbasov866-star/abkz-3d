# abkz-3d

3D models used by **Assessment Builder KZ** (Сарбасов Нұрхат Қанатұлы) for school lessons:
the «Адам денесі 3D» (human body) tool loads the files in `anatomy/` directly from this repository.

## anatomy/ — human anatomy models

| File | Content |
|---|---|
| `heart.glb` | Heart: wall, coronary arteries and veins, valves, papillary muscles |
| `brain.glb` | Brain grouped by lobes, cerebellum, brainstem, inner structures, ventricles |
| `lungs.glb` | Lung lobes and trachea |
| `digestive.glb` | Esophagus, stomach, liver, gallbladder, pancreas, small and large intestine |
| `urinary.glb` | Kidneys and urinary bladder |
| `skeleton.glb` | Skeleton grouped into bones / bone groups |

**Source and license.** These models are adapted from **BodyParts3D**,
© The Database Center for Life Science (DBCLS), licensed under
[Creative Commons Attribution-Share Alike 2.1 Japan](https://creativecommons.org/licenses/by-sa/2.1/jp/deed.en).
Original data: http://lifesciencedb.jp/bp3d/ (version 3.0, via the STL conversion at
https://github.com/Kevin-Mattheus-Moerman/BodyParts3D).

**Changes made:** meshes were simplified (polygon reduction), parts were merged into named groups
with Kazakh labels and colours, and exported to glTF binary (`.glb`).
In accordance with the Share-Alike term, the files in `anatomy/` are distributed under the same
license (CC BY-SA 2.1 JP).

Citation: Mitsuhashi N, Fujieda K, Tamura T, Kawamoto S, Takagi T, Okubo K.
BodyParts3D: 3D structure database for anatomical concepts. Nucleic Acids Res. 2009;37(Database issue):D782-5.
https://doi.org/10.1093/nar/gkn613

## Space models

The «Ғарыш 3D» tool loads NASA models directly from https://github.com/nasa/NASA-3D-Resources (not copied here).
