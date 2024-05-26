# Scope

This repository contains the design files for a custom extension board **ESP32S3-DevKit-Lipo** from Olimex, created using KiCad.

## Version

KiCAD v8.0

## Project Structure

The repository is organized as follows:

```
├── .gitignore
├── LICENSE
├── README.md
├── ver/
│   ├── esp32s3_ext_v0.1.0      # zip file
```

### Contents

1. Schematic file (`esp32s3_ext.sch`).
2. PCB layout file (`esp32s3_ext.kicad_pcb`).

### Generating Gerber Files

1. Go to `File > Plot` in the PCB editor.
2. Select the layers you need and specify the output directory as `gerbers/`.
3. Click `Plot` to generate the Gerber files.
4. Click `Generate Drill Files` to create the drill files.

## Preview

Front view:
![esp32s3_ext](https://github.com/hemanre/esp32s3_ext/assets/108745217/c62e974e-12b6-47d1-bba2-663c2bd6d33a)

Back view: 
![esp32s3_ext_bk](https://github.com/hemanre/esp32s3_ext/assets/108745217/522abcc6-7b89-4092-8bd1-5377042e9969)

## Future goals

1. Add a main power supply on board 9V.
2. Add sensors to schematic.
3. Add motor driver hardware MX1919 to schemtatic.
