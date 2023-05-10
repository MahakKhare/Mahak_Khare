#include <core_script_bridge/navigation_bridge.h>
#include <iostrem>
#include <math.h>

Navigation nav;
int main(int argc, char *argv[])
{
    nav.takeoff(10,0);
    nav.position_set(10(1/2),10(sqrt(3)/2),0);
    nav.position_set(10(1/2),-10(sqrt(3)/2),0);
    nav.position_set(-10,0,0);
    nav.land()
}