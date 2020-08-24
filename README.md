# loadmcu

Load and flash MCU firmware image to MCU chip ATTiny1634 of NPCM7xx BMC.

## Building

```bash
./configure --host=arm-linux-gnueabi --target=arm-inux-gnueabi
make
```

## Usage

```bash
loadmcu -d <mcu_device> -s <fw_file>
```

**-d mcu_device:**
specify the mcu device node <ex: /dev/mcu0>

**-s fw_file:**
specify the mcu firmware file path  <ex: /tmp/image-mcu>
