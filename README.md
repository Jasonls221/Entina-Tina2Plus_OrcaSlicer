This will make pretty good prints but you need to run this to get the printer to accept the gcode

sed -i '1i ;MachineType: TINA2Plus\n;FilamentType:PLA' file.gcode
