# cmf-watchface-specs

Header/Footer (0x24)

| Offset | Bytes                                      | Description                                                                 |
|--------|--------------------------------------------|-----------------------------------------------------------------------------|
| 0x00   | 00 00 00 00                                | CRC (0x4)                               |
| 0x04   | 01 00 00 02                                | Version (0x4)                                                                |
| 0x08   | 42 6F 6C 64 00 00 00 00 00 00 00 00 00 00 00 00 | Name (0x10)                                                                 |
| 0x18   | 51 26 00 00                                | Full length - 0x24 (0x4)                                                    |
| 0x1C   | 7A 25 00 00                                | Asset store length (from first asset header to last byte of last asset) (0x4) |
| 0x20   | 00 00 00 00                                | CRC (0x4)                               |
