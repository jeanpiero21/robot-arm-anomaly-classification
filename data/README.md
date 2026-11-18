# Data

The raw data is not versioned. Download the dataset from Kaggle <!-- TODO: pegar aquí el link de Kaggle --> and place these 5 files in this folder:

```
data/
├── IMU_earthquake.csv
├── IMU_extra_weigth.csv      # file name as provided by the dataset
├── IMU_hitting_arm.csv
├── IMU_hitting_platform.csv
└── IMU_magnet.csv
```

Each file holds 9-axis IMU readings at 10 Hz: `accX, accY, accZ, gyroX, gyroY, gyroZ, magX, magY, magZ`.
