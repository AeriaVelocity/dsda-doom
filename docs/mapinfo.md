## MAPINFO

This page tracks support for the MAPINFO lump, as seen in ZDoom. This is all a work in progress - the status of any feature (including whether or not it is planned) is subject to change.

### Current Status

You can enable MAPINFO parsing via the `-debug_mapinfo` command line option. Support is currently experimental and various errors are present.

### Legend

| Symbol             | Meaning                        |
| ------------------ | ------------------------------ |
| :heavy_check_mark: | Feature is supported           |
| :telescope:        | Feature is planned             |

### Top Level Keys

| Key           | Status             |
| ------------- | ------------------ |
| cluster       | :telescope:        |
| clearepisodes | :telescope:        |
| episode       | :telescope:        |
| map           | :heavy_check_mark: |
| defaultmap    | :heavy_check_mark: |
| adddefaultmap | :heavy_check_mark: |
| clearskills   | :telescope:        |
| skill         | :telescope:        |

### Map Properties

| Key                                | Status             |
| ---------------------------------- | ------------------ |
| LevelNum                           | :heavy_check_mark: |
| Next                               | :heavy_check_mark: |
| SecretNext                         | :heavy_check_mark: |
| Cluster                            | :heavy_check_mark: |
| Sky1                               | :heavy_check_mark: |
| TitlePatch                         | :heavy_check_mark: |
| Par                                | :heavy_check_mark: |
| Music                              | :heavy_check_mark: |
| ExitPic                            | :heavy_check_mark: |
| EnterPic                           | :heavy_check_mark: |
| InterMusic                         | :heavy_check_mark: |
| BorderTexture                      | :heavy_check_mark: |
| Gravity                            | :heavy_check_mark: |
| AirControl                         | :heavy_check_mark: |
| Author                             | :heavy_check_mark: |
| SpecialAction                      | :heavy_check_mark: |
| Intermission                       | :heavy_check_mark: |
| NoIntermission                     | :heavy_check_mark: |
| EvenLighting                       | :heavy_check_mark: |
| SmoothLighting                     | :heavy_check_mark: |
| AllowMonsterTelefrags              | :heavy_check_mark: |
| ActivateOwnDeathSpecials           | :heavy_check_mark: |
| KillerActivatesDeathSpecials       | :heavy_check_mark: |
| StrictMonsterActivation            | :heavy_check_mark: |
| LaxMonsterActivation               | :heavy_check_mark: |
| MissileShootersActivateImpactLines | :heavy_check_mark: |
| MissilesActivateImpactLines        | :heavy_check_mark: |
| FilterStarts                       | :heavy_check_mark: |
| AllowRespawn                       | :heavy_check_mark: |
| NoJump                             | :heavy_check_mark: |
| AllowJump                          | :heavy_check_mark: |
| CheckSwitchRange                   | :heavy_check_mark: |
| NoCheckSwitchRange                 | :heavy_check_mark: |
| ResetHealth                        | :heavy_check_mark: |
| ResetInventory                     | :heavy_check_mark: |
| UsePlayerStartZ                    | :heavy_check_mark: |
| NoPassover                         | :heavy_check_mark: |
| Passover                           | :heavy_check_mark: |
