<div align="center">

# 🦖 DINO-BUZZ

### Dinonaut Starter Bot · FTC Team 27572

**An open-source FIRST Tech Challenge robot. Full CAD, free for every team.**

![FTC Team](https://img.shields.io/badge/FTC-27572-ECB852?style=for-the-badge)
![Open Source](https://img.shields.io/badge/open--source-free%20CAD-111111?style=for-the-badge)
![CAD](https://img.shields.io/badge/CAD-STEP%20AP214-white?style=for-the-badge)
![Status](https://img.shields.io/badge/status-concept-ECB852?style=for-the-badge)

<img src="media/dino-buzz-hero.jpg" alt="DINO-BUZZ starter bot render" width="100%">

▶️ **[Watch the reveal video](media/DINO-BUZZ_Reveal.mp4)**

<!-- Tip: to get an inline player on GitHub, edit this README in the browser and drag the .mp4 into the editor,
     or upload the video to YouTube and replace the link above. -->

</div>

---

## About

**DINO-BUZZ** is a starter robot designed by **Team Dinonaut (FTC #27572)** and shared with the FTC community for free.
It's meant to be a solid starting point: download it, learn from it, change it, and build your own robot from it.

It drives on mecanum wheels, picks game pieces up with a full-width roller intake, passes them through a center transfer,
and launches them with a flywheel shooter.

## Features

| Subsystem | What's in the CAD |
|---|---|
| **Drivetrain** | 4 × Swyft Drive V2 modules (`SR-DRIVE-02`): mecanum, one module per wheel |
| **Intake** | Roller intake with 11 × Swyft 2.5" compliant intake wheels on 7 mm hex, plus a 3D-printed front ramp |
| **Transfer** | Center transfer that feeds game pieces from the intake up to the shooter |
| **Shooter** | 72 mm flywheel on a REX shaft, powered by a goBILDA 5000-series motor (belt drive below) |
| **Electronics** | REV Control Hub + REV Expansion Hub, mounted on the side plates |
| **Size** | 391 × 428 × 295 mm (15.4 × 16.8 × 11.6 in), so it fits the 18 in sizing cube |

<table>
  <tr>
    <td><img src="media/drivetrain.jpg" alt="Swyft Drive V2 mecanum drivetrain"></td>
    <td><img src="media/intake.jpg" alt="Roller intake with compliant wheels"></td>
  </tr>
  <tr>
    <td align="center"><b>Swyft Drive V2 mecanum drivetrain</b></td>
    <td align="center"><b>Roller intake</b></td>
  </tr>
  <tr>
    <td><img src="media/shooter-belt-drive.jpg" alt="Flywheel shooter with belt drive"></td>
    <td><img src="media/electronics.jpg" alt="REV Control Hub"></td>
  </tr>
  <tr>
    <td align="center"><b>Flywheel shooter + belt drive</b></td>
    <td align="center"><b>REV Control Hub + Expansion Hub</b></td>
  </tr>
</table>

<p align="center"><img src="media/exploded-view.jpg" alt="Exploded view of DINO-BUZZ" width="85%"></p>

## Shooter belt drive (planned)

The CAD currently has the shooter motor and flywheel but **no belt yet**. This is the drive shown in the renders and video,
sized to the shaft spacing that's already in the CAD:

| Part | Spec |
|---|---|
| Pulleys | 2 × HTD 5M, 24 teeth, for 9 mm belt (one on the motor shaft, one on the flywheel REX shaft) |
| Belt | HTD **415-5M**, 9 mm wide (83 teeth) |
| Ratio | 1 : 1 |
| Center distance | 147.6 mm (measured from the CAD) |

At the current spacing the belt path is 415.1 mm long, so a standard 415 mm belt fits with light pre-tension.
If you want adjustable tension, add an idler or slot the motor mount.

## Download the CAD

The full robot is one STEP file (about 180 MB, exported from Autodesk Fusion):

- **Units:** millimeters
- **Orientation:** Z-up, front of the robot (intake) facing −Y
- **Opens in:** Fusion, Onshape, SolidWorks, Inventor, FreeCAD, or any CAD that imports STEP AP214

> **Get it from the [Releases](../../releases) page.** GitHub doesn't allow single files over 100 MB in a repository,
> so the STEP file is attached to the release instead of living in the repo.

## Repository layout

```
dino-buzz/
├── README.md
├── media/
│   ├── dino-buzz-hero.jpg
│   ├── drivetrain.jpg
│   ├── intake.jpg
│   ├── shooter-belt-drive.jpg
│   ├── electronics.jpg
│   ├── exploded-view.jpg
│   └── DINO-BUZZ_Reveal.mp4
└── (CAD) → see Releases
```

## Status & roadmap

DINO-BUZZ is a **concept design**: it hasn't been built and tested yet.

- [x] Full robot CAD (drivetrain, intake, transfer, shooter, electronics)
- [x] Reveal video and renders
- [ ] Add the shooter belt drive to the CAD
- [ ] Bill of materials (BOM) with vendor links
- [ ] Build and test the prototype
- [ ] Publish robot code

## Use it, remix it, share it

Every team is welcome to use this design, whether you copy it outright or take one mechanism for your own robot.
If DINO-BUZZ helps you, we'd love to hear about it: open an [issue](../../issues), or tag **FTC 27572 Dinonaut**
when you share your robot.

Found a problem in the CAD or have an improvement? Issues and pull requests are welcome.

## License

Shared under [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/):
you're free to use, modify and share it, including on competition robots, as long as you credit **Team Dinonaut (FTC 27572)**.

## Credits

Designed by **Team Dinonaut, FTC #27572**.

Built around off-the-shelf parts from **Swyft Robotics**, **goBILDA** and **REV Robotics**.
Third-party part models belong to their respective manufacturers.

<div align="center">

**🦖 Dinonaut · FTC 27572**

</div>
