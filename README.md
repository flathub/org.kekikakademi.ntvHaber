# org.kekikakademi.ntvHaber

For bug reports and feature requests, see: [ntvHaber](https://github.com/keyiflerolsun/ntvHaber)

```bash
wget https://raw.githubusercontent.com/flatpak/flatpak-builder-tools/master/pip/flatpak-pip-generator && chmod +x flatpak-pip-generator

./flatpak-pip-generator poetry==1.3.2 --output SRC/python3-poetry --checker-data --yaml --runtime=org.freedesktop.Sdk//22.08
./flatpak-pip-generator --checker-data --yaml --requirements-file=SRC/requirements.txt --output SRC/python3-requirements --runtime=org.freedesktop.Sdk//22.08
```
