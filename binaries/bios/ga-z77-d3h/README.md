## <div style="color: red;"> WARNING! This will work ONLY with board rev 1.1! </div>

# Gigabyte GA-Z77-D3H REV 1.1

## Board info

- **Manufacturer:** Gigabyte
- **Stock BIOS:** F18
- **Newest BIOS:** F23b (beta) / F22 (stable)
- **CPU Socket:** LGA 1155
- **Chipset:** Intel Z77
- **RAM:** 4xDDR3, max 32GB (configuration 4:2:3:1)
- **Peripherials:**
  - **PCI Express:**
    - **x16:** 1 (PCIe 3.0)
    - **x4:** 1 (PCIe 2.0)
    - **x1:** 2 (PCIe 2.0)
  - **USB:**
    - **3.0:** 2 internal / 4 rear panel
    - **2.0/1.1:** 6 internal / 4 rear panel
  - **SATA:**
    - **6Gbps:** 2
    - **3Gbps:** 4
    - **mSATA:** 1
  - **Graphics ports**:
    - DVI, HDMI and VGA (max any 2 ports simultaneously)
- **EAN:** `4719331806156`

## Modded BIOS

This modded BIOS includes PCIe NVMe support from *NvmExpressDxe_Small* module. It's based on newest BETA bios for this motherboard, `f23b`.

Edited with MMTool `4.50.0.23`

It allows to boot from NVMe devices on Gigabyte *GA-Z77-D3H rev 1.1* motherboard.

Unfortunately there's only one PCIe 3.0 slot on the motherboard, that will be most likely occupated by your graphics card.

**Western Digital SN730** (256GB) connected through PCIe 2.0 on *GA-Z77-D3H rev 1.1*:

![wd](https://i.imgur.com/1T1wonH.png)

**SanDisk SSD Plus** (120GB) connected through SATA 3 on *GA-Z77-D3H rev 1.1*:

![sandisk](https://i.imgur.com/nCbX69D.png)