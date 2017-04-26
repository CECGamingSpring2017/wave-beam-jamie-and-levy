# Wave-Beam
Base code for wave beam using Allegro
Original

beam_x = ship_x + t * 2 + 16;
beam_y = ship_y + 10 * sin(0.5*t) + 16;



Simple wave beam

1
beam_x = ship_x + t * 2 + 16;
beam_y = ship_y + 200 * sin(0.5*t) + 16;



More spaced out wave beam

2
beam_x = ship_x + t * 2 + 16;
beam_y = ship_y + 20 * sin(0.5*t) + 16;



More scrunched up wave beam

3
beam_x = ship_x + t * 2 + 16;
beam_y = ship_y + 20 * sin(0.5*t) + 16;

beam2_x = ship_x + t * 2 + 16;
beam2_y = ship_y + 200 * sin(.5 * t) + 16;



2 wave beams
Green is more spaced out
Blue is more scrunched up

