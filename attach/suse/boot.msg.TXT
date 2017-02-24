klogd 1.4.1, log source = ksyslog started.
<6>[    0.000000] Initializing cgroup subsys cpuset
<6>[    0.000000] Initializing cgroup subsys cpu
<5>[    0.000000] Linux version 3.0.13-0.27-default (geeko@buildhost) (gcc version 4.3.4 [gcc-4_3-branch revision 152973] (SUSE Linux) ) #1 SMP Wed Feb 15 13:33:49 UTC 2012 (d73692b)
<6>[    0.000000] Command line: root=/dev/sda2 resume=/dev/sda1 splash=silent crashkernel=256M-:128M vga=0x317
<6>[    0.000000] Disabled fast string operations
<6>[    0.000000] BIOS-provided physical RAM map:
<6>[    0.000000]  BIOS-e820: 0000000000000000 - 000000000009f000 (usable)
<6>[    0.000000]  BIOS-e820: 000000000009f000 - 00000000000a0000 (reserved)
<6>[    0.000000]  BIOS-e820: 00000000000dc000 - 0000000000100000 (reserved)
<6>[    0.000000]  BIOS-e820: 0000000000100000 - 000000007fee0000 (usable)
<6>[    0.000000]  BIOS-e820: 000000007fee0000 - 000000007feff000 (ACPI data)
<6>[    0.000000]  BIOS-e820: 000000007feff000 - 000000007ff00000 (ACPI NVS)
<6>[    0.000000]  BIOS-e820: 000000007ff00000 - 0000000080000000 (usable)
<6>[    0.000000]  BIOS-e820: 00000000f0000000 - 00000000f8000000 (reserved)
<6>[    0.000000]  BIOS-e820: 00000000fec00000 - 00000000fec10000 (reserved)
<6>[    0.000000]  BIOS-e820: 00000000fee00000 - 00000000fee01000 (reserved)
<6>[    0.000000]  BIOS-e820: 00000000fffe0000 - 0000000100000000 (reserved)
<6>[    0.000000] NX (Execute Disable) protection: active
<6>[    0.000000] DMI present.
<7>[    0.000000] DMI: VMware, Inc. VMware Virtual Platform/440BX Desktop Reference Platform, BIOS 6.00 07/02/2015
<6>[    0.000000] Hypervisor detected: VMware
<7>[    0.000000] e820 update range: 0000000000000000 - 0000000000010000 (usable) ==> (reserved)
<7>[    0.000000] e820 remove range: 00000000000a0000 - 0000000000100000 (usable)
<6>[    0.000000] No AGP bridge found
<6>[    0.000000] last_pfn = 0x80000 max_arch_pfn = 0x400000000
<7>[    0.000000] MTRR default type: uncachable
<7>[    0.000000] MTRR fixed ranges enabled:
<7>[    0.000000]   00000-9FFFF write-back
<7>[    0.000000]   A0000-BFFFF uncachable
<7>[    0.000000]   C0000-CBFFF write-protect
<7>[    0.000000]   CC000-EFFFF uncachable
<7>[    0.000000]   F0000-FFFFF write-protect
<7>[    0.000000] MTRR variable ranges enabled:
<7>[    0.000000]   0 base 00C0000000 mask FFC0000000 uncachable
<7>[    0.000000]   1 base 0000000000 mask FF00000000 write-back
<7>[    0.000000]   2 disabled
<7>[    0.000000]   3 disabled
<7>[    0.000000]   4 disabled
<7>[    0.000000]   5 disabled
<7>[    0.000000]   6 disabled
<7>[    0.000000]   7 disabled
<6>[    0.000000] x86 PAT enabled: cpu 0, old 0x7040600070406, new 0x7010600070106
<6>[    0.000000] found SMP MP-table at [ffff8800000f6a80] f6a80
<7>[    0.000000] initial memory mapped : 0 - 20000000
<7>[    0.000000] Base memory trampoline at [ffff88000009a000] 9a000 size 20480
<6>[    0.000000] init_memory_mapping: 0000000000000000-0000000080000000
<7>[    0.000000]  0000000000 - 0080000000 page 2M
<7>[    0.000000] kernel direct mapping tables up to 80000000 @ 1fffd000-20000000
<6>[    0.000000] RAMDISK: 378d5000 - 37ff0000
<6>[    0.000000] Reserving 128MB of memory at 752MB for crashkernel (System RAM: 2048MB)
<4>[    0.000000] ACPI: RSDP 00000000000f6a10 00024 (v02 PTLTD )
<4>[    0.000000] ACPI: XSDT 000000007feed637 0006C (v01 DELL   PE_SC3   06040000 VMW  01324272)
<4>[    0.000000] ACPI: FACP 000000007fefee73 000F4 (v04 INTEL  440BX    06040000 PTL  000F4240)
<4>[    0.000000] ACPI: DSDT 000000007feee03e 10C6A (v01 PTLTD  Custom   06040000 MSFT 03000001)
<4>[    0.000000] ACPI: FACS 000000007fefffc0 00040
<4>[    0.000000] ACPI: SLIC 000000007fefecfd 00176 (v01 DELL   PE_SC3   06040000 MSFT 00000001)
<4>[    0.000000] ACPI: MSDM 000000007fefeca8 00055 (v03 DELL   PE_SC3   06040000 ASL  00040000)
<4>[    0.000000] ACPI: BOOT 000000007feee016 00028 (v01 PTLTD  $SBFTBL$ 06040000  LTP 00000001)
<4>[    0.000000] ACPI: APIC 000000007feedc2f 003C2 (v01 PTLTD  ? APIC   06040000  LTP 00000000)
<4>[    0.000000] ACPI: MCFG 000000007feedbf3 0003C (v01 PTLTD  $PCITBL$ 06040000  LTP 00000001)
<4>[    0.000000] ACPI: SRAT 000000007feed74b 004A8 (v02 VMWARE MEMPLUG  06040000 VMW  00000001)
<4>[    0.000000] ACPI: HPET 000000007feed713 00038 (v01 VMWARE VMW HPET 06040000 VMW  00000001)
<4>[    0.000000] ACPI: WAET 000000007feed6eb 00028 (v01 VMWARE VMW WAET 06040000 VMW  00000001)
<7>[    0.000000] ACPI: Local APIC address 0xfee00000
<7>[    0.000000] system APIC only can use physical flat
<6>[    0.000000] Setting APIC routing to physical flat.
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x00 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x02 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x04 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x06 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x08 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x0a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x0c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x0e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x10 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x12 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x14 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x16 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x18 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x1a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x1c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x1e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x20 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x22 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x24 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x26 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x28 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x2a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x2c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x2e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x30 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x32 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x34 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x36 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x38 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x3a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x3c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x3e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x40 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x42 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x44 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x46 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x48 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x4a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x4c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x4e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x50 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x52 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x54 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x56 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x58 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x5a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x5c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x5e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x60 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x62 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x64 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x66 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x68 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x6a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x6c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x6e -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x70 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x72 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x74 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x76 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x78 -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x7a -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x7c -> Node 0
<6>[    0.000000] SRAT: PXM 0 -> APIC 0x7e -> Node 0
<6>[    0.000000] SRAT: Node 0 PXM 0 0-a0000
<6>[    0.000000] SRAT: Node 0 PXM 0 100000-80000000
<6>[    0.000000] SRAT: Node 0 PXM 0 80000000-c0000000
<6>[    0.000000] NUMA: Node 0 [0,a0000) + [100000,80000000) -> [0,80000000)
<6>[    0.000000] Initmem setup node 0 0000000000000000-0000000080000000
<6>[    0.000000]   NODE_DATA [000000007ffd9000 - 000000007fffffff]
<7>[    0.000000]  [ffffea0000000000-ffffea0001bfffff] PMD -> [ffff88007d600000-ffff88007f1fffff] on node 0
<4>[    0.000000] Zone PFN ranges:
<4>[    0.000000]   DMA      0x00000010 -> 0x00001000
<4>[    0.000000]   DMA32    0x00001000 -> 0x00100000
<4>[    0.000000]   Normal   empty
<4>[    0.000000] Movable zone start PFN for each node
<4>[    0.000000] early_node_map[3] active PFN ranges
<4>[    0.000000]     0: 0x00000010 -> 0x0000009f
<4>[    0.000000]     0: 0x00000100 -> 0x0007fee0
<4>[    0.000000]     0: 0x0007ff00 -> 0x00080000
<7>[    0.000000] On node 0 totalpages: 524143
<7>[    0.000000]   DMA zone: 56 pages used for memmap
<7>[    0.000000]   DMA zone: 5 pages reserved
<7>[    0.000000]   DMA zone: 3922 pages, LIFO batch:0
<7>[    0.000000]   DMA32 zone: 7112 pages used for memmap
<7>[    0.000000]   DMA32 zone: 513048 pages, LIFO batch:31
<6>[    0.000000] ACPI: PM-Timer IO Port: 0x1008
<7>[    0.000000] ACPI: Local APIC address 0xfee00000
<7>[    0.000000] system APIC only can use physical flat
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x00] lapic_id[0x00] enabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x01] lapic_id[0x02] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x02] lapic_id[0x04] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x03] lapic_id[0x06] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x04] lapic_id[0x08] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x05] lapic_id[0x0a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x06] lapic_id[0x0c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x07] lapic_id[0x0e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x08] lapic_id[0x10] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x09] lapic_id[0x12] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x0a] lapic_id[0x14] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x0b] lapic_id[0x16] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x0c] lapic_id[0x18] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x0d] lapic_id[0x1a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x0e] lapic_id[0x1c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x0f] lapic_id[0x1e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x10] lapic_id[0x20] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x11] lapic_id[0x22] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x12] lapic_id[0x24] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x13] lapic_id[0x26] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x14] lapic_id[0x28] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x15] lapic_id[0x2a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x16] lapic_id[0x2c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x17] lapic_id[0x2e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x18] lapic_id[0x30] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x19] lapic_id[0x32] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x1a] lapic_id[0x34] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x1b] lapic_id[0x36] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x1c] lapic_id[0x38] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x1d] lapic_id[0x3a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x1e] lapic_id[0x3c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x1f] lapic_id[0x3e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x20] lapic_id[0x40] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x21] lapic_id[0x42] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x22] lapic_id[0x44] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x23] lapic_id[0x46] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x24] lapic_id[0x48] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x25] lapic_id[0x4a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x26] lapic_id[0x4c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x27] lapic_id[0x4e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x28] lapic_id[0x50] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x29] lapic_id[0x52] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x2a] lapic_id[0x54] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x2b] lapic_id[0x56] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x2c] lapic_id[0x58] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x2d] lapic_id[0x5a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x2e] lapic_id[0x5c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x2f] lapic_id[0x5e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x30] lapic_id[0x60] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x31] lapic_id[0x62] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x32] lapic_id[0x64] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x33] lapic_id[0x66] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x34] lapic_id[0x68] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x35] lapic_id[0x6a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x36] lapic_id[0x6c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x37] lapic_id[0x6e] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x38] lapic_id[0x70] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x39] lapic_id[0x72] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x3a] lapic_id[0x74] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x3b] lapic_id[0x76] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x3c] lapic_id[0x78] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x3d] lapic_id[0x7a] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x3e] lapic_id[0x7c] disabled)
<6>[    0.000000] ACPI: LAPIC (acpi_id[0x3f] lapic_id[0x7e] disabled)
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x00] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x01] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x02] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x03] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x04] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x05] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x06] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x07] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x08] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x09] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x0a] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x0b] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x0c] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x0d] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x0e] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x0f] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x10] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x11] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x12] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x13] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x14] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x15] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x16] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x17] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x18] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x19] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x1a] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x1b] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x1c] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x1d] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x1e] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x1f] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x20] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x21] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x22] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x23] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x24] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x25] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x26] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x27] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x28] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x29] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x2a] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x2b] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x2c] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x2d] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x2e] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x2f] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x30] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x31] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x32] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x33] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x34] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x35] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x36] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x37] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x38] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x39] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x3a] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x3b] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x3c] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x3d] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x3e] high edge lint[0x1])
<6>[    0.000000] ACPI: LAPIC_NMI (acpi_id[0x3f] high edge lint[0x1])
<6>[    0.000000] ACPI: IOAPIC (id[0x01] address[0xfec00000] gsi_base[0])
<6>[    0.000000] IOAPIC[0]: apic_id 1, version 17, address 0xfec00000, GSI 0-23
<6>[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 high edge)
<7>[    0.000000] ACPI: IRQ0 used by override.
<7>[    0.000000] ACPI: IRQ2 used by override.
<7>[    0.000000] ACPI: IRQ9 used by override.
<6>[    0.000000] Using ACPI (MADT) for SMP configuration information
<6>[    0.000000] ACPI: HPET id: 0x8086af01 base: 0xfed00000
<6>[    0.000000] SMP: Allowing 64 CPUs, 63 hotplug CPUs
<7>[    0.000000] nr_irqs_gsi: 40
<6>[    0.000000] PM: Registered nosave memory: 000000000009f000 - 00000000000a0000
<6>[    0.000000] PM: Registered nosave memory: 00000000000a0000 - 00000000000dc000
<6>[    0.000000] PM: Registered nosave memory: 00000000000dc000 - 0000000000100000
<6>[    0.000000] PM: Registered nosave memory: 000000007fee0000 - 000000007feff000
<6>[    0.000000] PM: Registered nosave memory: 000000007feff000 - 000000007ff00000
<6>[    0.000000] Allocating PCI resources starting at 80000000 (gap: 80000000:70000000)
<6>[    0.000000] Booting paravirtualized kernel on bare hardware
<6>[    0.000000] setup_percpu: NR_CPUS:4096 nr_cpumask_bits:64 nr_cpu_ids:64 nr_node_ids:1
<6>[    0.000000] PERCPU: Embedded 26 pages/cpu @ffff88007f600000 s74880 r8192 d23424 u131072
<7>[    0.000000] pcpu-alloc: s74880 r8192 d23424 u131072 alloc=1*2097152
<7>[    0.000000] pcpu-alloc: [0] 00 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 
<7>[    0.000000] pcpu-alloc: [0] 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 
<7>[    0.000000] pcpu-alloc: [0] 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47 
<7>[    0.000000] pcpu-alloc: [0] 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 
<4>[    0.000000] Built 1 zonelists in Node order, mobility grouping on.  Total pages: 516970
<4>[    0.000000] Policy zone: DMA32
<5>[    0.000000] Kernel command line: root=/dev/sda2 resume=/dev/sda1 splash=silent crashkernel=256M-:128M vga=0x317
<6>[    0.000000] bootsplash: silent mode.
<6>[    0.000000] PID hash table entries: 4096 (order: 3, 32768 bytes)
<6>[    0.000000] xsave/xrstor: enabled xstate_bv 0x7, cntxt size 0x340
<6>[    0.000000] Checking aperture...
<6>[    0.000000] No AGP bridge found
<6>[    0.000000] Memory: 1906132k/2097152k available (4405k kernel code, 580k absent, 190440k reserved, 7781k data, 1356k init)
<6>[    0.000000] Hierarchical RCU implementation.
<6>[    0.000000] 	RCU dyntick-idle grace-period acceleration is enabled.
<6>[    0.000000] NR_IRQS:262400 nr_irqs:1192 16
<6>[    0.000000] Extended CMOS year: 2000
<6>[    0.000000] Console: colour dummy device 80x25
<6>[    0.000000] console [tty0] enabled
<6>[    0.000000] allocated 16777216 bytes of page_cgroup
<6>[    0.000000] please try 'cgroup_disable=memory' option if you don't want memory cgroups
<7>[    0.000000] hpet clockevent registered
<6>[    0.004000] TSC freq read from hypervisor : 2601.000 MHz
<4>[    0.004000] Detected 2601.000 MHz processor.
<6>[    0.000085] Calibrating delay loop (skipped) preset value.. 5202.00 BogoMIPS (lpj=10404000)
<6>[    0.000091] pid_max: default: 65536 minimum: 512
<4>[    0.003593] kdb version 4.4 by Keith Owens, Scott Lurndal. Copyright SGI, All Rights Reserved
<6>[    0.012535] Security Framework initialized
<6>[    0.012556] AppArmor: AppArmor initialized
<6>[    0.018792] Dentry cache hash table entries: 262144 (order: 9, 2097152 bytes)
<6>[    0.065963] Inode-cache hash table entries: 131072 (order: 8, 1048576 bytes)
<6>[    0.096874] Mount-cache hash table entries: 256
<6>[    0.102325] Initializing cgroup subsys cpuacct
<6>[    0.102335] Initializing cgroup subsys memory
<6>[    0.102835] Initializing cgroup subsys devices
<6>[    0.102838] Initializing cgroup subsys freezer
<6>[    0.102840] Initializing cgroup subsys net_cls
<6>[    0.102842] Initializing cgroup subsys blkio
<6>[    0.102983] Initializing cgroup subsys perf_event
<6>[    0.107517] Disabled fast string operations
<6>[    0.107594] CPU: Physical Processor ID: 0
<4>[    0.107952] ENERGY_PERF_BIAS: Set to 'normal', was 'performance'
<4>[    0.107953] ENERGY_PERF_BIAS: View and update with x86_energy_perf_policy(8)
<6>[    0.108073] mce: CPU supports 0 MCE banks
<6>[    0.110491] SMP alternatives: switching to UP code
<6>[    0.362973] ACPI: Core revision 20110413
<6>[    0.423120] x2apic not enabled, IRQ remapping init failed
<6>[    0.431089] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
<6>[    0.471511] CPU0: Intel(R) Core(TM) i5-3230M CPU @ 2.60GHz stepping 09
<6>[    0.578121] Performance Events: generic architected perfmon, core PMU driver.
<6>[    0.578333] ... version:                1
<6>[    0.578335] ... bit width:              48
<6>[    0.578336] ... generic registers:      4
<6>[    0.578338] ... value mask:             0000ffffffffffff
<6>[    0.578339] ... max period:             000000007fffffff
<6>[    0.578341] ... fixed-purpose events:   0
<6>[    0.578342] ... event mask:             000000000000000f
<6>[    0.581299] NMI watchdog enabled, takes one hw-pmu counter.
<6>[    0.581698] Brought up 1 CPUs
<6>[    0.581703] Total of 1 processors activated (5202.00 BogoMIPS).
<6>[    0.591051] devtmpfs: initialized
<6>[    0.596662] PM: Registering ACPI NVS region at 7feff000 (4096 bytes)
<6>[    0.597859] print_constraints: dummy: 
<6>[    0.598858] Time: 13:53:17  Date: 02/23/17
<6>[    0.601287] NET: Registered protocol family 16
<6>[    0.602100] ACPI: bus type pci registered
<6>[    0.603855] PCI: MMCONFIG for domain 0000 [bus 00-7f] at [mem 0xf0000000-0xf7ffffff] (base 0xf0000000)
<6>[    0.603860] PCI: MMCONFIG at [mem 0xf0000000-0xf7ffffff] reserved in E820
<6>[    0.625986] PCI: Using configuration type 1 for base access
<6>[    0.637435] bio: create slab <bio-0> at 0
<7>[    0.649072] ACPI: EC: Look up EC in DSDT
<5>[    0.661955] [Firmware Bug]: ACPI: BIOS _OSI(Linux) query ignored
<6>[    0.682955] ACPI: Interpreter enabled
<6>[    0.682962] ACPI: (supports S0 S1 S4 S5)
<6>[    0.682977] ACPI: Using IOAPIC for interrupt routing
<6>[    0.850098] ACPI: No dock devices found.
<6>[    0.850110] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
<6>[    0.854779] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-7f])
<6>[    0.861520] pci_root PNP0A03:00: host bridge window [mem 0x000a0000-0x000bffff]
<6>[    0.861525] pci_root PNP0A03:00: host bridge window [mem 0x000cc000-0x000cffff]
<6>[    0.861527] pci_root PNP0A03:00: host bridge window [mem 0x000d0000-0x000d3fff]
<6>[    0.861530] pci_root PNP0A03:00: host bridge window [mem 0x000d4000-0x000d7fff]
<6>[    0.861532] pci_root PNP0A03:00: host bridge window [mem 0x000d8000-0x000dbfff]
<6>[    0.861534] pci_root PNP0A03:00: host bridge window [mem 0xc0000000-0xfebfffff]
<6>[    0.861537] pci_root PNP0A03:00: host bridge window [io  0x0000-0x0cf7]
<6>[    0.861539] pci_root PNP0A03:00: host bridge window [io  0x0d00-0xfeff]
<7>[    0.861985] pci 0000:00:00.0: [8086:7190] type 0 class 0x000600
<7>[    0.866028] pci 0000:00:01.0: [8086:7191] type 1 class 0x000604
<7>[    0.872717] pci 0000:00:07.0: [8086:7110] type 0 class 0x000601
<7>[    0.878806] pci 0000:00:07.1: [8086:7111] type 0 class 0x000101
<7>[    0.883228] pci 0000:00:07.1: reg 20: [io  0x1060-0x106f]
<7>[    0.886927] pci 0000:00:07.3: [8086:7113] type 0 class 0x000680
<6>[    0.893551] pci 0000:00:07.3: quirk: [io  0x1000-0x103f] claimed by PIIX4 ACPI
<6>[    0.893642] pci 0000:00:07.3: quirk: [io  0x1040-0x104f] claimed by PIIX4 SMB
<7>[    0.895378] pci 0000:00:07.7: [15ad:0740] type 0 class 0x000880
<7>[    0.897456] pci 0000:00:07.7: reg 10: [io  0x1080-0x10bf]
<7>[    0.899753] pci 0000:00:07.7: reg 14: [mem 0xfebfe000-0xfebfffff 64bit]
<7>[    0.910213] pci 0000:00:0f.0: [15ad:0405] type 0 class 0x000300
<7>[    0.914851] pci 0000:00:0f.0: reg 10: [io  0x1070-0x107f]
<7>[    0.918390] pci 0000:00:0f.0: reg 14: [mem 0xe8000000-0xefffffff pref]
<7>[    0.922374] pci 0000:00:0f.0: reg 18: [mem 0xfe000000-0xfe7fffff]
<7>[    0.937764] pci 0000:00:0f.0: reg 30: [mem 0x00000000-0x00007fff pref]
<7>[    0.939635] pci 0000:00:10.0: [1000:0030] type 0 class 0x000100
<7>[    0.942049] pci 0000:00:10.0: reg 10: [io  0x1400-0x14ff]
<7>[    0.945165] pci 0000:00:10.0: reg 14: [mem 0xfeba0000-0xfebbffff 64bit]
<7>[    0.949799] pci 0000:00:10.0: reg 1c: [mem 0xfebc0000-0xfebdffff 64bit]
<7>[    0.955227] pci 0000:00:10.0: reg 30: [mem 0x00000000-0x00003fff pref]
<7>[    0.956451] pci 0000:00:11.0: [15ad:0790] type 1 class 0x000604
<7>[    0.961449] pci 0000:00:15.0: [15ad:07a0] type 1 class 0x000604
<7>[    0.969940] pci 0000:00:15.0: PME# supported from D0 D3hot D3cold
<7>[    0.970151] pci 0000:00:15.0: PME# disabled
<7>[    0.972661] pci 0000:00:15.1: [15ad:07a0] type 1 class 0x000604
<7>[    0.976687] pci 0000:00:15.1: PME# supported from D0 D3hot D3cold
<7>[    0.976844] pci 0000:00:15.1: PME# disabled
<7>[    0.979115] pci 0000:00:15.2: [15ad:07a0] type 1 class 0x000604
<7>[    0.983349] pci 0000:00:15.2: PME# supported from D0 D3hot D3cold
<7>[    0.983580] pci 0000:00:15.2: PME# disabled
<7>[    0.985304] pci 0000:00:15.3: [15ad:07a0] type 1 class 0x000604
<7>[    0.990139] pci 0000:00:15.3: PME# supported from D0 D3hot D3cold
<7>[    0.990312] pci 0000:00:15.3: PME# disabled
<7>[    0.992539] pci 0000:00:15.4: [15ad:07a0] type 1 class 0x000604
<7>[    0.997351] pci 0000:00:15.4: PME# supported from D0 D3hot D3cold
<7>[    0.997586] pci 0000:00:15.4: PME# disabled
<7>[    0.999180] pci 0000:00:15.5: [15ad:07a0] type 1 class 0x000604
<7>[    1.003665] pci 0000:00:15.5: PME# supported from D0 D3hot D3cold
<7>[    1.004787] pci 0000:00:15.5: PME# disabled
<7>[    1.010043] pci 0000:00:15.6: [15ad:07a0] type 1 class 0x000604
<7>[    1.015914] pci 0000:00:15.6: PME# supported from D0 D3hot D3cold
<7>[    1.016085] pci 0000:00:15.6: PME# disabled
<7>[    1.018295] pci 0000:00:15.7: [15ad:07a0] type 1 class 0x000604
<7>[    1.022798] pci 0000:00:15.7: PME# supported from D0 D3hot D3cold
<7>[    1.022966] pci 0000:00:15.7: PME# disabled
<7>[    1.024948] pci 0000:00:16.0: [15ad:07a0] type 1 class 0x000604
<7>[    1.032788] pci 0000:00:16.0: PME# supported from D0 D3hot D3cold
<7>[    1.032957] pci 0000:00:16.0: PME# disabled
<7>[    1.034595] pci 0000:00:16.1: [15ad:07a0] type 1 class 0x000604
<7>[    1.038723] pci 0000:00:16.1: PME# supported from D0 D3hot D3cold
<7>[    1.038892] pci 0000:00:16.1: PME# disabled
<7>[    1.041140] pci 0000:00:16.2: [15ad:07a0] type 1 class 0x000604
<7>[    1.045458] pci 0000:00:16.2: PME# supported from D0 D3hot D3cold
<7>[    1.045666] pci 0000:00:16.2: PME# disabled
<7>[    1.047573] pci 0000:00:16.3: [15ad:07a0] type 1 class 0x000604
<7>[    1.052803] pci 0000:00:16.3: PME# supported from D0 D3hot D3cold
<7>[    1.052972] pci 0000:00:16.3: PME# disabled
<7>[    1.054617] pci 0000:00:16.4: [15ad:07a0] type 1 class 0x000604
<7>[    1.059978] pci 0000:00:16.4: PME# supported from D0 D3hot D3cold
<7>[    1.060150] pci 0000:00:16.4: PME# disabled
<7>[    1.061964] pci 0000:00:16.5: [15ad:07a0] type 1 class 0x000604
<7>[    1.069076] pci 0000:00:16.5: PME# supported from D0 D3hot D3cold
<7>[    1.069347] pci 0000:00:16.5: PME# disabled
<7>[    1.071634] pci 0000:00:16.6: [15ad:07a0] type 1 class 0x000604
<7>[    1.077754] pci 0000:00:16.6: PME# supported from D0 D3hot D3cold
<7>[    1.077923] pci 0000:00:16.6: PME# disabled
<7>[    1.079741] pci 0000:00:16.7: [15ad:07a0] type 1 class 0x000604
<7>[    1.083766] pci 0000:00:16.7: PME# supported from D0 D3hot D3cold
<7>[    1.083936] pci 0000:00:16.7: PME# disabled
<7>[    1.085888] pci 0000:00:17.0: [15ad:07a0] type 1 class 0x000604
<7>[    1.095992] pci 0000:00:17.0: PME# supported from D0 D3hot D3cold
<7>[    1.096204] pci 0000:00:17.0: PME# disabled
<7>[    1.098352] pci 0000:00:17.1: [15ad:07a0] type 1 class 0x000604
<7>[    1.102476] pci 0000:00:17.1: PME# supported from D0 D3hot D3cold
<7>[    1.102643] pci 0000:00:17.1: PME# disabled
<7>[    1.105965] pci 0000:00:17.2: [15ad:07a0] type 1 class 0x000604
<7>[    1.111575] pci 0000:00:17.2: PME# supported from D0 D3hot D3cold
<7>[    1.111804] pci 0000:00:17.2: PME# disabled
<7>[    1.116226] pci 0000:00:17.3: [15ad:07a0] type 1 class 0x000604
<7>[    1.121429] pci 0000:00:17.3: PME# supported from D0 D3hot D3cold
<7>[    1.121598] pci 0000:00:17.3: PME# disabled
<7>[    1.123735] pci 0000:00:17.4: [15ad:07a0] type 1 class 0x000604
<7>[    1.129672] pci 0000:00:17.4: PME# supported from D0 D3hot D3cold
<7>[    1.129891] pci 0000:00:17.4: PME# disabled
<7>[    1.133445] pci 0000:00:17.5: [15ad:07a0] type 1 class 0x000604
<7>[    1.140053] pci 0000:00:17.5: PME# supported from D0 D3hot D3cold
<7>[    1.140223] pci 0000:00:17.5: PME# disabled
<7>[    1.142455] pci 0000:00:17.6: [15ad:07a0] type 1 class 0x000604
<7>[    1.147562] pci 0000:00:17.6: PME# supported from D0 D3hot D3cold
<7>[    1.147782] pci 0000:00:17.6: PME# disabled
<7>[    1.149539] pci 0000:00:17.7: [15ad:07a0] type 1 class 0x000604
<7>[    1.154651] pci 0000:00:17.7: PME# supported from D0 D3hot D3cold
<7>[    1.154875] pci 0000:00:17.7: PME# disabled
<7>[    1.156583] pci 0000:00:18.0: [15ad:07a0] type 1 class 0x000604
<7>[    1.161511] pci 0000:00:18.0: PME# supported from D0 D3hot D3cold
<7>[    1.161683] pci 0000:00:18.0: PME# disabled
<7>[    1.163750] pci 0000:00:18.1: [15ad:07a0] type 1 class 0x000604
<7>[    1.172164] pci 0000:00:18.1: PME# supported from D0 D3hot D3cold
<7>[    1.173198] pci 0000:00:18.1: PME# disabled
<7>[    1.175331] pci 0000:00:18.2: [15ad:07a0] type 1 class 0x000604
<7>[    1.179288] pci 0000:00:18.2: PME# supported from D0 D3hot D3cold
<7>[    1.179455] pci 0000:00:18.2: PME# disabled
<7>[    1.181320] pci 0000:00:18.3: [15ad:07a0] type 1 class 0x000604
<7>[    1.185575] pci 0000:00:18.3: PME# supported from D0 D3hot D3cold
<7>[    1.185847] pci 0000:00:18.3: PME# disabled
<7>[    1.187750] pci 0000:00:18.4: [15ad:07a0] type 1 class 0x000604
<7>[    1.192334] pci 0000:00:18.4: PME# supported from D0 D3hot D3cold
<7>[    1.192511] pci 0000:00:18.4: PME# disabled
<7>[    1.194242] pci 0000:00:18.5: [15ad:07a0] type 1 class 0x000604
<7>[    1.198972] pci 0000:00:18.5: PME# supported from D0 D3hot D3cold
<7>[    1.199141] pci 0000:00:18.5: PME# disabled
<7>[    1.200905] pci 0000:00:18.6: [15ad:07a0] type 1 class 0x000604
<7>[    1.205084] pci 0000:00:18.6: PME# supported from D0 D3hot D3cold
<7>[    1.205253] pci 0000:00:18.6: PME# disabled
<7>[    1.207111] pci 0000:00:18.7: [15ad:07a0] type 1 class 0x000604
<7>[    1.212276] pci 0000:00:18.7: PME# supported from D0 D3hot D3cold
<7>[    1.212445] pci 0000:00:18.7: PME# disabled
<6>[    1.217795] pci 0000:00:01.0: PCI bridge to [bus 01-01]
<7>[    1.217916] pci 0000:00:01.0:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.218082] pci 0000:00:01.0:   bridge window [mem 0xfff00000-0x000fffff] (disabled)
<7>[    1.218248] pci 0000:00:01.0:   bridge window [mem 0xfff00000-0x000fffff pref] (disabled)
<7>[    1.220103] pci 0000:02:00.0: [15ad:0774] type 0 class 0x000c03
<7>[    1.224726] pci 0000:02:00.0: reg 20: [io  0x2080-0x209f]
<7>[    1.229325] pci 0000:02:01.0: [8086:100f] type 0 class 0x000200
<7>[    1.234199] pci 0000:02:01.0: reg 10: [mem 0xfd5c0000-0xfd5dffff 64bit]
<7>[    1.237050] pci 0000:02:01.0: reg 18: [mem 0xfdff0000-0xfdffffff 64bit]
<7>[    1.238959] pci 0000:02:01.0: reg 20: [io  0x2000-0x203f]
<7>[    1.242811] pci 0000:02:01.0: reg 30: [mem 0x00000000-0x0000ffff pref]
<7>[    1.245603] pci 0000:02:02.0: [1274:1371] type 0 class 0x000401
<7>[    1.247545] pci 0000:02:02.0: reg 10: [io  0x2040-0x207f]
<7>[    1.254511] pci 0000:02:03.0: [15ad:0770] type 0 class 0x000c03
<7>[    1.255888] pci 0000:02:03.0: reg 10: [mem 0xfd5ef000-0xfd5effff]
<6>[    1.268568] pci 0000:00:11.0: PCI bridge to [bus 02-02] (subtractive decode)
<7>[    1.268724] pci 0000:00:11.0:   bridge window [io  0x2000-0x3fff]
<7>[    1.269102] pci 0000:00:11.0:   bridge window [mem 0xfd500000-0xfdffffff]
<7>[    1.269540] pci 0000:00:11.0:   bridge window [mem 0xe7b00000-0xe7ffffff 64bit pref]
<7>[    1.269546] pci 0000:00:11.0:   bridge window [mem 0x000a0000-0x000bffff] (subtractive decode)
<7>[    1.269548] pci 0000:00:11.0:   bridge window [mem 0x000cc000-0x000cffff] (subtractive decode)
<7>[    1.269551] pci 0000:00:11.0:   bridge window [mem 0x000d0000-0x000d3fff] (subtractive decode)
<7>[    1.269553] pci 0000:00:11.0:   bridge window [mem 0x000d4000-0x000d7fff] (subtractive decode)
<7>[    1.269555] pci 0000:00:11.0:   bridge window [mem 0x000d8000-0x000dbfff] (subtractive decode)
<7>[    1.269558] pci 0000:00:11.0:   bridge window [mem 0xc0000000-0xfebfffff] (subtractive decode)
<7>[    1.269560] pci 0000:00:11.0:   bridge window [io  0x0000-0x0cf7] (subtractive decode)
<7>[    1.269562] pci 0000:00:11.0:   bridge window [io  0x0d00-0xfeff] (subtractive decode)
<6>[    1.273237] pci 0000:00:15.0: PCI bridge to [bus 03-03]
<7>[    1.273358] pci 0000:00:15.0:   bridge window [io  0x4000-0x4fff]
<7>[    1.273572] pci 0000:00:15.0:   bridge window [mem 0xfd400000-0xfd4fffff]
<7>[    1.273901] pci 0000:00:15.0:   bridge window [mem 0xe7a00000-0xe7afffff 64bit pref]
<6>[    1.278197] pci 0000:00:15.1: PCI bridge to [bus 04-04]
<7>[    1.278317] pci 0000:00:15.1:   bridge window [io  0x8000-0x8fff]
<7>[    1.278519] pci 0000:00:15.1:   bridge window [mem 0xfd000000-0xfd0fffff]
<7>[    1.278849] pci 0000:00:15.1:   bridge window [mem 0xe7600000-0xe76fffff 64bit pref]
<6>[    1.281905] pci 0000:00:15.2: PCI bridge to [bus 05-05]
<7>[    1.282022] pci 0000:00:15.2:   bridge window [io  0xc000-0xcfff]
<7>[    1.282188] pci 0000:00:15.2:   bridge window [mem 0xfcc00000-0xfccfffff]
<7>[    1.282583] pci 0000:00:15.2:   bridge window [mem 0xe7200000-0xe72fffff 64bit pref]
<6>[    1.285807] pci 0000:00:15.3: PCI bridge to [bus 06-06]
<7>[    1.285927] pci 0000:00:15.3:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.286208] pci 0000:00:15.3:   bridge window [mem 0xfc800000-0xfc8fffff]
<7>[    1.286591] pci 0000:00:15.3:   bridge window [mem 0xe6e00000-0xe6efffff 64bit pref]
<6>[    1.292495] pci 0000:00:15.4: PCI bridge to [bus 07-07]
<7>[    1.292618] pci 0000:00:15.4:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.292793] pci 0000:00:15.4:   bridge window [mem 0xfc400000-0xfc4fffff]
<7>[    1.293199] pci 0000:00:15.4:   bridge window [mem 0xe6a00000-0xe6afffff 64bit pref]
<6>[    1.296215] pci 0000:00:15.5: PCI bridge to [bus 08-08]
<7>[    1.296363] pci 0000:00:15.5:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.296530] pci 0000:00:15.5:   bridge window [mem 0xfc000000-0xfc0fffff]
<7>[    1.296921] pci 0000:00:15.5:   bridge window [mem 0xe6600000-0xe66fffff 64bit pref]
<6>[    1.299867] pci 0000:00:15.6: PCI bridge to [bus 09-09]
<7>[    1.299983] pci 0000:00:15.6:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.300150] pci 0000:00:15.6:   bridge window [mem 0xfbc00000-0xfbcfffff]
<7>[    1.300524] pci 0000:00:15.6:   bridge window [mem 0xe6200000-0xe62fffff 64bit pref]
<6>[    1.303644] pci 0000:00:15.7: PCI bridge to [bus 0a-0a]
<7>[    1.303764] pci 0000:00:15.7:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.303930] pci 0000:00:15.7:   bridge window [mem 0xfb800000-0xfb8fffff]
<7>[    1.304259] pci 0000:00:15.7:   bridge window [mem 0xe5e00000-0xe5efffff 64bit pref]
<6>[    1.308821] pci 0000:00:16.0: PCI bridge to [bus 0b-0b]
<7>[    1.309065] pci 0000:00:16.0:   bridge window [io  0x5000-0x5fff]
<7>[    1.309328] pci 0000:00:16.0:   bridge window [mem 0xfd300000-0xfd3fffff]
<7>[    1.309687] pci 0000:00:16.0:   bridge window [mem 0xe7900000-0xe79fffff 64bit pref]
<6>[    1.313368] pci 0000:00:16.1: PCI bridge to [bus 0c-0c]
<7>[    1.313488] pci 0000:00:16.1:   bridge window [io  0x9000-0x9fff]
<7>[    1.313653] pci 0000:00:16.1:   bridge window [mem 0xfcf00000-0xfcffffff]
<7>[    1.313981] pci 0000:00:16.1:   bridge window [mem 0xe7500000-0xe75fffff 64bit pref]
<6>[    1.317436] pci 0000:00:16.2: PCI bridge to [bus 0d-0d]
<7>[    1.317556] pci 0000:00:16.2:   bridge window [io  0xd000-0xdfff]
<7>[    1.317803] pci 0000:00:16.2:   bridge window [mem 0xfcb00000-0xfcbfffff]
<7>[    1.318131] pci 0000:00:16.2:   bridge window [mem 0xe7100000-0xe71fffff 64bit pref]
<6>[    1.322210] pci 0000:00:16.3: PCI bridge to [bus 0e-0e]
<7>[    1.322406] pci 0000:00:16.3:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.322579] pci 0000:00:16.3:   bridge window [mem 0xfc700000-0xfc7fffff]
<7>[    1.322921] pci 0000:00:16.3:   bridge window [mem 0xe6d00000-0xe6dfffff 64bit pref]
<6>[    1.326050] pci 0000:00:16.4: PCI bridge to [bus 0f-0f]
<7>[    1.326170] pci 0000:00:16.4:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.326454] pci 0000:00:16.4:   bridge window [mem 0xfc300000-0xfc3fffff]
<7>[    1.326883] pci 0000:00:16.4:   bridge window [mem 0xe6900000-0xe69fffff 64bit pref]
<6>[    1.331738] pci 0000:00:16.5: PCI bridge to [bus 10-10]
<7>[    1.331858] pci 0000:00:16.5:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.332026] pci 0000:00:16.5:   bridge window [mem 0xfbf00000-0xfbffffff]
<7>[    1.332392] pci 0000:00:16.5:   bridge window [mem 0xe6500000-0xe65fffff 64bit pref]
<6>[    1.335642] pci 0000:00:16.6: PCI bridge to [bus 11-11]
<7>[    1.335792] pci 0000:00:16.6:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.335998] pci 0000:00:16.6:   bridge window [mem 0xfbb00000-0xfbbfffff]
<7>[    1.336376] pci 0000:00:16.6:   bridge window [mem 0xe6100000-0xe61fffff 64bit pref]
<6>[    1.339983] pci 0000:00:16.7: PCI bridge to [bus 12-12]
<7>[    1.340101] pci 0000:00:16.7:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.340301] pci 0000:00:16.7:   bridge window [mem 0xfb700000-0xfb7fffff]
<7>[    1.340629] pci 0000:00:16.7:   bridge window [mem 0xe5d00000-0xe5dfffff 64bit pref]
<6>[    1.345613] pci 0000:00:17.0: PCI bridge to [bus 13-13]
<7>[    1.345761] pci 0000:00:17.0:   bridge window [io  0x6000-0x6fff]
<7>[    1.345966] pci 0000:00:17.0:   bridge window [mem 0xfd200000-0xfd2fffff]
<7>[    1.346435] pci 0000:00:17.0:   bridge window [mem 0xe7800000-0xe78fffff 64bit pref]
<6>[    1.350028] pci 0000:00:17.1: PCI bridge to [bus 14-14]
<7>[    1.350380] pci 0000:00:17.1:   bridge window [io  0xa000-0xafff]
<7>[    1.350688] pci 0000:00:17.1:   bridge window [mem 0xfce00000-0xfcefffff]
<7>[    1.351875] pci 0000:00:17.1:   bridge window [mem 0xe7400000-0xe74fffff 64bit pref]
<6>[    1.355557] pci 0000:00:17.2: PCI bridge to [bus 15-15]
<7>[    1.355794] pci 0000:00:17.2:   bridge window [io  0xe000-0xefff]
<7>[    1.356021] pci 0000:00:17.2:   bridge window [mem 0xfca00000-0xfcafffff]
<7>[    1.356469] pci 0000:00:17.2:   bridge window [mem 0xe7000000-0xe70fffff 64bit pref]
<6>[    1.360248] pci 0000:00:17.3: PCI bridge to [bus 16-16]
<7>[    1.360406] pci 0000:00:17.3:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.360625] pci 0000:00:17.3:   bridge window [mem 0xfc600000-0xfc6fffff]
<7>[    1.361171] pci 0000:00:17.3:   bridge window [mem 0xe6c00000-0xe6cfffff 64bit pref]
<6>[    1.365440] pci 0000:00:17.4: PCI bridge to [bus 17-17]
<7>[    1.365631] pci 0000:00:17.4:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.365801] pci 0000:00:17.4:   bridge window [mem 0xfc200000-0xfc2fffff]
<7>[    1.366200] pci 0000:00:17.4:   bridge window [mem 0xe6800000-0xe68fffff 64bit pref]
<6>[    1.370407] pci 0000:00:17.5: PCI bridge to [bus 18-18]
<7>[    1.370528] pci 0000:00:17.5:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.370694] pci 0000:00:17.5:   bridge window [mem 0xfbe00000-0xfbefffff]
<7>[    1.372572] pci 0000:00:17.5:   bridge window [mem 0xe6400000-0xe64fffff 64bit pref]
<6>[    1.376674] pci 0000:00:17.6: PCI bridge to [bus 19-19]
<7>[    1.376794] pci 0000:00:17.6:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.376960] pci 0000:00:17.6:   bridge window [mem 0xfba00000-0xfbafffff]
<7>[    1.377392] pci 0000:00:17.6:   bridge window [mem 0xe6000000-0xe60fffff 64bit pref]
<6>[    1.380852] pci 0000:00:17.7: PCI bridge to [bus 1a-1a]
<7>[    1.380975] pci 0000:00:17.7:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.381330] pci 0000:00:17.7:   bridge window [mem 0xfb600000-0xfb6fffff]
<7>[    1.381805] pci 0000:00:17.7:   bridge window [mem 0xe5c00000-0xe5cfffff 64bit pref]
<6>[    1.386375] pci 0000:00:18.0: PCI bridge to [bus 1b-1b]
<7>[    1.386544] pci 0000:00:18.0:   bridge window [io  0x7000-0x7fff]
<7>[    1.386770] pci 0000:00:18.0:   bridge window [mem 0xfd100000-0xfd1fffff]
<7>[    1.387297] pci 0000:00:18.0:   bridge window [mem 0xe7700000-0xe77fffff 64bit pref]
<6>[    1.392345] pci 0000:00:18.1: PCI bridge to [bus 1c-1c]
<7>[    1.392509] pci 0000:00:18.1:   bridge window [io  0xb000-0xbfff]
<7>[    1.392831] pci 0000:00:18.1:   bridge window [mem 0xfcd00000-0xfcdfffff]
<7>[    1.393361] pci 0000:00:18.1:   bridge window [mem 0xe7300000-0xe73fffff 64bit pref]
<6>[    1.396526] pci 0000:00:18.2: PCI bridge to [bus 1d-1d]
<7>[    1.396692] pci 0000:00:18.2:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.396920] pci 0000:00:18.2:   bridge window [mem 0xfc900000-0xfc9fffff]
<7>[    1.397545] pci 0000:00:18.2:   bridge window [mem 0xe6f00000-0xe6ffffff 64bit pref]
<6>[    1.402064] pci 0000:00:18.3: PCI bridge to [bus 1e-1e]
<7>[    1.403382] pci 0000:00:18.3:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.403609] pci 0000:00:18.3:   bridge window [mem 0xfc500000-0xfc5fffff]
<7>[    1.404120] pci 0000:00:18.3:   bridge window [mem 0xe6b00000-0xe6bfffff 64bit pref]
<6>[    1.407827] pci 0000:00:18.4: PCI bridge to [bus 1f-1f]
<7>[    1.408012] pci 0000:00:18.4:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.408232] pci 0000:00:18.4:   bridge window [mem 0xfc100000-0xfc1fffff]
<7>[    1.408655] pci 0000:00:18.4:   bridge window [mem 0xe6700000-0xe67fffff 64bit pref]
<6>[    1.412385] pci 0000:00:18.5: PCI bridge to [bus 20-20]
<7>[    1.412505] pci 0000:00:18.5:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.412671] pci 0000:00:18.5:   bridge window [mem 0xfbd00000-0xfbdfffff]
<7>[    1.413556] pci 0000:00:18.5:   bridge window [mem 0xe6300000-0xe63fffff 64bit pref]
<6>[    1.420653] pci 0000:00:18.6: PCI bridge to [bus 21-21]
<7>[    1.420814] pci 0000:00:18.6:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.421047] pci 0000:00:18.6:   bridge window [mem 0xfb900000-0xfb9fffff]
<7>[    1.421676] pci 0000:00:18.6:   bridge window [mem 0xe5f00000-0xe5ffffff 64bit pref]
<6>[    1.425939] pci 0000:00:18.7: PCI bridge to [bus 22-22]
<7>[    1.426134] pci 0000:00:18.7:   bridge window [io  0xf000-0x0000] (disabled)
<7>[    1.426898] pci 0000:00:18.7:   bridge window [mem 0xfb500000-0xfb5fffff]
<7>[    1.427337] pci 0000:00:18.7:   bridge window [mem 0xe5b00000-0xe5bfffff 64bit pref]
<7>[    1.445112] ACPI: PCI Interrupt Routing Table [\_SB_.PCI0._PRT]
<6>[    1.447157]  pci0000:00: Requesting ACPI _OSC control (0x1d)
<6>[    1.447844]  pci0000:00: ACPI _OSC control (0x15) granted
<6>[    1.930994] ACPI: PCI Interrupt Link [LNKA] (IRQs 3 4 5 6 7 *9 10 11 14 15)
<6>[    1.931231] ACPI: PCI Interrupt Link [LNKB] (IRQs 3 4 5 6 7 9 10 *11 14 15)
<6>[    1.931453] ACPI: PCI Interrupt Link [LNKC] (IRQs 3 4 5 6 7 9 *10 11 14 15)
<6>[    1.931750] ACPI: PCI Interrupt Link [LNKD] (IRQs 3 4 *5 6 7 9 10 11 14 15)
<6>[    1.932089] vgaarb: device added: PCI:0000:00:0f.0,decodes=io+mem,owns=io+mem,locks=none
<6>[    1.932107] vgaarb: loaded
<6>[    1.932950] PCI: Using ACPI for IRQ routing
<7>[    2.272907] PCI: pci_cache_line_size set to 64 bytes
<7>[    2.281140] reserve RAM buffer: 000000000009f000 - 000000000009ffff 
<7>[    2.281145] reserve RAM buffer: 000000007fee0000 - 000000007fffffff 
<6>[    2.281883] NetLabel: Initializing
<6>[    2.281888] NetLabel:  domain hash size = 128
<6>[    2.281890] NetLabel:  protocols = UNLABELED CIPSOv4
<6>[    2.281976] NetLabel:  unlabeled traffic allowed by default
<6>[    2.283633] hpet0: at MMIO 0xfed00000, IRQs 2, 8, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0
<6>[    2.283644] hpet0: 16 comparators, 64-bit 14.318180 MHz counter
<6>[    2.289708] Switching to clocksource hpet
<6>[    2.291925] Switched to NOHz mode on CPU #0
<6>[    2.318458] AppArmor: AppArmor Filesystem Enabled
<6>[    2.318563] pnp: PnP ACPI init
<6>[    2.318577] ACPI: bus type pnp registered
<7>[    2.324764] pnp 00:00: [bus 00-7f]
<7>[    2.324767] pnp 00:00: [mem 0x000a0000-0x000bffff window]
<7>[    2.324768] pnp 00:00: [mem 0x000c0000-0x000c3fff window]
<7>[    2.324770] pnp 00:00: [mem 0x000c4000-0x000c7fff window]
<7>[    2.324771] pnp 00:00: [mem 0x000c8000-0x000cbfff window]
<7>[    2.324772] pnp 00:00: [mem 0x000cc000-0x000cffff window]
<7>[    2.324773] pnp 00:00: [mem 0x000d0000-0x000d3fff window]
<7>[    2.324774] pnp 00:00: [mem 0x000d4000-0x000d7fff window]
<7>[    2.324776] pnp 00:00: [mem 0x000d8000-0x000dbfff window]
<7>[    2.324777] pnp 00:00: [mem 0x000dc000-0x000dffff window]
<7>[    2.324778] pnp 00:00: [mem 0x000e0000-0x000e3fff window]
<7>[    2.324779] pnp 00:00: [mem 0x000e4000-0x000e7fff window]
<7>[    2.324780] pnp 00:00: [mem 0x000e8000-0x000ebfff window]
<7>[    2.324782] pnp 00:00: [mem 0x000ec000-0x000effff window]
<7>[    2.324783] pnp 00:00: [mem 0xc0000000-0xfebfffff window]
<7>[    2.324784] pnp 00:00: [mem 0x00000000 window]
<7>[    2.324786] pnp 00:00: [io  0x0cf8-0x0cff]
<7>[    2.324787] pnp 00:00: [io  0x0000-0x0cf7 window]
<7>[    2.324788] pnp 00:00: [io  0x0d00-0xfeff window]
<7>[    2.324949] pnp 00:00: Plug and Play ACPI device, IDs PNP0a03 PNP0a08 (active)
<7>[    2.325291] pnp 00:01: [io  0x0010-0x001f]
<7>[    2.325292] pnp 00:01: [io  0x0024-0x0025]
<7>[    2.325293] pnp 00:01: [io  0x0028-0x0029]
<7>[    2.325294] pnp 00:01: [io  0x002c-0x002d]
<7>[    2.325367] pnp 00:01: [io  0x002e-0x002f]
<7>[    2.325368] pnp 00:01: [io  0x0030-0x0031]
<7>[    2.325370] pnp 00:01: [io  0x0034-0x0035]
<7>[    2.325371] pnp 00:01: [io  0x0038-0x0039]
<7>[    2.325372] pnp 00:01: [io  0x003c-0x003d]
<7>[    2.325373] pnp 00:01: [io  0x0050-0x0053]
<7>[    2.325374] pnp 00:01: [io  0x0072-0x0077]
<7>[    2.325375] pnp 00:01: [io  0x0080]
<7>[    2.325375] pnp 00:01: [io  0x0090-0x009f]
<7>[    2.325376] pnp 00:01: [io  0x00a4-0x00a5]
<7>[    2.325377] pnp 00:01: [io  0x00a8-0x00a9]
<7>[    2.325378] pnp 00:01: [io  0x00ac-0x00ad]
<7>[    2.325379] pnp 00:01: [io  0x00b0-0x00b5]
<7>[    2.325380] pnp 00:01: [io  0x00b8-0x00b9]
<7>[    2.325381] pnp 00:01: [io  0x00bc-0x00bd]
<7>[    2.325382] pnp 00:01: [io  0x1000-0x103f]
<7>[    2.325383] pnp 00:01: [io  0x1040-0x104f]
<7>[    2.325385] pnp 00:01: [io  0x0cf0-0x0cf1]
<6>[    2.325442] system 00:01: [io  0x1000-0x103f] has been reserved
<6>[    2.325447] system 00:01: [io  0x1040-0x104f] has been reserved
<6>[    2.325449] system 00:01: [io  0x0cf0-0x0cf1] has been reserved
<7>[    2.325452] system 00:01: Plug and Play ACPI device, IDs PNP0c02 (active)
<7>[    2.325460] pnp 00:02: [io  0x0000-0x000f]
<7>[    2.325461] pnp 00:02: [io  0x0081-0x008f]
<7>[    2.325463] pnp 00:02: [io  0x00c0-0x00df]
<7>[    2.325464] pnp 00:02: [dma 4]
<7>[    2.325550] pnp 00:02: Plug and Play ACPI device, IDs PNP0200 (active)
<7>[    2.325559] pnp 00:03: [io  0x0020-0x0021]
<7>[    2.325560] pnp 00:03: [io  0x00a0-0x00a1]
<7>[    2.325561] pnp 00:03: [io  0x04d0-0x04d1]
<7>[    2.325563] pnp 00:03: [irq 2 disabled]
<7>[    2.325576] pnp 00:03: Plug and Play ACPI device, IDs PNP0001 (active)
<7>[    2.325655] pnp 00:04: [io  0x0070-0x0071]
<7>[    2.325718] pnp 00:04: [irq 8]
<7>[    2.325734] pnp 00:04: Plug and Play ACPI device, IDs PNP0b00 (active)
<7>[    2.325741] pnp 00:05: [io  0x0061]
<7>[    2.325824] pnp 00:05: Plug and Play ACPI device, IDs PNP0800 (active)
<7>[    2.325832] pnp 00:06: [io  0x0060]
<7>[    2.325945] pnp 00:06: [io  0x0064]
<7>[    2.326002] pnp 00:06: [irq 1]
<7>[    2.326018] pnp 00:06: Plug and Play ACPI device, IDs PNP0303 (active)
<7>[    2.326155] pnp 00:07: [irq 12]
<7>[    2.326172] pnp 00:07: Plug and Play ACPI device, IDs PNP0f13 VMW0003 (active)
<7>[    2.327033] pnp 00:08: [mem 0xfed00000-0xfed003ff]
<6>[    2.327144] system 00:08: [mem 0xfed00000-0xfed003ff] has been reserved
<7>[    2.327148] system 00:08: Plug and Play ACPI device, IDs PNP0103 PNP0c01 (active)
<7>[    2.331417] pnp 00:09: [io  0x0378-0x037b]
<7>[    2.331484] pnp 00:09: [irq 7]
<7>[    2.332281] pnp 00:09: Plug and Play ACPI device, IDs PNP0400 (active)
<7>[    2.332860] pnp 00:0a: [io  0x03f8-0x03ff]
<7>[    2.332920] pnp 00:0a: [irq 4]
<7>[    2.333133] pnp 00:0a: Plug and Play ACPI device, IDs PNP0501 (active)
<7>[    2.334408] pnp 00:0b: [io  0x02f8-0x02ff]
<7>[    2.334473] pnp 00:0b: [irq 3]
<7>[    2.334562] pnp 00:0b: Plug and Play ACPI device, IDs PNP0501 (active)
<7>[    2.335413] pnp 00:0c: [io  0x03f0-0x03f5]
<7>[    2.335415] pnp 00:0c: [io  0x03f7]
<7>[    2.335492] pnp 00:0c: [irq 6]
<7>[    2.335495] pnp 00:0c: [dma 2]
<7>[    2.335881] pnp 00:0c: Plug and Play ACPI device, IDs PNP0700 (active)
<7>[    2.337052] pnp 00:0d: [mem 0xf0000000-0xf7ffffff]
<7>[    2.337055] pnp 00:0d: [io  0xfce0-0xfcff]
<7>[    2.337056] pnp 00:0d: [mem 0xfe800000-0xfe9fffff]
<6>[    2.337132] system 00:0d: [io  0xfce0-0xfcff] has been reserved
<6>[    2.337139] system 00:0d: [mem 0xf0000000-0xf7ffffff] has been reserved
<6>[    2.337142] system 00:0d: [mem 0xfe800000-0xfe9fffff] has been reserved
<7>[    2.337145] system 00:0d: Plug and Play ACPI device, IDs PNP0c02 (active)
<6>[    2.368254] pnp: PnP ACPI: found 14 devices
<6>[    2.368260] ACPI: ACPI bus type pnp unregistered
<7>[    2.383465] PCI: max bus depth: 1 pci_try_num: 2
<6>[    2.404182] pci 0000:00:0f.0: BAR 6: assigned [mem 0xc0000000-0xc0007fff pref]
<6>[    2.404193] pci 0000:00:10.0: BAR 6: assigned [mem 0xc0008000-0xc000bfff pref]
<6>[    2.404200] pci 0000:00:18.7: BAR 13: can't assign io (size 0x1000)
<6>[    2.404205] pci 0000:00:18.6: BAR 13: can't assign io (size 0x1000)
<6>[    2.404210] pci 0000:00:18.5: BAR 13: can't assign io (size 0x1000)
<6>[    2.404213] pci 0000:00:18.4: BAR 13: can't assign io (size 0x1000)
<6>[    2.404215] pci 0000:00:18.3: BAR 13: can't assign io (size 0x1000)
<6>[    2.404218] pci 0000:00:18.2: BAR 13: can't assign io (size 0x1000)
<6>[    2.404221] pci 0000:00:17.7: BAR 13: can't assign io (size 0x1000)
<6>[    2.404223] pci 0000:00:17.6: BAR 13: can't assign io (size 0x1000)
<6>[    2.404226] pci 0000:00:17.5: BAR 13: can't assign io (size 0x1000)
<6>[    2.404228] pci 0000:00:17.4: BAR 13: can't assign io (size 0x1000)
<6>[    2.404231] pci 0000:00:17.3: BAR 13: can't assign io (size 0x1000)
<6>[    2.404233] pci 0000:00:16.7: BAR 13: can't assign io (size 0x1000)
<6>[    2.404236] pci 0000:00:16.6: BAR 13: can't assign io (size 0x1000)
<6>[    2.404239] pci 0000:00:16.5: BAR 13: can't assign io (size 0x1000)
<6>[    2.404241] pci 0000:00:16.4: BAR 13: can't assign io (size 0x1000)
<6>[    2.404244] pci 0000:00:16.3: BAR 13: can't assign io (size 0x1000)
<6>[    2.404246] pci 0000:00:15.7: BAR 13: can't assign io (size 0x1000)
<6>[    2.404248] pci 0000:00:15.6: BAR 13: can't assign io (size 0x1000)
<6>[    2.404251] pci 0000:00:15.5: BAR 13: can't assign io (size 0x1000)
<6>[    2.404253] pci 0000:00:15.4: BAR 13: can't assign io (size 0x1000)
<6>[    2.404256] pci 0000:00:15.3: BAR 13: can't assign io (size 0x1000)
<6>[    2.404259] pci 0000:00:01.0: PCI bridge to [bus 01-01]
<6>[    2.404261] pci 0000:00:01.0:   bridge window [io  disabled]
<6>[    2.404516] pci 0000:00:01.0:   bridge window [mem disabled]
<6>[    2.404735] pci 0000:00:01.0:   bridge window [mem pref disabled]
<6>[    2.405137] pci 0000:02:01.0: BAR 6: assigned [mem 0xe7b00000-0xe7b0ffff pref]
<6>[    2.405143] pci 0000:00:11.0: PCI bridge to [bus 02-02]
<6>[    2.405230] pci 0000:00:11.0:   bridge window [io  0x2000-0x3fff]
<6>[    2.405479] pci 0000:00:11.0:   bridge window [mem 0xfd500000-0xfdffffff]
<6>[    2.405856] pci 0000:00:11.0:   bridge window [mem 0xe7b00000-0xe7ffffff 64bit pref]
<6>[    2.406195] pci 0000:00:15.0: PCI bridge to [bus 03-03]
<6>[    2.406281] pci 0000:00:15.0:   bridge window [io  0x4000-0x4fff]
<6>[    2.406529] pci 0000:00:15.0:   bridge window [mem 0xfd400000-0xfd4fffff]
<6>[    2.406697] pci 0000:00:15.0:   bridge window [mem 0xe7a00000-0xe7afffff 64bit pref]
<6>[    2.407131] pci 0000:00:15.1: PCI bridge to [bus 04-04]
<6>[    2.407218] pci 0000:00:15.1:   bridge window [io  0x8000-0x8fff]
<6>[    2.407465] pci 0000:00:15.1:   bridge window [mem 0xfd000000-0xfd0fffff]
<6>[    2.407631] pci 0000:00:15.1:   bridge window [mem 0xe7600000-0xe76fffff 64bit pref]
<6>[    2.408012] pci 0000:00:15.2: PCI bridge to [bus 05-05]
<6>[    2.408099] pci 0000:00:15.2:   bridge window [io  0xc000-0xcfff]
<6>[    2.408347] pci 0000:00:15.2:   bridge window [mem 0xfcc00000-0xfccfffff]
<6>[    2.408513] pci 0000:00:15.2:   bridge window [mem 0xe7200000-0xe72fffff 64bit pref]
<6>[    2.408859] pci 0000:00:15.3: PCI bridge to [bus 06-06]
<6>[    2.408861] pci 0000:00:15.3:   bridge window [io  disabled]
<6>[    2.409760] pci 0000:00:15.3:   bridge window [mem 0xfc800000-0xfc8fffff]
<6>[    2.409938] pci 0000:00:15.3:   bridge window [mem 0xe6e00000-0xe6efffff 64bit pref]
<6>[    2.410300] pci 0000:00:15.4: PCI bridge to [bus 07-07]
<6>[    2.410302] pci 0000:00:15.4:   bridge window [io  disabled]
<6>[    2.410552] pci 0000:00:15.4:   bridge window [mem 0xfc400000-0xfc4fffff]
<6>[    2.410719] pci 0000:00:15.4:   bridge window [mem 0xe6a00000-0xe6afffff 64bit pref]
<6>[    2.411117] pci 0000:00:15.5: PCI bridge to [bus 08-08]
<6>[    2.411120] pci 0000:00:15.5:   bridge window [io  disabled]
<6>[    2.411369] pci 0000:00:15.5:   bridge window [mem 0xfc000000-0xfc0fffff]
<6>[    2.411536] pci 0000:00:15.5:   bridge window [mem 0xe6600000-0xe66fffff 64bit pref]
<6>[    2.411883] pci 0000:00:15.6: PCI bridge to [bus 09-09]
<6>[    2.411885] pci 0000:00:15.6:   bridge window [io  disabled]
<6>[    2.412165] pci 0000:00:15.6:   bridge window [mem 0xfbc00000-0xfbcfffff]
<6>[    2.412332] pci 0000:00:15.6:   bridge window [mem 0xe6200000-0xe62fffff 64bit pref]
<6>[    2.412678] pci 0000:00:15.7: PCI bridge to [bus 0a-0a]
<6>[    2.412681] pci 0000:00:15.7:   bridge window [io  disabled]
<6>[    2.412965] pci 0000:00:15.7:   bridge window [mem 0xfb800000-0xfb8fffff]
<6>[    2.413132] pci 0000:00:15.7:   bridge window [mem 0xe5e00000-0xe5efffff 64bit pref]
<6>[    2.413479] pci 0000:00:16.0: PCI bridge to [bus 0b-0b]
<6>[    2.413755] pci 0000:00:16.0:   bridge window [io  0x5000-0x5fff]
<6>[    2.414042] pci 0000:00:16.0:   bridge window [mem 0xfd300000-0xfd3fffff]
<6>[    2.414209] pci 0000:00:16.0:   bridge window [mem 0xe7900000-0xe79fffff 64bit pref]
<6>[    2.414556] pci 0000:00:16.1: PCI bridge to [bus 0c-0c]
<6>[    2.414643] pci 0000:00:16.1:   bridge window [io  0x9000-0x9fff]
<6>[    2.414927] pci 0000:00:16.1:   bridge window [mem 0xfcf00000-0xfcffffff]
<6>[    2.415095] pci 0000:00:16.1:   bridge window [mem 0xe7500000-0xe75fffff 64bit pref]
<6>[    2.415452] pci 0000:00:16.2: PCI bridge to [bus 0d-0d]
<6>[    2.415539] pci 0000:00:16.2:   bridge window [io  0xd000-0xdfff]
<6>[    2.415789] pci 0000:00:16.2:   bridge window [mem 0xfcb00000-0xfcbfffff]
<6>[    2.416031] pci 0000:00:16.2:   bridge window [mem 0xe7100000-0xe71fffff 64bit pref]
<6>[    2.416401] pci 0000:00:16.3: PCI bridge to [bus 0e-0e]
<6>[    2.416404] pci 0000:00:16.3:   bridge window [io  disabled]
<6>[    2.416653] pci 0000:00:16.3:   bridge window [mem 0xfc700000-0xfc7fffff]
<6>[    2.416819] pci 0000:00:16.3:   bridge window [mem 0xe6d00000-0xe6dfffff 64bit pref]
<6>[    2.417201] pci 0000:00:16.4: PCI bridge to [bus 0f-0f]
<6>[    2.417204] pci 0000:00:16.4:   bridge window [io  disabled]
<6>[    2.417457] pci 0000:00:16.4:   bridge window [mem 0xfc300000-0xfc3fffff]
<6>[    2.417829] pci 0000:00:16.4:   bridge window [mem 0xe6900000-0xe69fffff 64bit pref]
<6>[    2.418208] pci 0000:00:16.5: PCI bridge to [bus 10-10]
<6>[    2.418210] pci 0000:00:16.5:   bridge window [io  disabled]
<6>[    2.418458] pci 0000:00:16.5:   bridge window [mem 0xfbf00000-0xfbffffff]
<6>[    2.418623] pci 0000:00:16.5:   bridge window [mem 0xe6500000-0xe65fffff 64bit pref]
<6>[    2.419039] pci 0000:00:16.6: PCI bridge to [bus 11-11]
<6>[    2.419041] pci 0000:00:16.6:   bridge window [io  disabled]
<6>[    2.419290] pci 0000:00:16.6:   bridge window [mem 0xfbb00000-0xfbbfffff]
<6>[    2.419457] pci 0000:00:16.6:   bridge window [mem 0xe6100000-0xe61fffff 64bit pref]
<6>[    2.419804] pci 0000:00:16.7: PCI bridge to [bus 12-12]
<6>[    2.419807] pci 0000:00:16.7:   bridge window [io  disabled]
<6>[    2.420063] pci 0000:00:16.7:   bridge window [mem 0xfb700000-0xfb7fffff]
<6>[    2.420230] pci 0000:00:16.7:   bridge window [mem 0xe5d00000-0xe5dfffff 64bit pref]
<6>[    2.420577] pci 0000:00:17.0: PCI bridge to [bus 13-13]
<6>[    2.420664] pci 0000:00:17.0:   bridge window [io  0x6000-0x6fff]
<6>[    2.421247] pci 0000:00:17.0:   bridge window [mem 0xfd200000-0xfd2fffff]
<6>[    2.422554] pci 0000:00:17.0:   bridge window [mem 0xe7800000-0xe78fffff 64bit pref]
<6>[    2.423177] pci 0000:00:17.1: PCI bridge to [bus 14-14]
<6>[    2.423296] pci 0000:00:17.1:   bridge window [io  0xa000-0xafff]
<6>[    2.423610] pci 0000:00:17.1:   bridge window [mem 0xfce00000-0xfcefffff]
<6>[    2.423830] pci 0000:00:17.1:   bridge window [mem 0xe7400000-0xe74fffff 64bit pref]
<6>[    2.424307] pci 0000:00:17.2: PCI bridge to [bus 15-15]
<6>[    2.424397] pci 0000:00:17.2:   bridge window [io  0xe000-0xefff]
<6>[    2.424647] pci 0000:00:17.2:   bridge window [mem 0xfca00000-0xfcafffff]
<6>[    2.424815] pci 0000:00:17.2:   bridge window [mem 0xe7000000-0xe70fffff 64bit pref]
<6>[    2.425248] pci 0000:00:17.3: PCI bridge to [bus 16-16]
<6>[    2.425251] pci 0000:00:17.3:   bridge window [io  disabled]
<6>[    2.425709] pci 0000:00:17.3:   bridge window [mem 0xfc600000-0xfc6fffff]
<6>[    2.425989] pci 0000:00:17.3:   bridge window [mem 0xe6c00000-0xe6cfffff 64bit pref]
<6>[    2.426377] pci 0000:00:17.4: PCI bridge to [bus 17-17]
<6>[    2.426380] pci 0000:00:17.4:   bridge window [io  disabled]
<6>[    2.426633] pci 0000:00:17.4:   bridge window [mem 0xfc200000-0xfc2fffff]
<6>[    2.426803] pci 0000:00:17.4:   bridge window [mem 0xe6800000-0xe68fffff 64bit pref]
<6>[    2.427244] pci 0000:00:17.5: PCI bridge to [bus 18-18]
<6>[    2.427247] pci 0000:00:17.5:   bridge window [io  disabled]
<6>[    2.427526] pci 0000:00:17.5:   bridge window [mem 0xfbe00000-0xfbefffff]
<6>[    2.427698] pci 0000:00:17.5:   bridge window [mem 0xe6400000-0xe64fffff 64bit pref]
<6>[    2.428212] pci 0000:00:17.6: PCI bridge to [bus 19-19]
<6>[    2.428216] pci 0000:00:17.6:   bridge window [io  disabled]
<6>[    2.428467] pci 0000:00:17.6:   bridge window [mem 0xfba00000-0xfbafffff]
<6>[    2.428638] pci 0000:00:17.6:   bridge window [mem 0xe6000000-0xe60fffff 64bit pref]
<6>[    2.429805] pci 0000:00:17.7: PCI bridge to [bus 1a-1a]
<6>[    2.429812] pci 0000:00:17.7:   bridge window [io  disabled]
<6>[    2.430194] pci 0000:00:17.7:   bridge window [mem 0xfb600000-0xfb6fffff]
<6>[    2.430419] pci 0000:00:17.7:   bridge window [mem 0xe5c00000-0xe5cfffff 64bit pref]
<6>[    2.430897] pci 0000:00:18.0: PCI bridge to [bus 1b-1b]
<6>[    2.431163] pci 0000:00:18.0:   bridge window [io  0x7000-0x7fff]
<6>[    2.431415] pci 0000:00:18.0:   bridge window [mem 0xfd100000-0xfd1fffff]
<6>[    2.431582] pci 0000:00:18.0:   bridge window [mem 0xe7700000-0xe77fffff 64bit pref]
<6>[    2.431984] pci 0000:00:18.1: PCI bridge to [bus 1c-1c]
<6>[    2.432072] pci 0000:00:18.1:   bridge window [io  0xb000-0xbfff]
<6>[    2.432320] pci 0000:00:18.1:   bridge window [mem 0xfcd00000-0xfcdfffff]
<6>[    2.432488] pci 0000:00:18.1:   bridge window [mem 0xe7300000-0xe73fffff 64bit pref]
<6>[    2.432881] pci 0000:00:18.2: PCI bridge to [bus 1d-1d]
<6>[    2.432884] pci 0000:00:18.2:   bridge window [io  disabled]
<6>[    2.433135] pci 0000:00:18.2:   bridge window [mem 0xfc900000-0xfc9fffff]
<6>[    2.433303] pci 0000:00:18.2:   bridge window [mem 0xe6f00000-0xe6ffffff 64bit pref]
<6>[    2.433859] pci 0000:00:18.3: PCI bridge to [bus 1e-1e]
<6>[    2.433862] pci 0000:00:18.3:   bridge window [io  disabled]
<6>[    2.434111] pci 0000:00:18.3:   bridge window [mem 0xfc500000-0xfc5fffff]
<6>[    2.434279] pci 0000:00:18.3:   bridge window [mem 0xe6b00000-0xe6bfffff 64bit pref]
<6>[    2.434625] pci 0000:00:18.4: PCI bridge to [bus 1f-1f]
<6>[    2.434627] pci 0000:00:18.4:   bridge window [io  disabled]
<6>[    2.434941] pci 0000:00:18.4:   bridge window [mem 0xfc100000-0xfc1fffff]
<6>[    2.435110] pci 0000:00:18.4:   bridge window [mem 0xe6700000-0xe67fffff 64bit pref]
<6>[    2.435536] pci 0000:00:18.5: PCI bridge to [bus 20-20]
<6>[    2.435540] pci 0000:00:18.5:   bridge window [io  disabled]
<6>[    2.435945] pci 0000:00:18.5:   bridge window [mem 0xfbd00000-0xfbdfffff]
<6>[    2.436120] pci 0000:00:18.5:   bridge window [mem 0xe6300000-0xe63fffff 64bit pref]
<6>[    2.436483] pci 0000:00:18.6: PCI bridge to [bus 21-21]
<6>[    2.436486] pci 0000:00:18.6:   bridge window [io  disabled]
<6>[    2.436735] pci 0000:00:18.6:   bridge window [mem 0xfb900000-0xfb9fffff]
<6>[    2.436948] pci 0000:00:18.6:   bridge window [mem 0xe5f00000-0xe5ffffff 64bit pref]
<6>[    2.437358] pci 0000:00:18.7: PCI bridge to [bus 22-22]
<6>[    2.437361] pci 0000:00:18.7:   bridge window [io  disabled]
<6>[    2.437883] pci 0000:00:18.7:   bridge window [mem 0xfb500000-0xfb5fffff]
<6>[    2.438095] pci 0000:00:18.7:   bridge window [mem 0xe5b00000-0xe5bfffff 64bit pref]
<7>[    2.438895] pci 0000:00:01.0: setting latency timer to 64
<7>[    2.439486] pci 0000:00:15.0: setting latency timer to 64
<7>[    2.440920] pci 0000:00:15.1: setting latency timer to 64
<7>[    2.441457] pci 0000:00:15.2: setting latency timer to 64
<7>[    2.443314] pci 0000:00:15.3: setting latency timer to 64
<7>[    2.443958] pci 0000:00:15.4: setting latency timer to 64
<7>[    2.444453] pci 0000:00:15.5: setting latency timer to 64
<7>[    2.444953] pci 0000:00:15.6: setting latency timer to 64
<7>[    2.445317] pci 0000:00:15.7: setting latency timer to 64
<7>[    2.445680] pci 0000:00:16.0: setting latency timer to 64
<7>[    2.446320] pci 0000:00:16.1: setting latency timer to 64
<7>[    2.446728] pci 0000:00:16.2: setting latency timer to 64
<7>[    2.447146] pci 0000:00:16.3: setting latency timer to 64
<7>[    2.447541] pci 0000:00:16.4: setting latency timer to 64
<7>[    2.448100] pci 0000:00:16.5: setting latency timer to 64
<7>[    2.448612] pci 0000:00:16.6: setting latency timer to 64
<7>[    2.449096] pci 0000:00:16.7: setting latency timer to 64
<7>[    2.449905] pci 0000:00:17.0: setting latency timer to 64
<7>[    2.450304] pci 0000:00:17.1: setting latency timer to 64
<7>[    2.450666] pci 0000:00:17.2: setting latency timer to 64
<7>[    2.451117] pci 0000:00:17.3: setting latency timer to 64
<7>[    2.451518] pci 0000:00:17.4: setting latency timer to 64
<7>[    2.451929] pci 0000:00:17.5: setting latency timer to 64
<7>[    2.452324] pci 0000:00:17.6: setting latency timer to 64
<7>[    2.452685] pci 0000:00:17.7: setting latency timer to 64
<7>[    2.453120] pci 0000:00:18.0: setting latency timer to 64
<7>[    2.453715] pci 0000:00:18.1: setting latency timer to 64
<7>[    2.454091] pci 0000:00:18.2: setting latency timer to 64
<7>[    2.454488] pci 0000:00:18.3: setting latency timer to 64
<7>[    2.454900] pci 0000:00:18.4: setting latency timer to 64
<7>[    2.455394] pci 0000:00:18.5: setting latency timer to 64
<7>[    2.456025] pci 0000:00:18.6: setting latency timer to 64
<7>[    2.456396] pci 0000:00:18.7: setting latency timer to 64
<7>[    2.456457] pci_bus 0000:00: resource 4 [mem 0x000a0000-0x000bffff]
<7>[    2.456459] pci_bus 0000:00: resource 5 [mem 0x000cc000-0x000cffff]
<7>[    2.456460] pci_bus 0000:00: resource 6 [mem 0x000d0000-0x000d3fff]
<7>[    2.456461] pci_bus 0000:00: resource 7 [mem 0x000d4000-0x000d7fff]
<7>[    2.456462] pci_bus 0000:00: resource 8 [mem 0x000d8000-0x000dbfff]
<7>[    2.456464] pci_bus 0000:00: resource 9 [mem 0xc0000000-0xfebfffff]
<7>[    2.456465] pci_bus 0000:00: resource 10 [io  0x0000-0x0cf7]
<7>[    2.456467] pci_bus 0000:00: resource 11 [io  0x0d00-0xfeff]
<7>[    2.456469] pci_bus 0000:02: resource 0 [io  0x2000-0x3fff]
<7>[    2.456470] pci_bus 0000:02: resource 1 [mem 0xfd500000-0xfdffffff]
<7>[    2.456472] pci_bus 0000:02: resource 2 [mem 0xe7b00000-0xe7ffffff 64bit pref]
<7>[    2.456473] pci_bus 0000:02: resource 4 [mem 0x000a0000-0x000bffff]
<7>[    2.456474] pci_bus 0000:02: resource 5 [mem 0x000cc000-0x000cffff]
<7>[    2.456476] pci_bus 0000:02: resource 6 [mem 0x000d0000-0x000d3fff]
<7>[    2.456477] pci_bus 0000:02: resource 7 [mem 0x000d4000-0x000d7fff]
<7>[    2.456478] pci_bus 0000:02: resource 8 [mem 0x000d8000-0x000dbfff]
<7>[    2.456479] pci_bus 0000:02: resource 9 [mem 0xc0000000-0xfebfffff]
<7>[    2.456481] pci_bus 0000:02: resource 10 [io  0x0000-0x0cf7]
<7>[    2.456482] pci_bus 0000:02: resource 11 [io  0x0d00-0xfeff]
<7>[    2.456484] pci_bus 0000:03: resource 0 [io  0x4000-0x4fff]
<7>[    2.456485] pci_bus 0000:03: resource 1 [mem 0xfd400000-0xfd4fffff]
<7>[    2.456486] pci_bus 0000:03: resource 2 [mem 0xe7a00000-0xe7afffff 64bit pref]
<7>[    2.456488] pci_bus 0000:04: resource 0 [io  0x8000-0x8fff]
<7>[    2.456489] pci_bus 0000:04: resource 1 [mem 0xfd000000-0xfd0fffff]
<7>[    2.456490] pci_bus 0000:04: resource 2 [mem 0xe7600000-0xe76fffff 64bit pref]
<7>[    2.456492] pci_bus 0000:05: resource 0 [io  0xc000-0xcfff]
<7>[    2.456493] pci_bus 0000:05: resource 1 [mem 0xfcc00000-0xfccfffff]
<7>[    2.456494] pci_bus 0000:05: resource 2 [mem 0xe7200000-0xe72fffff 64bit pref]
<7>[    2.456496] pci_bus 0000:06: resource 1 [mem 0xfc800000-0xfc8fffff]
<7>[    2.456497] pci_bus 0000:06: resource 2 [mem 0xe6e00000-0xe6efffff 64bit pref]
<7>[    2.456499] pci_bus 0000:07: resource 1 [mem 0xfc400000-0xfc4fffff]
<7>[    2.456500] pci_bus 0000:07: resource 2 [mem 0xe6a00000-0xe6afffff 64bit pref]
<7>[    2.456502] pci_bus 0000:08: resource 1 [mem 0xfc000000-0xfc0fffff]
<7>[    2.456503] pci_bus 0000:08: resource 2 [mem 0xe6600000-0xe66fffff 64bit pref]
<7>[    2.456505] pci_bus 0000:09: resource 1 [mem 0xfbc00000-0xfbcfffff]
<7>[    2.456506] pci_bus 0000:09: resource 2 [mem 0xe6200000-0xe62fffff 64bit pref]
<7>[    2.456508] pci_bus 0000:0a: resource 1 [mem 0xfb800000-0xfb8fffff]
<7>[    2.456509] pci_bus 0000:0a: resource 2 [mem 0xe5e00000-0xe5efffff 64bit pref]
<7>[    2.456511] pci_bus 0000:0b: resource 0 [io  0x5000-0x5fff]
<7>[    2.456512] pci_bus 0000:0b: resource 1 [mem 0xfd300000-0xfd3fffff]
<7>[    2.456513] pci_bus 0000:0b: resource 2 [mem 0xe7900000-0xe79fffff 64bit pref]
<7>[    2.456515] pci_bus 0000:0c: resource 0 [io  0x9000-0x9fff]
<7>[    2.456516] pci_bus 0000:0c: resource 1 [mem 0xfcf00000-0xfcffffff]
<7>[    2.456517] pci_bus 0000:0c: resource 2 [mem 0xe7500000-0xe75fffff 64bit pref]
<7>[    2.456519] pci_bus 0000:0d: resource 0 [io  0xd000-0xdfff]
<7>[    2.456520] pci_bus 0000:0d: resource 1 [mem 0xfcb00000-0xfcbfffff]
<7>[    2.456521] pci_bus 0000:0d: resource 2 [mem 0xe7100000-0xe71fffff 64bit pref]
<7>[    2.456523] pci_bus 0000:0e: resource 1 [mem 0xfc700000-0xfc7fffff]
<7>[    2.456524] pci_bus 0000:0e: resource 2 [mem 0xe6d00000-0xe6dfffff 64bit pref]
<7>[    2.456526] pci_bus 0000:0f: resource 1 [mem 0xfc300000-0xfc3fffff]
<7>[    2.456527] pci_bus 0000:0f: resource 2 [mem 0xe6900000-0xe69fffff 64bit pref]
<7>[    2.456529] pci_bus 0000:10: resource 1 [mem 0xfbf00000-0xfbffffff]
<7>[    2.456530] pci_bus 0000:10: resource 2 [mem 0xe6500000-0xe65fffff 64bit pref]
<7>[    2.456532] pci_bus 0000:11: resource 1 [mem 0xfbb00000-0xfbbfffff]
<7>[    2.456533] pci_bus 0000:11: resource 2 [mem 0xe6100000-0xe61fffff 64bit pref]
<7>[    2.456535] pci_bus 0000:12: resource 1 [mem 0xfb700000-0xfb7fffff]
<7>[    2.456536] pci_bus 0000:12: resource 2 [mem 0xe5d00000-0xe5dfffff 64bit pref]
<7>[    2.456538] pci_bus 0000:13: resource 0 [io  0x6000-0x6fff]
<7>[    2.456539] pci_bus 0000:13: resource 1 [mem 0xfd200000-0xfd2fffff]
<7>[    2.456540] pci_bus 0000:13: resource 2 [mem 0xe7800000-0xe78fffff 64bit pref]
<7>[    2.456542] pci_bus 0000:14: resource 0 [io  0xa000-0xafff]
<7>[    2.456543] pci_bus 0000:14: resource 1 [mem 0xfce00000-0xfcefffff]
<7>[    2.456544] pci_bus 0000:14: resource 2 [mem 0xe7400000-0xe74fffff 64bit pref]
<7>[    2.456546] pci_bus 0000:15: resource 0 [io  0xe000-0xefff]
<7>[    2.456547] pci_bus 0000:15: resource 1 [mem 0xfca00000-0xfcafffff]
<7>[    2.456548] pci_bus 0000:15: resource 2 [mem 0xe7000000-0xe70fffff 64bit pref]
<7>[    2.456550] pci_bus 0000:16: resource 1 [mem 0xfc600000-0xfc6fffff]
<7>[    2.456551] pci_bus 0000:16: resource 2 [mem 0xe6c00000-0xe6cfffff 64bit pref]
<7>[    2.456553] pci_bus 0000:17: resource 1 [mem 0xfc200000-0xfc2fffff]
<7>[    2.456554] pci_bus 0000:17: resource 2 [mem 0xe6800000-0xe68fffff 64bit pref]
<7>[    2.456556] pci_bus 0000:18: resource 1 [mem 0xfbe00000-0xfbefffff]
<7>[    2.456557] pci_bus 0000:18: resource 2 [mem 0xe6400000-0xe64fffff 64bit pref]
<7>[    2.456559] pci_bus 0000:19: resource 1 [mem 0xfba00000-0xfbafffff]
<7>[    2.456560] pci_bus 0000:19: resource 2 [mem 0xe6000000-0xe60fffff 64bit pref]
<7>[    2.456562] pci_bus 0000:1a: resource 1 [mem 0xfb600000-0xfb6fffff]
<7>[    2.456563] pci_bus 0000:1a: resource 2 [mem 0xe5c00000-0xe5cfffff 64bit pref]
<7>[    2.456565] pci_bus 0000:1b: resource 0 [io  0x7000-0x7fff]
<7>[    2.456566] pci_bus 0000:1b: resource 1 [mem 0xfd100000-0xfd1fffff]
<7>[    2.456567] pci_bus 0000:1b: resource 2 [mem 0xe7700000-0xe77fffff 64bit pref]
<7>[    2.456569] pci_bus 0000:1c: resource 0 [io  0xb000-0xbfff]
<7>[    2.456570] pci_bus 0000:1c: resource 1 [mem 0xfcd00000-0xfcdfffff]
<7>[    2.456571] pci_bus 0000:1c: resource 2 [mem 0xe7300000-0xe73fffff 64bit pref]
<7>[    2.456573] pci_bus 0000:1d: resource 1 [mem 0xfc900000-0xfc9fffff]
<7>[    2.456574] pci_bus 0000:1d: resource 2 [mem 0xe6f00000-0xe6ffffff 64bit pref]
<7>[    2.456576] pci_bus 0000:1e: resource 1 [mem 0xfc500000-0xfc5fffff]
<7>[    2.456577] pci_bus 0000:1e: resource 2 [mem 0xe6b00000-0xe6bfffff 64bit pref]
<7>[    2.456579] pci_bus 0000:1f: resource 1 [mem 0xfc100000-0xfc1fffff]
<7>[    2.456580] pci_bus 0000:1f: resource 2 [mem 0xe6700000-0xe67fffff 64bit pref]
<7>[    2.456582] pci_bus 0000:20: resource 1 [mem 0xfbd00000-0xfbdfffff]
<7>[    2.456583] pci_bus 0000:20: resource 2 [mem 0xe6300000-0xe63fffff 64bit pref]
<7>[    2.456584] pci_bus 0000:21: resource 1 [mem 0xfb900000-0xfb9fffff]
<7>[    2.456586] pci_bus 0000:21: resource 2 [mem 0xe5f00000-0xe5ffffff 64bit pref]
<7>[    2.456587] pci_bus 0000:22: resource 1 [mem 0xfb500000-0xfb5fffff]
<7>[    2.456588] pci_bus 0000:22: resource 2 [mem 0xe5b00000-0xe5bfffff 64bit pref]
<6>[    2.463917] NET: Registered protocol family 2
<6>[    2.466298] IP route cache hash table entries: 65536 (order: 7, 524288 bytes)
<6>[    2.484816] TCP established hash table entries: 262144 (order: 10, 4194304 bytes)
<6>[    2.577699] TCP bind hash table entries: 65536 (order: 8, 1048576 bytes)
<6>[    2.601766] TCP: Hash tables configured (established 262144 bind 65536)
<6>[    2.601773] TCP reno registered
<6>[    2.601789] UDP hash table entries: 1024 (order: 3, 32768 bytes)
<6>[    2.602441] UDP-Lite hash table entries: 1024 (order: 3, 32768 bytes)
<6>[    2.608664] NET: Registered protocol family 1
<6>[    2.608681] pci 0000:00:00.0: Limiting direct PCI/PCI transfers
<7>[    2.609131] pci 0000:00:0f.0: Boot video device
<7>[    2.612622] PCI: CLS mismatch (32 != 64), using 64 bytes
<6>[    2.614243] Unpacking initramfs...
<6>[    3.164434] Freeing initrd memory: 7276k freed
<6>[    3.165319] Simple Boot Flag at 0x36 set to 0x80
<6>[    3.170510] audit: initializing netlink socket (disabled)
<5>[    3.170663] type=2000 audit(1487857999.048:1): initialized
<6>[    3.191484] HugeTLB registered 2 MB page size, pre-allocated 0 pages
<5>[    3.204763] VFS: Disk quotas dquot_6.5.2
<4>[    3.205592] Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
<6>[    3.207601] msgmni has been set to 934
<6>[    3.210068] alg: No test for stdrng (krng)
<6>[    3.210812] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 253)
<6>[    3.211706] io scheduler noop registered
<6>[    3.211711] io scheduler deadline registered
<6>[    3.213637] io scheduler cfq registered (default)
<7>[    3.216611] pcieport 0000:00:15.0: setting latency timer to 64
<7>[    3.222492] pcieport 0000:00:15.0: irq 40 for MSI/MSI-X
<7>[    3.226589] pcieport 0000:00:15.1: setting latency timer to 64
<7>[    3.230043] pcieport 0000:00:15.1: irq 41 for MSI/MSI-X
<7>[    3.236286] pcieport 0000:00:15.2: setting latency timer to 64
<7>[    3.240695] pcieport 0000:00:15.2: irq 42 for MSI/MSI-X
<7>[    3.244862] pcieport 0000:00:15.3: setting latency timer to 64
<7>[    3.248287] pcieport 0000:00:15.3: irq 43 for MSI/MSI-X
<7>[    3.253256] pcieport 0000:00:15.4: setting latency timer to 64
<7>[    3.256882] pcieport 0000:00:15.4: irq 44 for MSI/MSI-X
<7>[    3.261891] pcieport 0000:00:15.5: setting latency timer to 64
<7>[    3.266014] pcieport 0000:00:15.5: irq 45 for MSI/MSI-X
<7>[    3.270944] pcieport 0000:00:15.6: setting latency timer to 64
<7>[    3.274586] pcieport 0000:00:15.6: irq 46 for MSI/MSI-X
<7>[    3.279333] pcieport 0000:00:15.7: setting latency timer to 64
<7>[    3.283658] pcieport 0000:00:15.7: irq 47 for MSI/MSI-X
<7>[    3.288194] pcieport 0000:00:16.0: setting latency timer to 64
<7>[    3.292308] pcieport 0000:00:16.0: irq 48 for MSI/MSI-X
<7>[    3.297862] pcieport 0000:00:16.1: setting latency timer to 64
<7>[    3.301873] pcieport 0000:00:16.1: irq 49 for MSI/MSI-X
<7>[    3.306056] pcieport 0000:00:16.2: setting latency timer to 64
<7>[    3.309945] pcieport 0000:00:16.2: irq 50 for MSI/MSI-X
<7>[    3.315284] pcieport 0000:00:16.3: setting latency timer to 64
<7>[    3.319481] pcieport 0000:00:16.3: irq 51 for MSI/MSI-X
<7>[    3.323900] pcieport 0000:00:16.4: setting latency timer to 64
<7>[    3.327458] pcieport 0000:00:16.4: irq 52 for MSI/MSI-X
<7>[    3.332217] pcieport 0000:00:16.5: setting latency timer to 64
<7>[    3.336420] pcieport 0000:00:16.5: irq 53 for MSI/MSI-X
<7>[    3.341880] pcieport 0000:00:16.6: setting latency timer to 64
<7>[    3.346019] pcieport 0000:00:16.6: irq 54 for MSI/MSI-X
<7>[    3.350745] pcieport 0000:00:16.7: setting latency timer to 64
<7>[    3.354659] pcieport 0000:00:16.7: irq 55 for MSI/MSI-X
<7>[    3.361649] pcieport 0000:00:17.0: setting latency timer to 64
<7>[    3.365771] pcieport 0000:00:17.0: irq 56 for MSI/MSI-X
<7>[    3.370605] pcieport 0000:00:17.1: setting latency timer to 64
<7>[    3.376835] pcieport 0000:00:17.1: irq 57 for MSI/MSI-X
<7>[    3.382345] pcieport 0000:00:17.2: setting latency timer to 64
<7>[    3.385861] pcieport 0000:00:17.2: irq 58 for MSI/MSI-X
<7>[    3.390217] pcieport 0000:00:17.3: setting latency timer to 64
<7>[    3.394666] pcieport 0000:00:17.3: irq 59 for MSI/MSI-X
<7>[    3.399684] pcieport 0000:00:17.4: setting latency timer to 64
<7>[    3.403268] pcieport 0000:00:17.4: irq 60 for MSI/MSI-X
<7>[    3.411843] pcieport 0000:00:17.5: setting latency timer to 64
<7>[    3.417481] pcieport 0000:00:17.5: irq 61 for MSI/MSI-X
<7>[    3.423084] pcieport 0000:00:17.6: setting latency timer to 64
<7>[    3.427043] pcieport 0000:00:17.6: irq 62 for MSI/MSI-X
<7>[    3.431339] pcieport 0000:00:17.7: setting latency timer to 64
<7>[    3.434912] pcieport 0000:00:17.7: irq 63 for MSI/MSI-X
<7>[    3.441447] pcieport 0000:00:18.0: setting latency timer to 64
<7>[    3.444856] pcieport 0000:00:18.0: irq 64 for MSI/MSI-X
<7>[    3.448970] pcieport 0000:00:18.1: setting latency timer to 64
<7>[    3.454704] pcieport 0000:00:18.1: irq 65 for MSI/MSI-X
<7>[    3.460153] pcieport 0000:00:18.2: setting latency timer to 64
<7>[    3.463624] pcieport 0000:00:18.2: irq 66 for MSI/MSI-X
<7>[    3.468679] pcieport 0000:00:18.3: setting latency timer to 64
<7>[    3.474148] pcieport 0000:00:18.3: irq 67 for MSI/MSI-X
<7>[    3.479861] pcieport 0000:00:18.4: setting latency timer to 64
<7>[    3.483544] pcieport 0000:00:18.4: irq 68 for MSI/MSI-X
<7>[    3.488459] pcieport 0000:00:18.5: setting latency timer to 64
<7>[    3.492648] pcieport 0000:00:18.5: irq 69 for MSI/MSI-X
<7>[    3.497708] pcieport 0000:00:18.6: setting latency timer to 64
<7>[    3.504365] pcieport 0000:00:18.6: irq 70 for MSI/MSI-X
<7>[    3.508769] pcieport 0000:00:18.7: setting latency timer to 64
<7>[    3.513025] pcieport 0000:00:18.7: irq 71 for MSI/MSI-X
<6>[    3.519380] pcieport 0000:00:15.0: Signaling PME through PCIe PME interrupt
<7>[    3.519553] pcie_pme 0000:00:15.0:pcie01: service driver pcie_pme loaded
<6>[    3.520719] pcieport 0000:00:15.1: Signaling PME through PCIe PME interrupt
<7>[    3.520933] pcie_pme 0000:00:15.1:pcie01: service driver pcie_pme loaded
<6>[    3.521771] pcieport 0000:00:15.2: Signaling PME through PCIe PME interrupt
<7>[    3.521983] pcie_pme 0000:00:15.2:pcie01: service driver pcie_pme loaded
<6>[    3.522941] pcieport 0000:00:15.3: Signaling PME through PCIe PME interrupt
<7>[    3.523103] pcie_pme 0000:00:15.3:pcie01: service driver pcie_pme loaded
<6>[    3.524121] pcieport 0000:00:15.4: Signaling PME through PCIe PME interrupt
<7>[    3.524301] pcie_pme 0000:00:15.4:pcie01: service driver pcie_pme loaded
<6>[    3.525390] pcieport 0000:00:15.5: Signaling PME through PCIe PME interrupt
<7>[    3.525550] pcie_pme 0000:00:15.5:pcie01: service driver pcie_pme loaded
<6>[    3.526381] pcieport 0000:00:15.6: Signaling PME through PCIe PME interrupt
<7>[    3.526538] pcie_pme 0000:00:15.6:pcie01: service driver pcie_pme loaded
<6>[    3.527443] pcieport 0000:00:15.7: Signaling PME through PCIe PME interrupt
<7>[    3.527833] pcie_pme 0000:00:15.7:pcie01: service driver pcie_pme loaded
<6>[    3.528673] pcieport 0000:00:16.0: Signaling PME through PCIe PME interrupt
<7>[    3.529948] pcie_pme 0000:00:16.0:pcie01: service driver pcie_pme loaded
<6>[    3.531309] pcieport 0000:00:16.1: Signaling PME through PCIe PME interrupt
<7>[    3.531544] pcie_pme 0000:00:16.1:pcie01: service driver pcie_pme loaded
<6>[    3.532911] pcieport 0000:00:16.2: Signaling PME through PCIe PME interrupt
<7>[    3.533081] pcie_pme 0000:00:16.2:pcie01: service driver pcie_pme loaded
<6>[    3.534064] pcieport 0000:00:16.3: Signaling PME through PCIe PME interrupt
<7>[    3.534235] pcie_pme 0000:00:16.3:pcie01: service driver pcie_pme loaded
<6>[    3.535157] pcieport 0000:00:16.4: Signaling PME through PCIe PME interrupt
<7>[    3.535330] pcie_pme 0000:00:16.4:pcie01: service driver pcie_pme loaded
<6>[    3.537225] pcieport 0000:00:16.5: Signaling PME through PCIe PME interrupt
<7>[    3.537418] pcie_pme 0000:00:16.5:pcie01: service driver pcie_pme loaded
<6>[    3.538370] pcieport 0000:00:16.6: Signaling PME through PCIe PME interrupt
<7>[    3.538555] pcie_pme 0000:00:16.6:pcie01: service driver pcie_pme loaded
<6>[    3.539439] pcieport 0000:00:16.7: Signaling PME through PCIe PME interrupt
<7>[    3.539905] pcie_pme 0000:00:16.7:pcie01: service driver pcie_pme loaded
<6>[    3.540934] pcieport 0000:00:17.0: Signaling PME through PCIe PME interrupt
<7>[    3.541105] pcie_pme 0000:00:17.0:pcie01: service driver pcie_pme loaded
<6>[    3.542000] pcieport 0000:00:17.1: Signaling PME through PCIe PME interrupt
<7>[    3.542169] pcie_pme 0000:00:17.1:pcie01: service driver pcie_pme loaded
<6>[    3.543158] pcieport 0000:00:17.2: Signaling PME through PCIe PME interrupt
<7>[    3.543317] pcie_pme 0000:00:17.2:pcie01: service driver pcie_pme loaded
<6>[    3.544376] pcieport 0000:00:17.3: Signaling PME through PCIe PME interrupt
<7>[    3.544535] pcie_pme 0000:00:17.3:pcie01: service driver pcie_pme loaded
<6>[    3.545570] pcieport 0000:00:17.4: Signaling PME through PCIe PME interrupt
<7>[    3.545792] pcie_pme 0000:00:17.4:pcie01: service driver pcie_pme loaded
<6>[    3.546677] pcieport 0000:00:17.5: Signaling PME through PCIe PME interrupt
<7>[    3.546935] pcie_pme 0000:00:17.5:pcie01: service driver pcie_pme loaded
<6>[    3.548107] pcieport 0000:00:17.6: Signaling PME through PCIe PME interrupt
<7>[    3.548341] pcie_pme 0000:00:17.6:pcie01: service driver pcie_pme loaded
<6>[    3.550071] pcieport 0000:00:17.7: Signaling PME through PCIe PME interrupt
<7>[    3.550314] pcie_pme 0000:00:17.7:pcie01: service driver pcie_pme loaded
<6>[    3.551450] pcieport 0000:00:18.0: Signaling PME through PCIe PME interrupt
<7>[    3.551937] pcie_pme 0000:00:18.0:pcie01: service driver pcie_pme loaded
<6>[    3.553014] pcieport 0000:00:18.1: Signaling PME through PCIe PME interrupt
<7>[    3.553322] pcie_pme 0000:00:18.1:pcie01: service driver pcie_pme loaded
<6>[    3.554550] pcieport 0000:00:18.2: Signaling PME through PCIe PME interrupt
<7>[    3.554844] pcie_pme 0000:00:18.2:pcie01: service driver pcie_pme loaded
<6>[    3.556146] pcieport 0000:00:18.3: Signaling PME through PCIe PME interrupt
<7>[    3.556399] pcie_pme 0000:00:18.3:pcie01: service driver pcie_pme loaded
<6>[    3.557750] pcieport 0000:00:18.4: Signaling PME through PCIe PME interrupt
<7>[    3.557940] pcie_pme 0000:00:18.4:pcie01: service driver pcie_pme loaded
<6>[    3.559226] pcieport 0000:00:18.5: Signaling PME through PCIe PME interrupt
<7>[    3.559407] pcie_pme 0000:00:18.5:pcie01: service driver pcie_pme loaded
<6>[    3.560549] pcieport 0000:00:18.6: Signaling PME through PCIe PME interrupt
<7>[    3.561204] pcie_pme 0000:00:18.6:pcie01: service driver pcie_pme loaded
<6>[    3.562286] pcieport 0000:00:18.7: Signaling PME through PCIe PME interrupt
<7>[    3.562486] pcie_pme 0000:00:18.7:pcie01: service driver pcie_pme loaded
<6>[    3.562701] vesafb: mode is 1024x768x16, linelength=2048, pages=0
<6>[    3.562703] vesafb: scrolling: redraw
<6>[    3.562705] vesafb: Truecolor: size=0:5:6:5, shift=0:11:5:0
<6>[    3.563145] vesafb: framebuffer at 0xe8000000, mapped to 0xffffc90008a00000, using 3072k, total 32768k
<6>[    3.565310] bootsplash 3.2.0-2010/03/31: looking for picture...
<6>[    3.565312] bootsplash: silentjpeg size 59221 bytes
<6>[    3.610225] bootsplash: ...found (1024x768, 31358 bytes, v3).
<6>[    3.661694] Console: switching to colour frame buffer device 124x44
<6>[    3.710520] fb0: VESA VGA frame buffer device
<6>[    3.710660] Serial: 8250/16550 driver, 8 ports, IRQ sharing disabled
<6>[    3.715028] serial8250: ttyS0 at I/O 0x3f8 (irq = 4) is a 16550A
<6>[    3.720324] serial8250: ttyS1 at I/O 0x2f8 (irq = 3) is a 16550A
<6>[    3.724274] 00:0a: ttyS0 at I/O 0x3f8 (irq = 4) is a 16550A
<6>[    3.727168] 00:0b: ttyS1 at I/O 0x2f8 (irq = 3) is a 16550A
<6>[    3.728175] Non-volatile memory driver v1.3
<6>[    3.728181] Linux agpgart interface v0.103
<6>[    3.728231] Fixed MDIO Bus: probed
<6>[    3.728271] i8042: PNP: PS/2 Controller [PNP0303:KBC,PNP0f13:MOUS] at 0x60,0x64 irq 1,12
<6>[    3.737645] serio: i8042 KBD port at 0x60,0x64 irq 1
<6>[    3.737667] serio: i8042 AUX port at 0x60,0x64 irq 12
<6>[    3.737786] mousedev: PS/2 mouse device common for all mice
<6>[    3.738565] cpuidle: using governor ladder
<6>[    3.738570] cpuidle: using governor menu
<6>[    3.738572] EFI Variables Facility v0.08 2004-May-17
<6>[    3.738705] TCP cubic registered
<5>[    3.738718] Registering the dns_resolver key type
<7>[    3.739535] PM: Checking hibernation image partition /dev/sda1
<6>[    3.742961] input: AT Translated Set 2 keyboard as /devices/platform/i8042/serio0/input/input0
<6>[    3.982591] input: ImPS/2 Generic Wheel Mouse as /devices/platform/i8042/serio1/input/input1
<7>[    3.983179] PM: Hibernation image not present or could not be loaded.
<6>[    3.983194] registered taskstats version 1
<6>[    4.022208]   Magic number: 5:421:888
<6>[    4.024177] Freeing unused kernel memory: 1356k freed
<6>[    4.024323] Write protecting the kernel read-only data: 10240k
<6>[    4.030248] Freeing unused kernel memory: 1720k freed
<6>[    4.033679] Freeing unused kernel memory: 1032k freed
<5>[    4.094696] SCSI subsystem initialized
<6>[    4.099229] Fusion MPT base driver 4.28.00.00suse
<6>[    4.099284] Copyright (c) 1999-2010 LSI Corporation
<6>[    4.100255] Fusion MPT SPI Host driver 4.28.00.00suse
<6>[    4.100515] mptspi 0000:00:10.0: PCI INT A -> GSI 17 (level, low) -> IRQ 17
<6>[    4.100578] mptbase: ioc0: 32 BIT PCI BUS DMA ADDRESSING SUPPORTED, total memory = 1917516 kB
<6>[    4.101452] mptbase: ioc0: Initiating bringup
<6>[    4.603381] ioc0: LSI53C1030 B0: Capabilities={Initiator}
<6>[    5.116415] scsi0 : ioc0: LSI53C1030 B0, FwRev=01032920h, Ports=1, MaxQ=128, IRQ=17
<5>[    5.246292] scsi 0:0:0:0: Direct-Access     VMware,  VMware Virtual S 1.0  PQ: 0 ANSI: 2
<6>[    5.246343] scsi 0:0:0:0: mptscsih: ioc0: qdepth=32, tagged=1, simple=1, ordered=0, scsi_level=3, cmd_que=1
<4>[    5.246375] sdev dma_alignment 511 
<6>[    5.246418] scsi target0:0:0: Beginning Domain Validation
<6>[    5.251873] scsi target0:0:0: Domain Validation skipping write tests
<6>[    5.251929] scsi target0:0:0: Ending Domain Validation
<6>[    5.252237] scsi target0:0:0: FAST-40 WIDE SCSI 80.0 MB/s ST (25 ns, offset 127)
<7>[    5.269416] libata version 3.00 loaded.
<7>[    5.274365] ata_piix 0000:00:07.1: version 2.13
<6>[    5.276279] scsi1 : ata_piix
<6>[    5.276385] scsi2 : ata_piix
<6>[    5.276452] ata1: PATA max UDMA/33 cmd 0x1f0 ctl 0x3f6 bmdma 0x1060 irq 14
<6>[    5.276483] ata2: PATA max UDMA/33 cmd 0x170 ctl 0x376 bmdma 0x1068 irq 15
<6>[    5.489577] ata2.00: ATAPI: VMware Virtual IDE CDROM Drive, 00000001, max UDMA/33
<6>[    5.505766] ata2.00: configured for UDMA/33
<5>[    5.508891] scsi 2:0:0:0: CD-ROM            NECVMWar VMware IDE CDR10 1.00 PQ: 0 ANSI: 5
<6>[    5.526382] alua: device handler registered
<6>[    5.531749] rdac: device handler registered
<6>[    5.537909] emc: device handler registered
<6>[    5.546241] hp_sw: device handler registered
<6>[    5.556576] udev: starting version 147
<5>[    5.654649] sd 0:0:0:0: [sda] 104857600 512-byte logical blocks: (53.6 GB/50.0 GiB)
<5>[    5.654894] sd 0:0:0:0: [sda] Write Protect is off
<7>[    5.654928] sd 0:0:0:0: [sda] Mode Sense: 61 00 00 00
<5>[    5.655189] sd 0:0:0:0: [sda] Cache data unavailable
<3>[    5.655223] sd 0:0:0:0: [sda] Assuming drive cache: write through
<5>[    5.656704] sd 0:0:0:0: [sda] Cache data unavailable
<3>[    5.656743] sd 0:0:0:0: [sda] Assuming drive cache: write through
<6>[    5.679481]  sda: sda1 sda2
<5>[    5.681036] sd 0:0:0:0: [sda] Cache data unavailable
<3>[    5.681074] sd 0:0:0:0: [sda] Assuming drive cache: write through
<5>[    5.681108] sd 0:0:0:0: [sda] Attached SCSI disk
<7>[    5.686710] ACPI: acpi_idle registered with cpuidle
<6>[    5.808427] usbcore: registered new interface driver usbfs
<6>[    5.808483] usbcore: registered new interface driver hub
<6>[    5.834374] usbcore: registered new device driver usb
<6>[    5.909582] ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
<6>[    5.909752] ehci_hcd 0000:02:03.0: PCI INT A -> GSI 17 (level, low) -> IRQ 17
<6>[    5.910016] ehci_hcd 0000:02:03.0: EHCI Host Controller
<6>[    5.910068] ehci_hcd 0000:02:03.0: new USB bus registered, assigned bus number 1
<7>[    5.912130] ehci_hcd 0000:02:03.0: cache line size of 64 is not supported
<6>[    5.912139] ehci_hcd 0000:02:03.0: irq 17, io mem 0xfd5ef000
<6>[    5.924285] ehci_hcd 0000:02:03.0: USB 2.0 started, EHCI 1.00
<6>[    5.924668] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002
<6>[    5.924721] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
<6>[    5.924770] usb usb1: Product: EHCI Host Controller
<6>[    5.924817] usb usb1: Manufacturer: Linux 3.0.13-0.27-default ehci_hcd
<6>[    5.924867] usb usb1: SerialNumber: 0000:02:03.0
<6>[    5.925002] hub 1-0:1.0: USB hub found
<6>[    5.925037] hub 1-0:1.0: 6 ports detected
<6>[    5.938912] uhci_hcd: USB Universal Host Controller Interface driver
<6>[    5.941580] uhci_hcd 0000:02:00.0: PCI INT A -> GSI 18 (level, low) -> IRQ 18
<6>[    5.941982] uhci_hcd 0000:02:00.0: UHCI Host Controller
<6>[    5.942055] uhci_hcd 0000:02:00.0: new USB bus registered, assigned bus number 2
<6>[    5.945487] uhci_hcd 0000:02:00.0: irq 18, io base 0x00002080
<6>[    5.946452] usb usb2: New USB device found, idVendor=1d6b, idProduct=0001
<6>[    5.946486] usb usb2: New USB device strings: Mfr=3, Product=2, SerialNumber=1
<6>[    5.946518] usb usb2: Product: UHCI Host Controller
<6>[    5.946549] usb usb2: Manufacturer: Linux 3.0.13-0.27-default uhci_hcd
<6>[    5.946580] usb usb2: SerialNumber: 0000:02:00.0
<6>[    5.946706] hub 2-0:1.0: USB hub found
<6>[    5.946808] hub 2-0:1.0: 2 ports detected
<7>[    6.241388] PM: Marking nosave pages: 000000000009f000 - 0000000000100000
<7>[    6.241393] PM: Marking nosave pages: 000000007fee0000 - 000000007ff00000
<7>[    6.241394] PM: Basic memory bitmaps created
<7>[    6.249861] PM: Basic memory bitmaps freed
<6>[    6.255279] usb 2-1: new full-speed USB device number 2 using uhci_hcd
<6>[    6.309156] PM: Starting manual resume from disk
<7>[    6.309193] PM: Hibernation image partition 8:1 present
<7>[    6.309194] PM: Looking for hibernation image.
<7>[    6.310025] PM: Image not found (code -22)
<7>[    6.310026] PM: Hibernation image not present or could not be loaded.
<6>[    6.401805] usb 2-1: New USB device found, idVendor=0e0f, idProduct=0003
<6>[    6.401845] usb 2-1: New USB device strings: Mfr=1, Product=2, SerialNumber=0
<6>[    6.401876] usb 2-1: Product: VMware Virtual USB Mouse
<6>[    6.401906] usb 2-1: Manufacturer: VMware
<6>[    6.436893] input: VMware VMware Virtual USB Mouse as /devices/pci0000:00/0000:00:11.0/0000:02:00.0/usb2/2-1/2-1:1.0/input/input2
<6>[    6.437030] generic-usb 0003:0E0F:0003.0001: input,hidraw0: USB HID v1.10 Mouse [VMware VMware Virtual USB Mouse] on usb-0000:02:00.0-1/input0
<6>[    6.442902] input: VMware VMware Virtual USB Mouse as /devices/pci0000:00/0000:00:11.0/0000:02:00.0/usb2/2-1/2-1:1.1/input/input3
<6>[    6.443050] generic-usb 0003:0E0F:0003.0002: input,hidraw1: USB HID v1.10 Mouse [VMware VMware Virtual USB Mouse] on usb-0000:02:00.0-1/input1
<6>[    6.443126] usbcore: registered new interface driver usbhid
<6>[    6.443158] usbhid: USB HID core driver
<6>[    6.527498] usb 2-2: new full-speed USB device number 3 using uhci_hcd
<6>[    6.675405] kjournald starting.  Commit interval 15 seconds
<6>[    6.676475] EXT3-fs (sda2): using internal journal
<6>[    6.676529] EXT3-fs (sda2): mounted filesystem with ordered data mode
<6>[    6.715424] usb 2-2: New USB device found, idVendor=0e0f, idProduct=0002
<6>[    6.715464] usb 2-2: New USB device strings: Mfr=0, Product=1, SerialNumber=0
<6>[    6.715497] usb 2-2: Product: VMware Virtual USB Hub
<6>[    6.723778] hub 2-2:1.0: USB hub found
<6>[    6.726400] hub 2-2:1.0: 7 ports detected
<6>[    7.026896] usb 2-2.1: new full-speed USB device number 4 using uhci_hcd
<6>[    7.144616] usb 2-2.1: New USB device found, idVendor=0e0f, idProduct=0008
<6>[    7.144656] usb 2-2.1: New USB device strings: Mfr=1, Product=2, SerialNumber=3
<6>[    7.144687] usb 2-2.1: Product: Virtual Bluetooth Adapter
<6>[    7.144718] usb 2-2.1: Manufacturer: VMware
<6>[    7.144748] usb 2-2.1: SerialNumber: 000650268328
<6>[    9.072110] udev: starting version 147
<6>[    9.243345] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input4
<6>[    9.243424] ACPI: Power Button [PWRF]
<6>[    9.272297] agpgart-intel 0000:00:00.0: Intel 440BX Chipset
<6>[    9.274233] agpgart-intel 0000:00:00.0: AGP aperture is 256M @ 0x0
<3>[    9.276367] piix4_smbus 0000:00:07.3: Host SMBus controller not enabled!
<6>[    9.282928] pci_hotplug: PCI Hot Plug PCI Core version: 0.5
<4>[    9.292156] ACPI: Deprecated procfs I/F for AC is loaded, please retry with CONFIG_ACPI_PROCFS_POWER cleared
<6>[    9.292604] ACPI: AC Adapter [ACAD] (on-line)
<6>[    9.310676] Fusion MPT misc device (ioctl) driver 4.28.00.00suse
<6>[    9.310762] mptctl: Registered with Fusion MPT base driver
<6>[    9.310796] mptctl: /dev/mptctl @ (major,minor=10,220)
<6>[    9.318156] shpchp: Standard Hot Plug PCI Controller Driver version: 0.4
<6>[    9.507143] Floppy drive(s): fd0 is 1.44M
<6>[    9.543398] rtc_cmos 00:04: rtc core: registered rtc_cmos as rtc0
<6>[    9.544605] rtc0: alarms up to one month, y3k, 114 bytes nvram, hpet irqs
<6>[    9.563854] FDC 0 is a post-1991 82077
<5>[    9.567502] sd 0:0:0:0: Attached scsi generic sg0 type 0
<5>[    9.567591] scsi 2:0:0:0: Attached scsi generic sg1 type 5
<6>[    9.710334] pciehp 0000:00:15.0:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.710852] pciehp 0000:00:15.0:pcie04: service driver pciehp loaded
<6>[    9.711639] pciehp 0000:00:15.1:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.712188] pciehp 0000:00:15.1:pcie04: service driver pciehp loaded
<6>[    9.712957] pciehp 0000:00:15.2:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.713479] pciehp 0000:00:15.2:pcie04: service driver pciehp loaded
<6>[    9.714019] pciehp 0000:00:15.3:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.714489] pciehp 0000:00:15.3:pcie04: service driver pciehp loaded
<6>[    9.715063] pciehp 0000:00:15.4:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.715528] pciehp 0000:00:15.4:pcie04: service driver pciehp loaded
<6>[    9.716182] pciehp 0000:00:15.5:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.717434] pciehp 0000:00:15.5:pcie04: service driver pciehp loaded
<6>[    9.717988] pciehp 0000:00:15.6:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.718480] pciehp 0000:00:15.6:pcie04: service driver pciehp loaded
<6>[    9.719036] pciehp 0000:00:15.7:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.721080] pciehp 0000:00:15.7:pcie04: service driver pciehp loaded
<6>[    9.721596] pciehp 0000:00:16.0:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.722115] pciehp 0000:00:16.0:pcie04: service driver pciehp loaded
<6>[    9.722614] pciehp 0000:00:16.1:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.723109] pciehp 0000:00:16.1:pcie04: service driver pciehp loaded
<6>[    9.723608] pciehp 0000:00:16.2:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.724096] pciehp 0000:00:16.2:pcie04: service driver pciehp loaded
<6>[    9.724595] pciehp 0000:00:16.3:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.725289] pciehp 0000:00:16.3:pcie04: service driver pciehp loaded
<6>[    9.725789] pciehp 0000:00:16.4:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.726304] pciehp 0000:00:16.4:pcie04: service driver pciehp loaded
<6>[    9.726874] pciehp 0000:00:16.5:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.727470] pciehp 0000:00:16.5:pcie04: service driver pciehp loaded
<6>[    9.728106] pciehp 0000:00:16.6:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.729023] pciehp 0000:00:16.6:pcie04: service driver pciehp loaded
<6>[    9.729638] pciehp 0000:00:16.7:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.730255] pciehp 0000:00:16.7:pcie04: service driver pciehp loaded
<6>[    9.731232] pciehp 0000:00:17.0:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.732081] pciehp 0000:00:17.0:pcie04: service driver pciehp loaded
<6>[    9.733061] pciehp 0000:00:17.1:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.733768] pciehp 0000:00:17.1:pcie04: service driver pciehp loaded
<6>[    9.734554] pciehp 0000:00:17.2:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.735138] pciehp 0000:00:17.2:pcie04: service driver pciehp loaded
<6>[    9.736181] pciehp 0000:00:17.3:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.738164] pciehp 0000:00:17.3:pcie04: service driver pciehp loaded
<6>[    9.739243] pciehp 0000:00:17.4:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.739886] pciehp 0000:00:17.4:pcie04: service driver pciehp loaded
<6>[    9.740443] pciehp 0000:00:17.5:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.741199] pciehp 0000:00:17.5:pcie04: service driver pciehp loaded
<6>[    9.741787] pciehp 0000:00:17.6:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.742288] pciehp 0000:00:17.6:pcie04: service driver pciehp loaded
<6>[    9.742826] pciehp 0000:00:17.7:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.743286] pciehp 0000:00:17.7:pcie04: service driver pciehp loaded
<6>[    9.743829] pciehp 0000:00:18.0:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.744288] pciehp 0000:00:18.0:pcie04: service driver pciehp loaded
<6>[    9.745018] pciehp 0000:00:18.1:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.745480] pciehp 0000:00:18.1:pcie04: service driver pciehp loaded
<6>[    9.746050] pciehp 0000:00:18.2:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.746509] pciehp 0000:00:18.2:pcie04: service driver pciehp loaded
<6>[    9.747040] pciehp 0000:00:18.3:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.747498] pciehp 0000:00:18.3:pcie04: service driver pciehp loaded
<6>[    9.748018] pciehp 0000:00:18.4:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.748478] pciehp 0000:00:18.4:pcie04: service driver pciehp loaded
<6>[    9.749224] pciehp 0000:00:18.5:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.749684] pciehp 0000:00:18.5:pcie04: service driver pciehp loaded
<6>[    9.750216] pciehp 0000:00:18.6:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.750781] pciehp 0000:00:18.6:pcie04: service driver pciehp loaded
<6>[    9.751389] pciehp 0000:00:18.7:pcie04: HPC vendor_id 15ad device_id 7a0 ss_vid 15ad ss_did 7a0
<7>[    9.752159] pciehp 0000:00:18.7:pcie04: service driver pciehp loaded
<6>[    9.752174] pciehp: PCI Express Hot Plug Controller Driver version: 0.4
<4>[    9.773394] sr0: scsi3-mmc drive: 1x/1x writer dvd-ram cd/rw xa/form2 cdda tray
<6>[    9.773448] cdrom: Uniform CD-ROM driver Revision: 3.20
<7>[    9.773610] sr 2:0:0:0: Attached scsi CD-ROM sr0
<6>[    9.804304] parport_pc 00:09: reported by Plug and Play ACPI
<6>[    9.807681] parport0: PC-style at 0x378, irq 7 [PCSPP,TRISTATE]
<6>[    9.812055] input: PC Speaker as /devices/platform/pcspkr/input/input5
<6>[   10.091340] e1000: Intel(R) PRO/1000 Network Driver - version 7.3.21-k8-NAPI
<6>[   10.091393] e1000: Copyright (c) 1999-2006 Intel Corporation.
<6>[   10.091754] e1000 0000:02:01.0: PCI INT A -> GSI 19 (level, low) -> IRQ 19
<7>[   10.092392] e1000 0000:02:01.0: setting latency timer to 64
<6>[   10.116331] ppdev: user-space parallel port driver
<6>[   11.009499] e1000 0000:02:01.0: eth0: (PCI:66MHz:32-bit) 00:0c:29:f5:45:26
<6>[   11.009537] e1000 0000:02:01.0: eth0: Intel(R) PRO/1000 Network Connection
<6>[   11.112860] NET: Registered protocol family 10
<6>[   11.238102] Bluetooth: Core ver 2.16
<6>[   11.238153] NET: Registered protocol family 31
<6>[   11.238179] Bluetooth: HCI device and connection manager initialized
<6>[   11.238205] Bluetooth: HCI socket layer initialized
<6>[   11.238229] Bluetooth: L2CAP socket layer initialized
<6>[   11.253278] Bluetooth: SCO socket layer initialized
<6>[   11.360358] Bluetooth: Generic Bluetooth USB driver ver 0.6
<6>[   11.367543] usbcore: registered new interface driver btusb
<6>[   11.403988] ENS1371 0000:02:02.0: PCI INT A -> GSI 16 (level, low) -> IRQ 16
<6>[   11.636860] udev: renamed network interface eth0 to eth1
<6>[   12.808513] Adding 2103292k swap on /dev/sda1.  Priority:-1 extents:1 across:2103292k 
<6>[   14.140998] device-mapper: uevent: version 1.0.3
<6>[   14.141117] device-mapper: ioctl: 4.20.0-ioctl (2011-02-02) initialised: dm-devel@redhat.com
<6>[   14.652260] loop: module loaded
<6>[   16.901702] fuse init (API version 7.16)
Kernel logging (ksyslog) stopped.
Kernel log daemon terminating.

Boot logging started on /dev/tty1(/dev/console) at Thu Feb 23 08:53:22 2017

Trying manual resume from /dev/sda1
Invoking userspace resume from /dev/sda1
resume: libgcrypt version: 1.5.0
Trying manual resume from /dev/sda1
Invoking in-kernel resume from /dev/sda1
Waiting for device /dev/sda2 to appear:  ok
fsck from util-linux 2.19.1
[/sbin/fsck.ext3 (1) -- /] fsck.ext3 -a -C0 /dev/sda2 
/dev/sda2: clean, 193013/3145728 files, 1206032/12581120 blocks
fsck succeeded. Mounting root device read-write.
Mounting root /dev/sda2
mount -o rw,acl,user_xattr -t ext3 /dev/sda2 /root
