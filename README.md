- 👋 Hi, I’m @ramukdhana
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ramukdhana/ramukdhana is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->  
int signal1[] = {7,6,5},signal2[] = {4,3,2},signal3[] = {13, 12, 11},signal4[] = {10, 9, 8}; int redDelay = 1000;
int amberDelay = 1000; void setup()
{
for (int i = 0; i < 3; i++)
{
pinMode(signal2[i], OUTPUT); pinMode(signal3[i], OUTPUT); pinMode(signal4[i], OUTPUT);
}
}
void loop()
{

digitalWrite(signal1[2], HIGH); digitalWrite(signal1[0], LOW); digitalWrite(signal2[0], HIGH); digitalWrite(signal3[0], HIGH); digitalWrite(signal4[0], HIGH); delay(redDelay);

digitalWrite(signal1[1], HIGH); digitalWrite(signal1[2], LOW); delay(amberDelay); digitalWrite(signal1[1], LOW);

digitalWrite(signal1[0], HIGH); digitalWrite(signal2[2], HIGH);
digitalWrite(signal2[0], LOW); digitalWrite(signal3[0], HIGH); digitalWrite(signal4[0], HIGH); delay(redDelay);

digitalWrite(signal2[1], HIGH); digitalWrite(signal2[2], LOW); delay(amberDelay); digitalWrite(signal2[1], LOW); digitalWrite(signal1[0], HIGH); digitalWrite(signal2[0], HIGH); digitalWrite(signal3[2], HIGH); digitalWrite(signal3[0], LOW); digitalWrite(signal4[0], HIGH); delay(redDelay); digitalWrite(signal4[1], HIGH); digitalWrite(signal4[2], LOW); digitalWrite(signal3[1], HIGH); digitalWrite(signal3[2], LOW); delay(amberDelay); digitalWrite(signal3[1], LOW); digitalWrite(signal1[0], HIGH); digitalWrite(signal2[0], HIGH); digitalWrite(signal3[0], HIGH); digitalWrite(signal4[2], HIGH); digitalWrite(signal4[0], LOW); delay(redDelay); delay(amberDelay); digitalWrite(signal4[1], LOW);
}


