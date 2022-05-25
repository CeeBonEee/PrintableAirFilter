$fn=100;

difference(){
  cylinder(d=184.8,h=40);    
  translate([0,0,31]) cylinder(d=182.4,h=40);
  translate([0,0,1]) cylinder(d=179.56,h=40);

  for(x = [0 : 90 : 270]){
    rotate([0,0,x]) translate([-17/2,85,5.5]) cube([17,20,12.5]);}

  translate([60,-60,10]) rotate([90,0,45]) cylinder(d=4,h=20);}

for(x = [0 : 90 : 270]){
  rotate([0,0,x]){
    difference(){
      intersection(){
        cylinder(d=184.8,h=40);
        translate([-20/2,84,0]) cube([20,20,19.5]);}
        translate([-17/2,80,5.5]) cube([17,20,12.5]);}
        translate([-37,75,1]) cylinder(d1=5,d2=4,h=20);
        translate([6,38,1]) cylinder(d1=5,d2=4,h=20);}}
