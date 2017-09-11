    boolean state = false;
    boolean buttonup = true;
void setup() {
  pinMode (13, OUTPUT);
  digitalWrite(13, LOW);
  pinMode(7, INPUT);
  digitalWrite(7, HIGH);
}
void loop() {
  if(digitalWrite(7) != HIGH && buttonup == true) {
  state = !state;
  digitalWrite(13, stste);
  buttonup = false;
}
else if(gigitalRead(7) == HIGH && buttonup != true) {
buttonup = true;
}
delay(10)
}
