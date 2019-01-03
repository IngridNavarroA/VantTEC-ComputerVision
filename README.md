## Computer Vision and A.I. - VantTEC 

# Detection and Tracking on Aquatic Surfaces

Referencias
```
@article{redmon2016yolo9000,
  title={YOLO9000: Better, Faster, Stronger},
  author={Redmon, Joseph and Farhadi, Ali},
  journal={arXiv preprint arXiv:1612.08242},
  year={2016}
}

@article{yolov3,
  title={YOLOv3: An Incremental Improvement},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2018}
}
```

## Detector + Tracker

NOTA: Por el momento solo se tiene el CentroidTracker. 

Dentro de la carpeta boat-vision, ejecutar: 
```

python3 main.py --config vanttec/config/yolo3-vantec.cfg --weights vanttec/weights/yolo3-vantec.weights --classes vanttec/obj.names --video vanttec/video.mp4

```
Ejemplo de resultado:
<p align="center"><img src="./readme/det-track.png" /> </p>

## TO DO:
- [x] Deteccion de objetos
- [ ] Buscar un metodo mas preciso para realizar rastreo de objetos (Tracking) 
- [ ] Reconocimiento de colores
- [ ] Estimacion de distancias con respecto a las camaras (Stereo)
- [ ] Planeacion de trayectorias
- [ ] Calibracion de camaras
- [ ] Deteccion de numeros
- [ ] Planeacion de retos de RoboBoat


# Retos RoboBoat

## Introductorios 

### 1. Maintain Heading 

<p align="center"><img src="./readme/intro-heading.png" /> </p>

### 2. Slalom Maneuver

<p align="center"><img src="./readme/intro-slalom.png" /> </p>

## Navegacion autonoma

<p align="center"><img src="./readme/autonomous.png" /> </p>

## Misiones

### 1. Speed Challenge

<p align="center"><img src="./readme/mission-speed.png" /> </p>

### 2. Raise the flag

<p align="center"><img src="./readme/mission-flag.png" /> </p>

### 3. Find the path 

<p align="center"><img src="./readme/mission-path.png" /> </p>

### 4. Follow the leader

<p align="center"><img src="./readme/mission-leader.png" /> </p>