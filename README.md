# Trading_fixed


addlabel is n/a
addlabel(SHOWTAS, if (!IsNaN(rotaciones)) then "CMP " + rotaciones else "",
if (rotaciones >= 2.00) then Color.green
else if (rotaciones <= -2.00) then Color.RED
else if (rotaciones > rotaciones[1] and rotaciones > 0.00 and rotaciones < 2.00 and rotaciones > 0.00) then Color.dark_green
else if (rotaciones < rotaciones[1] and rotaciones < 0.00 and rotaciones > -2.00 and rotaciones < 0.00) then Color.dark_red
else if (rotaciones >= rotaciones[1] and rotaciones > 0.00) then Color.GRAY else Color.dark_gray);