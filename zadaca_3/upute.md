preuzeti zip
unzipati zip

1. promjena imena windowa di se prikazuje kornjaca
cd ~/zadaca_ws/src/ros_tutorials/turtlesim/src
code turtle_frame.cpp
  -> na 52. liniji umjesto "Ime Prezime" napisite svoje ime i prezime

2. otvoriti dva terminala
cd ~/zadaca_ws (oba terminala neka budu u ovom direktoriju)
colcon build (trebali bi se buildati turtlesim i turtle_motion paketi)
source install/setup.bash

3. pokretanje (ovo snimate za zadacu)
  -> prvi terminal
   ros2 run turtlesim turtlesim_node
     -> pokretanjem ovoga trebao bi se otvoriti prozor s kornjacom gdje na vrhu pise "Zadaca 3 - {vase ime i prezime}"
  -> drugi terminal
   ros2 run turtle_motion grid_scan
     -> pokretanjem ovoga koranjaca bi trebala krenuti raditi ocekivane kretnje

