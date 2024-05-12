# PCB-Design-Application
# Aim
To design a simple Led based circuit

# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory

Theory:

LED (Light Emitting Diode): An LED is a semiconductor device that emits light when current flows through it. It has two terminals: Anode (+) and Cathode (-).
Resistor: A resistor limits the flow of electric current in a circuit. It's essential in LED circuits to prevent too much current from damaging the LED.
Two-Pin Connector: This is just a simple electrical connector with two pins for making electrical connections.

### Working 

Connecting the LED: Connect one leg of the LED (the longer one, the Anode, which is the positive terminal) to one pin of the connector.
Connecting the Resistor: Connect one leg of the resistor to the other pin of the connector.
Completing the Circuit: Connect the free leg of the resistor to the free leg of the LED (the shorter one, the Cathode, which is the negative terminal).
Now, when you connect this circuit to a power source such as a battery, here's what happens:

Current Flow: Electric current flows from the positive terminal of the battery, through the LED (which lights up), then through the resistor, and finally back to the negative terminal of the battery.
Resistor's Role: The resistor limits the current flowing through the LED. Without it, too much current would flow through the LED, potentially damaging it. The value of the resistor is chosen based on the LED's specifications and the power supply voltage.
LED Illumination: As current passes through the LED, it emits light. The intensity of the light depends on the current flowing through the LED, which is regulated by the resistor.

# Circuit Diagram
![image](https://github.com/S-Priyadharshan/PCB-Design-Application/assets/145854138/6a3bc290-117f-467b-8525-93a356fbd71e)

# Output



### Schematic diagram

![image](https://github.com/S-Priyadharshan/PCB-Design-Application/assets/145854138/b63d7a6b-4cdd-41fe-80bf-9eb8dfb43353)


### Layout diagram
![image](https://github.com/S-Priyadharshan/PCB-Design-Application/assets/145854138/f65eef37-504e-4dcc-9aa5-0f064ae5142d)

# Result

Thus , the Led circuit's schmetic diagram and layout diagram is designed successfully by using the eagle software.
