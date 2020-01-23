const int CNY = A0;
int color = 0;

void setup() {
pinMode(CNY, INPUT);
Serial.begin(9600);
}

void loop() {
color = analogRead(CNY);
Serial.println(color);
delay(500);
}
