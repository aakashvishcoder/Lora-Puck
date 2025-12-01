# Lora Puck

a Lora Puck made using an RP2040 microcontroller!

# Features:
- USBC Receptacle
- Programmable Microcontroller

# Images:

<img width="411" height="591" alt="Screenshot 2025-11-30 210822" src="https://github.com/user-attachments/assets/3bf2af28-a2cb-4683-8539-2a67bf7b4f28" />
<img width="418" height="596" alt="Screenshot 2025-11-30 210816" src="https://github.com/user-attachments/assets/4ef056b9-2cde-4743-8147-74aa8b75ec19" />
<img width="438" height="630" alt="Screenshot 2025-11-30 210807" src="https://github.com/user-attachments/assets/54e8275c-a148-42a1-8da0-71e120bb11b8" />
<img width="1321" height="897" alt="Screenshot 2025-11-30 210747" src="https://github.com/user-attachments/assets/1484a1f5-f7bd-4e58-923d-200739f7ea15" />

# Build of Materials (BOM)

| Reference        | Qty | Value     | DNP | Exclude from BOM | Exclude from Board | Footprint                                                                 | Datasheet                                                                 |
|------------------|-----|-----------|-----|------------------|--------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|
| 15uH1            | 1   | L2        |     |                  |                    | Inductor_SMD:L_0402_1005Metric                                            | ~                                                                         |
| AE1              | 1   | Antenna   |     |                  |                    | Connector_PinSocket_2.54mm:PinSocket_1x01_P2.54mm_Vertical                | ~                                                                         |
| C1,C2,C5,C6,C7,C8,C9,C10,C11,C12,C13,C15,C26 | 13  | 100nF     |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C3               | 1   | 470nF     |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C4,C14           | 2   | 1uF       |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C16              | 1   | 47nF      |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C17              | 1   | 47pF      |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C18              | 1   | 1nF       |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C19              | 1   | 39pF      |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C20,C21,C22,C23  | 4   | 3.3pF     |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| C24,C25          | 2   | 10uF      |     |                  |                    | Capacitor_SMD:C_0402_1005Metric                                           | ~                                                                         |
| FB1              | 1   | FerriteBead_Small | |                |                    | Inductor_SMD:L_0402_1005Metric                                            | ~                                                                         |
| FL1              | 1   | 0900FM15K0039 | |                  |                    | RF_Converter:Balun_Johanson_0900FM15K0039                                 | [Johanson Datasheet](https://www.johansontechnology.com/datasheets/0900FM15K0039/0900FM15K0039.pdf) |
| J1               | 1   | USB_C_Receptacle_USB2.0_16P | |        |                    | Connector_USB:USB_C_Receptacle_GCT_USB4105-xx-A_16P_TopMnt_Horizontal     | [USB Type-C Spec](https://www.usb.org/sites/default/files/documents/usb_type-c.zip) |
| L1               | 1   | 47nH      |     |                  |                    | Inductor_SMD:L_0402_1005Metric                                            | ~                                                                         |
| L3               | 1   | 9.1nH     |     |                  |                    | Inductor_SMD:L_0402_1005Metric                                            | ~                                                                         |
| R1               | 1   | 10k       |     |                  |                    | Resistor_SMD:R_0402_1005Metric                                            | ~                                                                         |
| R2,R3            | 2   | 27.4      |     |                  |                    | Resistor_SMD:R_0402_1005Metric                                            | ~                                                                         |
| R4,R6            | 2   | 1k        |     |                  |                    | Resistor_SMD:R_0402_1005Metric                                            | ~                                                                         |
| R5               | 1   | 100       |     |                  |                    | Resistor_SMD:R_0402_1005Metric                                            | ~                                                                         |
| R7,R8            | 2   | 5.1k      |     |                  |                    | Resistor_SMD:R_0402_1005Metric                                            | ~                                                                         |
| R9,R10           | 2   | 4.7k      |     |                  |                    | Resistor_SMD:R_0402_1005Metric                                            | ~                                                                         |
| SW1              | 1   | BOOTSEL   |     |                  |                    | Button_Switch_SMD:SW_Tactile_SPST_NO_Straight_CK_PTS636Sx25SMTRLFS        | ~                                                                         |
| SW2              | 1   | RESET     |     |                  |                    | Button_Switch_SMD:SW_Tactile_SPST_NO_Straight_CK_PTS636Sx25SMTRLFS        | ~                                                                         |
| U1               | 1   | SX1262IMLTRT | |                  |                    | Package_DFN_QFN:QFN-24-1EP_4x4mm_P0.5mm_EP2.6x2.6mm                       | [SX1262 Datasheet](https://semtech.file.force.com/sfc/dist/version/download/?oid=00DE0000000JelG&ids=0682R00000IjPWSQA3&d=%2Fa%2F2R000000Un7F%2FyT.fKdAr9ZAo3cJLc4F2cBdUsMftpT2vsOICP7NmvMo) |
| U2               | 1   | RP2040    |     |                  |                    | Package_DFN_QFN:QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm                       | [RP2040 Datasheet](https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf) |
| U3               | 1   | W25Q128JVS | |                  |                    | Package_SO:SOIC-8_5.3x5.3mm_P1.27mm                                       | [Winbond Datasheet](https://www.winbond.com/resource-files/w25q128jv_dtr%20revc%2003272018%20plus.pdf) |
| U4               | 1   | PE4259    |     |                  |                    | Package_TO_SOT_SMD:SOT-363_SC-70-6                                        | [PE4259 Datasheet](https://lcsc.com/datasheet/lcsc_datasheet_2409301504_pSemi-PE4259-63_C470892.pdf) |
| U5               | 1   | AP2112K-3.3 | |                  |                    | Package_TO_SOT_SMD:SOT-23-5                                               | [AP2112 Datasheet](https://www.diodes.com/assets/Datasheets/AP2112.pdf) |
| U6               | 1   | SHTC3     |     |                  |                    | Sensor_Humidity:Sensirion_DFN-4-1EP_2x2mm_P1mm_EP0.7x1.6mm                | [SHTC3 Datasheet](https://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/0_Datasheets/Humidity/Sensirion_Humidity_Sensors_SHTC3_Datasheet.pdf) |
| Y1               | 1   | 32MHz     |     |                  |                    | Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm                                   | ~                                                                         |
| Y2               | 1   | 12MHz     |     |                  |                    | Crystal:Crystal_SMD_Abracon_ABM8G-4Pin_3.2x2.5mm                          | ~                                                                         |
