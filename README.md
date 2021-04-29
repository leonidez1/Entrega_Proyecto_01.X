Entrega_Proyecto_01.X

#define F_CPU 1000000UL // 1MHz

#include <xc.h>

#include<util/delay.h>

int main(void) {
    
    DDRB=0xFF; //Define D como salida// FF todos salida //01-0 salida los demas entradas  
    
    PORTB=0x08;
    while(1)
    {
      
    }
}
