# ESP 32 Ardiuno

板载LED是GPIO2管脚

````
```cpp
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILDIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILDIN, LOW);
  delay(1000);
}

```
````



