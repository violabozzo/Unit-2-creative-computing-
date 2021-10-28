# Unit 2 Creative Computing
<h2>A guide through creative computing by a beginner for a beginner </h2>
<p style="text-align: center;">I am a student of graphic communication design at Central Saint Martins. I do not have much knowledge when it comes to creative computing, electronics and coding. This Unit I started is a chance for me to learn what it means, new skills and ultimatley share it with others. I am planning on writing things in a way that myself and others as well that do not have much knowledge about this topic are able to understand it. </p>
<p style="text-align: center;">I decided to pursue this project because...</p>
<strong>What is Physical Computing?</strong>
<p style="text-align: center;"> Physical computing are interactive systems such as hardware, software and materials which combined together are able to sense and respond to the world around them. It collects information about the environment and the real world and acts back by making a decision. Computers are literally everywhere. It allows you to see to see how physical devices can be monitored and controlled by a microprocessor. Creating or using devices that that interact with the world around them. It senses the information, reflects about it and then acts. An example is a self driving car. It uses sensors, analyzes data and acts.Through physical computing, you can develop digital solutions that directly impact the real world based on real-world needs. </p>
<strong>What is Arduino? </strong>
<p style="text-align: center;"> Arduino is a programmable device that can be used to allow our code to interact with the world around us. It is made of multiple components and sesnors. It senses the world around it, and based on its programming it reacts accordingly. Temperature sensor is an example. It measures the temperature of the room. If for example it finds that the temperatuire is above 19 degress celcius, it applies this value to the program that is coded with. If it sees that the temperature is less than 20, a light LED turns on. If not it turns off. You have to communicate wtih your device and programm how it should sense, what it should think and how it should react. </p>
<strong>How does Arduino work? </strong>
<p style="text-align: center;">Let's have a look at what Arduino actually is and how it works. I'll then demostrate defferent examples of what you can do with it as a begginer.</p>
<p style="text-align: center;">The Arduino kit offers different components to create your circuit. There is the Arduino software which makes it easy to write code and upload it to the board. Inside the kit you find:</p>
<ul><p>1. Arduino Uno, which is the most important part of the kit. </p>
<ul><p>2.The Breadboard, is the tool to experiment with circuits and you can make quick electrical connections. Components are plugged into the holes.</p> 
<ul><p>3.LEDs come in different colours. It has a longer and a shorter leg. Usually the longer is positive while the shorter leg is negative.</p>
<ul><p>4.The USB Cable, connects to your Arduino as well to your computer. It provides power to the unit and the cable transmits the data from the computer's software to the Arduino.</p>
</ul><p>5.The resistors, can look different depenidng on the kit you have. They give and limit the flow of current to other components.</p>
</ul><p>6.The Pushbuttons, are buttons that when pressed they can interupt or make the flow of electricty go. When the button is pushed all the four legs are going to be connected.</p>
</ul><p>7.The Jumper Wires, are for making connections on the breadboard, as well to connect breadboard and Arduino itself. They come in different colors which does not change anything, it is simply to organize them better when together.</p>
<nav> Before jumping into realizing an actual circut with the components, I am going to explain further what the breadboard is and how it works to better understand the process.<br/>
<br/><div>The image below was taken from the website https://toptechboy.com/tag/pc-board/ </div> <br/>
<img width="469" alt="Screenshot 2021-10-28 at 11 11 37" src="https://user-images.githubusercontent.com/93208364/139285226-1689933d-2641-47c4-bf27-eb7c1ef90f59.png"><br/>
<p style="text-align: center;">In order to build a circuit, you have to connect circuit elements together. The schematic above is going to be built in the real world. The holes along the columns are connected together. If you bring a leg of the LED and the resistor, they will then be connected together. Except across the dividing layers between the holes. The positive and negative rows are not connected together, they are connected on their own row only. You have to put elements in the same column, not row, to make them connected. </p>
<span style="text-decoration: underline;">Now I will show through images one of the process to turn on through the circuit the LED light on.</span> <br/>
<img width="366" alt="Screenshot 2021-10-27 at 23 27 22" src="https://user-images.githubusercontent.com/93208364/139288696-483d936a-0706-47fa-94e2-c6177fc320b5.png">
<p style="text-align: center;">Take an Arduino Uno R3 and a small Breadboard.</p>
<img width="389" alt="Screenshot 2021-10-27 at 23 37 47" src="https://user-images.githubusercontent.com/93208364/139288829-4ed65fdd-7c8e-41a5-866d-b4d3d7583385.png">
<p style="text-align: center;">You need now to connect a jumper wire to the board. You connect from the SV to the first positive hole of the breadboard. This will give this entire vertical line power. </p>
<img width="385" alt="Screenshot 2021-10-27 at 23 46 42" src="https://user-images.githubusercontent.com/93208364/139288981-1f878a6e-4318-4ba2-9b10-9db1da893f8b.png"> 
  <p style="text-align: center;">Now you position the Pushbutton more or less where it is placed in the image above. Make sure to push well the button down so it clicks.</p>
  <img width="378" alt="Screenshot 2021-10-27 at 23 48 49" src="https://user-images.githubusercontent.com/93208364/139289084-8cb7df99-8fde-4460-86c0-2985144615b2.png">
  <p style="text-align: center;">You now place the resistor on the breadboard. To do so make sure to bend the legs of it. You will place one of the legs in the hole next to the Pushbutton's top left leg. You will place the other leg on the other column, on the negative side and either one up or down hole from the other leg.</p>
<img width="382" alt="Screenshot 2021-10-27 at 23 53 06" src="https://user-images.githubusercontent.com/93208364/139289195-3796b478-ef84-4b97-b4d9-6b14ab915bcb.png">
 <p style="text-align: center;">You will place the LED light on the same vertical side of the Pushbutton's legs. The long leg needs to go to the positive voltage. </p>
  <img width="382" alt="Screenshot 2021-10-27 at 23 56 31" src="https://user-images.githubusercontent.com/93208364/139289349-d5c91244-20b1-481d-add6-687ebcacc3c9.png">
<p style="text-align: center;">You will place a new jumper wire. One will fill the hole which is on the same horizontal line of the LED light and the one right next to it. The other will be the hole on the positive, same horizontal line.</p>
<img width="382" alt="Screenshot 2021-10-28 at 00 00 38" src="https://user-images.githubusercontent.com/93208364/139289437-debb6e03-7aab-47e0-8b49-6e4e12c241e7.png"> 
  <p style="text-align: center;">You will put in a new jumper wire. One will fill the hole in front of the LED light on the vertical line compared to the Pushbutton. The other will be connected on the horizontal line of the Pushbutton bottom left leg, right next to it. </p>
  <img width="364" alt="Screenshot 2021-10-28 at 00 06 52" src="https://user-images.githubusercontent.com/93208364/139289551-14a03a59-4221-4049-bdee-0c3b41b2708c.png">
  <p style="text-align: center;">You will connect it with a USB cable that is connected on the other hand to the computer. You can now press the button and the LED light will turn on. </p>
 <h3>I want to write some personal feesback about the journey it took me to understand how this initial process works.</h3>
  <em>At first it was really hard for me to even simply conceptualizing what all of these informations meant to me. I had initially no idea what physical computing was and honestly it sounded very scary. I am still very afraid of how this entire world works as the way of thinking might appear so different from my personal perspective. I was very frustrated at the beggining when I was trying to build the circuit as it was not working. After litterally ten different tries, I was able to make the LED light work and it was so satisfying! It was almost magical and just very rewarding. I suggest following very well another person's tutorial and if it does not work just carefully move around the components, until you make it work. I was then motivated to try other circuits and I am going to show a couple more I tried.</em>
<h4>Second Circuit Example</h4>
<p style="text-align: center;">For this next part you need to download Arduino's software. The one I downloaded is Arduino 1. 8. 9. This will open the Arduino program. Every Arduino program has a "void setup" and a "void loop". You need to go to "Tools", then click "Port" and then make sure that it is on "Arduino Uno" option. You also need to click "Board" to make sure it matches as well "Arduino Uno". With the pins you can connect things with them and create circuits. For example, if you are working with pin 13, you will write in the program "pinMode(13,OUTPUT)". When you write words in the correct form, they should turn into a color. When you want the LED light to turn on, you write "digitalWrite(13,HIGH)". When you write "LOW" instead, it will turn it off. To make the light blink you then add "digitalWrite(13,LOW);" and you need to add a delay to make sure the blinking is visible to the human eye. The command is "delay(1000);" in between the two other commands and after the "digitalWrite(13,LOW)".</p>
  <img width="250" alt="Screenshot 2021-10-28 at 10 59 13" src="https://user-images.githubusercontent.com/93208364/139292084-24d718a1-19ac-4d88-8bfc-338886d233a8.png">
 <br>
<p style="text-align: center;">You will place a wire in pin 13 and connect to a column. Then you connect a leg of a resistor by placing a leg in the same column of the wire. You will place the LED light connected to the second leg of the resistor, this means it must be on the same column. The long leg needs to go towards the positive voltage. The last wire will pin GND and connect on the same column of the LED light's second leg. This is the program used to make the light turn on. The delay is very long in order to see it well. But you can change it however you please. </p>
<img width="377" alt="Screenshot 2021-10-28 at 11 33 37" src="https://user-images.githubusercontent.com/93208364/139292506-d35d1b46-e5e8-4316-8e5f-b8668806a5d6.png">
<img width="404" alt="Screenshot 2021-10-28 at 16 58 43" src="https://user-images.githubusercontent.com/93208364/139292590-f634ea40-ae4e-4e0d-ac6d-008bfb39adb3.png">
<img width="352" alt="Screenshot 2021-10-28 at 11 41 12" src="https://user-images.githubusercontent.com/93208364/139292763-966465bf-c430-423b-a6e3-87bd60c4f1ed.png">
<br>
<h4>Third Circuit Example</h4>  
<p style="text-align: center;">For this part, you will need an arduino Uno, a breadboard, a USB cable, 3 resistors and 4 jumper wires. Connect them like in the pictures above. The resistors need to be spaced out from each other and a leg be on the negative row. The LEDs longest leg will connect with the resistor's leg. The wires must connect on one side with the other LEDs leg and the other on the pins. The USB cable will power the Arduino. Below is the program used to make the lights go on a sequence. The loop is the actual instructions of the lights to follow. 
</p>
  <img width="487" alt="Screenshot 2021-10-28 at 11 53 12" src="https://user-images.githubusercontent.com/93208364/139293166-a797b560-24ca-4e21-b66b-aee56da4dd9d.png">
  <br>
<strong>These are the Results:</strong>
  <br>
  <img width="379" alt="Screenshot 2021-10-28 at 11 04 56" src="https://user-images.githubusercontent.com/93208364/139293308-6155b0d3-54ee-4584-a753-a72b2cd1adf3.png">
<img width="377" alt="Screenshot 2021-10-28 at 11 07 58" src="https://user-images.githubusercontent.com/93208364/139293339-df2147e3-8023-450f-98a3-4db592112884.png">
<img width="381" alt="Screenshot 2021-10-28 at 11 26 17" src="https://user-images.githubusercontent.com/93208364/139293383-39930c65-caba-4c21-b782-016a8059210b.png">
<img width="384" alt="Screenshot 2021-10-28 at 11 29 16" src="https://user-images.githubusercontent.com/93208364/139293423-b4883279-0b26-419f-938d-28d346c0a2c9.png">
<p style="text-align: center;">These are two videos I made. The first one shows how I changed the variables to make light twitching very fast. The second video is morsing the code S.O.S.</p>

https://user-images.githubusercontent.com/93208364/139296299-026ff760-05a0-468f-b087-f9bcd54605b9.mp4
<br>
<p style="text-align: center;">This is the second video</p>  
https://user-images.githubusercontent.com/93208364/139296379-9704d370-8ce8-4a59-b7fd-c406c1b80f76.mp4
<br>
<p style="text-align: center;">I used the Youtube Link below to help myself with Arduino./p>
[https://www.youtube.com/watch?v=fJWR7dBuc18&list=PLGs0VKk2DiYw-L-RibttcvK-WBZm8WLEP&index=1&ab_channel=PaulMcWhorter](url)
<br>
<h3>Open Source and GitHub</h3>
<p style="text-align: center;">I found this definition: "Open source is source code that is made freely available for possible modification and redistribution. Products include permission to use the source code, design documents,or content of the product. The open-source model is a decentralized software development model that encourages open collaboration. A main principle of open-source software development is peer production, with products such as source code, blueprints, and documentation freely available to the public. The open-source movement in software began as a response to the limitations of proprietary code. The model is used for projects such as in open-source appropriate technology and open-source drug discovery".</p> 
Wikipedia Contributors (2019). Open source. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Open_source.
<br>
<p style="text-align: center;">The source code of a program is specially designed to make programmers' work easier, as programmers specify by writing source code what actions a computer should perform.</p>
  <p style="text-align: center;">I was still unsure what it actually meant so I decided to watch this TED talk which really helped.</p>
  https://www.youtube.com/watch?v=glPmxeVMgyg&t=64s Why I Give My Best Design Ideas Away for Free | Ben Uyeda | TEDxJamaicaPlain.
  <br>
 <li>"How do you design for people who can't afford to hire you?"</li> 
 <li>"Design is a way to access new experiences no matter how limited the resources are."</li>
  <li>"When other people make and sell my ideas, I get to learn how they improve them"</li>
  <li>"The surest way to run out of new ideas is to hold on too tightly on old ideas"</li>
  <li>"If i was spending time developing products I would spend months if not years, on ideas that i already have and i would see new ideas as distractions and not opportunities."</li>
 <br/>
 <nav>
   <p style="text-align: center;"> He produced media content that motivated, instructed and resulted in economic activity.I decided to watch another TED talk. "Open Source Design: Design is the Future of Open Source - Soleio, Combine (Config)"https://www.youtube.com/watch?v=2jlt-1E1Ee0&feature=emb_logo&ab_channel=Figma </p>
   <br>
   <p style="text-align: center;">It shares the importance of creative computing. Open Source is a way of teaching by sharing. New infrastructures were engineered when they were open sourced for example. Open sourcing should be made accessible to only people that know how to code. It shares this example Spreadsheet by Moira for the #MeToo movement. It allowed many women to share the perpetrators that inflicted sexual violence upon them. This spreadsheet reached a lot of popularity. The right combination of tool, people and distribution demonstrated the power to kick off investigations and in some cases create justice and cultural reform. Open source is evolving, allowing many more people to access technology. We need to broaden access to technology and design. If not the concentration of power to few give them opportunity to reveal their talent.</p>
   <img width="497" alt="Screenshot 2021-10-28 at 18 10 20" src="https://user-images.githubusercontent.com/93208364/139302999-5f988e7b-f783-4e0e-a662-dee656ab6b21.png">
This picture was taken form TheGuardian.com portraying Moira. 
   <br>
   <strong>Examples of Open Sharing in communities:</strong>
   <br>
   <p style="text-align: center;">"One Community - For The Highest Good Of All" is a non-profit community organized by volunteers. Their "mission is to help people create a better world by demonstrating a more sustainable and enriching way of living and open source everything needed for replication. This includes free-shared and “Highest Good” approaches to food, energy, housing, education, for-profit and non-profit economic design, social architecture, fulfilled living, global stewardship practices, and more. Combined, we will use these to build One Community as the first of many teacher/demonstration hubs. These hubs will form a global collaborative to provide even more research, blueprints, and necessary support for successively easier, more affordable, and creative duplication everywhere." </p>
   <br>
   <p style="text-align: center;">Open sourcing for them is fundamental, as it promotes collaboration instead of competition, as everyone as a free access to the information they provvide and are encouraged to share their ideas. A solution-creating solution model offers this benefit as it does not limit the possible solutions. They want to promote this sharing to improve humanity. </p>
   <img width="664" alt="Screenshot 2021-10-28 at 18 22 39" src="https://user-images.githubusercontent.com/93208364/139304692-9fb5319c-5d04-4b12-886e-a422e454f09c.png">

   <p style="text-align: center;"> They said: "Most people know now that the necessary resources and technology exist to solve our biggest challenges. We have the ability to feed, house, and provide energy for every person on Earth if we want to. These solutions, however, are currently not available to most people. People can create solution-creating solutions specific to each of these areas though. Doing this will make food, energy, and housing accessible and replicable by people with average knowledge and little or no experience. It will also teach these people how to teach others how to replicate these things too.  People visiting generates even more sharing of the solutions and model and also generates revenue for expansion and additional design, development, and construction. "</p>
<h2>"Give a man a fish and you feed him for a day. Teach the man to fish and you feed him for a lifetime" - Chinese Proverb</h2> 
