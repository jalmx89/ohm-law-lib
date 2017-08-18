# Library  *ohm's law*

Library basic for calculate ohm's law in JAVA


## how toi use?

### For calculate Current

```java

double voltage = 10; //10V
double resistance = 100; // 100 ohms


double currentValue =  Current.calculateCurrent(volage, resistance);

System.out.println("Value current " + currentValue);


```

### For calculate Voltage

```java

double current = 1; //1 Amp
double resistance = 100; // 100 ohms


double voltagetValue =  Voltage.calculateVoltage(current, resistance);

System.out.println("Value voltage " + currentValue);


```

### For calculate Resistance

```java

double voltage = 10; //10V
double current = 0.01; // 10 mAmp


double currentValue =  Resistance.calculateResistance(volage, current);

System.out.println("Value current " + currentValue);


```
## How to install

Download the jar and add your project [here](https://github.com/jalmx89/ohm-law/tree/master/out/artifacts/ohm_law)