<h1 align="left">
  <br>
  <img src="./img/hei-en.png" alt="HEI-Vs Logo" width="350">
  <br>
  HEI-Vs Engineering School - Industrial Automation Base
  <br>
</h1>

Cours AutB

# CtrlX PLc Trace

If a OPC UA Tool can be usefull to display the general form of a signal, it is not accurate and/or quick enough to display a signal generated at 10 [ms] or less.

A trace tool is a little bit different. It store a signal in the memory of the PLC, then you can load the trace immediately or latter.

Here the different steps to trace a signal, for example, the sin of LAB 01.

<figure>
    <img src="./img/TraceStep_1.png"
         alt="Lost image TraceStep_1.png">
    <figcaption>Add a trace object in the PLC with name BaseInterfaceUa</figcaption>
</figure>

<figure>
    <img src="./img/TraceStep_2.png"
         alt="Lost image TraceStep_2.png">
    <figcaption>Give a name to the trace and select a task to record it</figcaption>
</figure>

> The task should be ideally the task where your program is working, it is more easy to interprete.

<figure>
    <img src="./img/TraceStep_3.png"
         alt="Lost image TraceStep_3.png">
    <figcaption>Add the variable you want to trace...</figcaption>
</figure>

<figure>
    <img src="./img/TraceStep_4.png"
         alt="Lost image TraceStep_4.png">
    <figcaption>Scroll the PLC_PRG to find your variables</figcaption>
</figure>

<figure>
    <img src="./img/TraceStep_5.png"
         alt="Lost image TraceStep_5.png">
    <figcaption>Download the trace</figcaption>
</figure>

> If you trace the sin signal of LAB 01, you can check the frequency, the amplitude and the sample time of the signal.

<figure>
    <img src="./img/TraceStep_6.png"
         alt="Lost image TraceStep_5.png">
    <figcaption>Interpret the result and check your algorithm!</figcaption>
</figure>