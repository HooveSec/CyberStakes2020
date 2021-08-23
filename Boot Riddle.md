# Boot Riddle
# Points: 100
# This floppy disk image boots, but instead of a flag we see some silly riddle...
### [Solution]
    qemu-system-i386 floppy.img -monitor stdio
    When the screen pops up it says "Your flag awaits at 0x7DC0"
    We will then use qemu studio to actively look at memory starting at that location
    xp/80x 0x7DC0
    This gives us the hex value's of 0x7b494341 0x4c414552 0x65646f6d
    when converted from hex to ascii the following is left "{ICALAERedom"
    I am not sure the most correct way to answer the question but I knew the format of the flags was ACI{flag}
    I put the ACI{} and figured the rest of the letters could have spelled something, and the first thing that came to mind was
    Flag: ACI{REALmode} 
