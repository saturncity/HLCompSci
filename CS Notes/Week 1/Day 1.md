# Topics for First Semester

Week 1: Introduction to Computer Science
Weeks 2-7: Topic 2 - Computer Organization
Weeks 8-9: Topic 6 - Resource Management
Weeks 11-14: Topic 3: Networks
Weeks 15-16: Topic 7: Control
Weeks 17+: Topic 4: Computional Thinking

-----
 
 ### System Development Life Cycle
- The system development life cycle is a model that represents how long term projects are kept alive.
- The system follows these steps:
	1. Plan
	2. Analyze
	3. Design
	4. Develop
	5. Testing
	6. Implement/Integrate
	7. Maintain (go back to step 1)

###  Migration
- Computer Migration is a process that involves transfering data from one client to another. Many different things can be migrated, such as:
	- Data (Files)
	- Databases
	- Applications
	- Processes

### Alpha Testing vs Beta Testing
- Alpha testing is testing that is done locally on the host organization's technology. This is often done to make sure the product is use-able for beta testing.
- Beta testing is testing that is done externally which is often tested through the view of an actual user.
	- There are multiple types of beta testing:
		- Traditional Beta Testing
			- This is often done when there are no full releases of a product and the fixing/maintenance/newer versions gets done as the product is in devleopment.
		- Public Beta Testing
			- This kind of testing is a testing that lets the public optionally beta test the product. This kind of testing is effective to gather info from users enthusiatic to use the beta, but still let others opt-out.
		- Technical/Closed Beta Testing
			- This kind of beta testing is often done among a very small group of people. There are multiple reasons why closed beta testing occurs. One of the more common examples is when it is given to third parties to have early support. Other times the closed beta is just kept among employees and other people the company can trust.
		- Focused Beta Testing
			- Focused beta testing is when developers don't give access the full beta. This testing often exists to test essential parts of an upcoming product. Focused testing is a good way to ensure that certain parts of a product have been tested throughly.
		- Post-release Beta Testing
			- Post-release testing is often testing done for an expiremental version of a product.

### Debugging
- Debugging is a multi-step process to ensure code runs as expected. 
- The process is as follows:
	1. Find the error's location
	2. Analyze the error
	3. Prove the analysis
	4. Cover lateral damage
	5. Fix and validate
	6. Identify that you have an error (repeat if true, stop if false)

### Router vs Modem
- In networking, a Modem is what connects your network to the world-wide network.
- A <u>Route</u>r is what connects other devices to the Modem. As well as allowing communication between devices without reaching the world-wide network.
- Often most Internet Service Providers (ISPs) provide products that perform both.

### Modularity
- Modularity in networking, is when multiple parts of a network are seperated so that, if one section fails all the others will be left unaffected (or not depending on what has failed). 
- This can be seen in functions in coding. Instead of always using the same formulas in code, it is possible to make a function that can do that. This helps to reduce the complexity and ensure that the calculations are done correct every time.

### Parts of a CPU
[[Days 2-5; Computer Architecture]]

### Types of Memory
[[Days 2-5; Computer Architecture]]

### Volitie Memory
[[Days 2-5; Computer Architecture]]

### Binary
- "[The] binary number system, in mathematics, [is a] positional numeral system employing 2 as the base and so requiring only two different symbols for its digits, 0 and 1, instead of the usual 10 different symbols needed in the decimal system. The numbers from 0 to 10 are thus in binary 0, 1, 10, 11, 100, 101, 110, 111, 1000, 1001, and 1010." Britannica
- To convert 00001101 to decimal we follow this process:
$$=(0)128+(0)64+(0)32+0(16)+(1)8+(1)4+(0)2+1(1)$$
$$=8+4+1$$
$$=13$$
- Binary is the language that computers communicate in. This is because the transitors within a computer can only reliabley understand on/off or low/high voltage.


### Data Types (Java)
Not going into too much detail here since we will get taught this

- Primative Data Types
	- Byte
	- Short
	- Int
	- Long
	- Float
	- Double
	- Boolean
	- Char
- Non-Primative Data Types
	- Strings
	- ArrayLists

### Concatination vs Arithmatic
- Concatination is the process of conjoining two strings together. For example:

"Hello," + " " + "how ArE yOu?" = "Hello, how ArE yOu?"

- Lazy Concatination is when a number is "cast" into a string automatically.

2 + ", is pronounced the-ree"
^ This IS Lazy Concatination

"2" + ", is pronounced the ree"
^ This ISN'T Lazy Concatination

- Artithmatic is basic math this can be:
	- Adding
	- Subtracting
	- Multiplying
	- Deviding
	- Remainder
	- Incrementing
	- Decrementing

### Logic Gates

![[logic gates.png]]
