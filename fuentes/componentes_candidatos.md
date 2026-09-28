# Componentes candidatos y fuentes tecnicas

Esta lista no fija una seleccion definitiva de componentes. Sirve como soporte preliminar para que las tablas de interfaces, potencia, datos y arquitectura no queden basadas en valores sueltos.

## Candidato base recomendado

Usar como arquitectura preliminar:

`STM32H7 + memoria SPI/microSD + CC1120 con etapa RF externa + modulo multiespectral compacto + ADCS con magnetorquers tipo iMTQ + EPS 2S Li-Ion con BQ25713 + INA219/TMP117`

## Descargas sugeridas

| Subsistema | Candidato | Documento a descargar | Carpeta |
|---|---|---|---|
| PCB principal / OBC | STM32H743 o familia STM32H7 | Datasheet del STM32H743/753 | `datasheets/obc/` |
| Memoria no volatil | Winbond W25Q128JV | Datasheet W25Q128JV | `datasheets/memoria/` |
| Almacenamiento de imagenes | microSD, SD NAND o eMMC TBD | Datasheet del dispositivo elegido | `datasheets/memoria/` |
| Comunicaciones UHF | TI CC1120 | Datasheet CC1120 | `datasheets/comunicaciones/` |
| Etapa RF | TI CC1190 o PA equivalente | Datasheet CC1190 o PA seleccionado | `datasheets/comunicaciones/` |
| EPS / bateria | BQ25713 + bateria 2S Li-Ion | Datasheet BQ25713 y hoja de datos del pack/celda | `datasheets/eps_bateria/` |
| Medicion electrica | INA219 | Datasheet INA219 | `datasheets/sensores/` |
| Sensor termico | TMP117 | Datasheet TMP117 | `datasheets/sensores/` |
| Sensor de actitud | LIS3MDL | Datasheet LIS3MDL | `datasheets/sensores/` |
| IMU / giroscopio-acelerometro | BMI088 | Datasheet BMI088 | `datasheets/sensores/` |
| Actitud / actuadores | ISISPACE iMTQ Magnetorquer Board | Brochure/datasheet iMTQ | `datasheets/adcs/` |
| Carga util multiespectral | AS7341 o modulo OEM multiespectral TBD | Datasheet AS7341 o documento del modulo elegido | `datasheets/carga_util/` |

## Enlaces oficiales o de fabricante

- STM32H743/753: https://www.st.com/en/microcontrollers-microprocessors/stm32h743-753/documentation.html
- TI CC1120: https://www.ti.com/product/CC1120
- TI CC1190: https://www.ti.com/product/CC1190
- TI BQ25713: https://www.ti.com/product/BQ25713
- TI INA219: https://www.ti.com/product/INA219
- TI TMP117: https://www.ti.com/product/TMP117
- Winbond W25Q128JV: https://www.winbond.com/hq/support/documentation/
- ST LIS3MDL: https://www.st.com/en/mems-and-sensors/lis3mdl.html
- Bosch BMI088: https://www.bosch-sensortec.com/en/products/motion-sensors/imus/bmi088
- ISISPACE iMTQ: https://www.isispace.nl/wp-content/uploads/2019/08/ISIS-IMTQ-Magnetorquer-Board-Brochure-V2R-web.pdf
- ams OSRAM AS7341: https://ams-osram.com/products/sensor-solutions/ambient-light-color-spectral-proximity-sensors/ams-as7341-11-channel-spectral-color-sensor

## Nota sobre la camara

La carga util es el punto que mas puede cambiar el presupuesto. Si se usa AS7341, queda mas como sensor espectral compacto de laboratorio, no como camara multiespectral orbital completa. Si se usa una camara CubeSat real, probablemente cambian masa, volumen, potencia y tasa de datos. Esa decision debe quedar declarada en el informe.

## Nombres de archivo sugeridos

- `stm32h743_datasheet.pdf`
- `w25q128jv_datasheet.pdf`
- `cc1120_datasheet.pdf`
- `cc1190_datasheet.pdf`
- `bq25713_datasheet.pdf`
- `ina219_datasheet.pdf`
- `tmp117_datasheet.pdf`
- `lis3mdl_datasheet.pdf`
- `bmi088_datasheet.pdf`
- `imtq_magnetorquer_board_brochure.pdf`
- `as7341_datasheet.pdf`
