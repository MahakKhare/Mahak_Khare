#include <core_script_bridge/navigation_bridge.h>
#include <iostrem>

Navigation nav;
int main(int argc, char *argv[])
{
    nav.takeoff(5,0);
    nav.position_set(6.5,0,0);
    nav.position_set(0,6.5,0);
    nav.position_set(-6.5,0,0);
    nav.position_set(0,-6.5,0);
    nav.land()
}