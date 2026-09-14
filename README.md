#include <stdio.h>

int main()
{
    double time, speed;
    double distance, meters, centimeters, millimeters;
    printf("Enter time in hours (h): ");
    scanf("%lf", &time);
    printf("Enter speed in kilometers per hour (km/h): ");
    scanf("%lf", &speed);
    distance = speed * time;
    meters = distance * 1000;
    centimeters = distance * 100000;
    millimeters = distance * 1000000;
    printf("\nDistance in Kilometers: %.2lf km\n", distance);
    printf("Distance in Meters: %.2lf m\n", meters);
    printf("Distance in Centimeters: %.2lf cm\n", centimeters);
    printf("Distance in Millimeters: %.2lf mm\n", millimeters);
    return 0;
}
