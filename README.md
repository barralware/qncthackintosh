# QNCT Hackintosh

Meu canal:
https://www.youtube.com/channel/UCYE9gAddfibMTIrRTinAEvg

Testado no:
Catalina 10.15.7, Big Sur

Essa é minha atual EFI, mas com alguns problemas:

Horário do Windows fica bugado, não resolvido.
Pode dar uma tela com tom roseada, já que é uma placa-mãe diferente.
Audio Frontal não funciona.
FaceTime e iMessage não configurado.

Config:
i7 QNCT (i7 8850H)
8GB DDR4 2400MHZ Asgard Loki (Chip Nanya) Single Channel
Biostar H170GT3 (2 Portas HDMI e 1 DVI)
Intel UHD Graphics 630
Placa de Rede Intel i219V
Placa de Áudio ALC887
Bootloader Opencore

Kexts:

AppleALC
Lilu
IntelMausi
USBInjectAll
VirtualSMC
WhateverGreen
XHCI-unsupported

Kext de placa de rede:
IntelMausiEthernet.kext – Enables ethernet for motherboards using an Intel Ethernet Chipset.
RealtekRTL8111.kext – Enables ethernet for motherboards using a Realtek Ethernet Chipset
AtherosE2200Ethernet.kext – Enables ethernet for motherboards using Killer Lan Ethernet Chipset
https://hackintosher.com/downloads/kexts/

[ENGLISH]
This is my current EFI, but with some problems:

Windows time gets buggy, unresolved. You can give a screen with a pinkish tone, since it is a different motherboard. Front Audio does not work. FaceTime and iMessage not configured.

Config:
i7 QNCT (i7 8850H)
8GB DDR4 2400MHZ Asgard Loki (Chip Nanya) Single Channel Biostar H170GT3 (2 HDMI Ports and 1 DVI)
Intel UHD Graphics 630
Intel i219V Network Card
ALC887 Audio Card
Opencore Bootloader

Kexts:

AppleALC
CtlnaACHIPort
IntelMausi
Lilu
RestrictEvents
USBPorts
VirtualSMC
WhateverGreen
