# DCIT104-Assignment-2
int sum = 0;
int tally = 0;
void setup() { 
  Serial.begin(9600);
  for (int a = 1; a <= 10000; a++)  { 
    if (a % 2 == 0)  { 
      sum = sum + a;
      tally = tally + 1;
    } 
  } 
     Serial.print("sum =  "); 
     Serial.println(sum); 
     Serial.print("average =  "); 
     Serial.println(sum / tally); 
} 
void loop() { 
} 
