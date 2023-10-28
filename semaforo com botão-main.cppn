#define BOTAO 12
#define CARRO_VERMELHO 7
#define CARRO_AMARELO  6
#define CARRO_VERDE    5

#define PEDESTRE_VERMELHO A4
#define PEDESTRE_VERDE A5

void setup ()
{
  pinMode(BOTAO, INPUT_PULLUP);
  pinMode (CARRO_VERMELHO, OUTPUT);
  pinMode (CARRO_AMARELO, OUTPUT);
  pinMode (CARRO_VERDE, OUTPUT);
  
  pinMode(PEDESTRE_VERMELHO, OUTPUT);
  pinMode(PEDESTRE_VERDE, OUTPUT);
  
  digitalWrite (CARRO_VERMELHO, 0);
  digitalWrite (CARRO_AMARELO, 0);
  digitalWrite (CARRO_VERDE, 1);
  
  digitalWrite (PEDESTRE_VERMELHO,1);
  digitalWrite (PEDESTRE_VERDE,0);
}
void loop ()
{ 
  if (digitalRead(BOTAO) == 0 )
  {
  digitalWrite (CARRO_VERMELHO, 0);
  digitalWrite (CARRO_AMARELO, 1);
  digitalWrite (CARRO_VERDE, 0);
  
  digitalWrite (PEDESTRE_VERMELHO,1);
  digitalWrite (PEDESTRE_VERDE,0);
  
  delay (2000);
  
  digitalWrite (CARRO_VERMELHO, 1);
  digitalWrite (CARRO_AMARELO, 0);
  digitalWrite (CARRO_VERDE, 0);
  
  digitalWrite (PEDESTRE_VERMELHO,0);
  digitalWrite (PEDESTRE_VERDE,1);
    
  delay (5000);
    
  digitalWrite (CARRO_VERMELHO, 0);
  digitalWrite (CARRO_AMARELO, 0);
  digitalWrite (CARRO_VERDE, 1);
  
  digitalWrite (PEDESTRE_VERMELHO,1);
  digitalWrite (PEDESTRE_VERDE,0);
    
  delay (10000);
}
  delay (100);
}
