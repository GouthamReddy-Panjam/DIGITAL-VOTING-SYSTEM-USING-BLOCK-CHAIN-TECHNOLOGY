# DIGITAL-VOTING-SYSTEM-USING-BLOCK-CHAIN-TECHNOLOGY

###  **ABSTRACT**  ###
The aim of this project is to outline our proposal to solving the digital voting by using blockchain technology. The project starts by brief explanation of what blockchain technology is and how it is currently used. The following section looks at present day deployments of digital voting and the issues they face. The main section of the project is a detailed breakdown of our proposed design followed by an analysis of potential flaws and threats . The final section is a conclusion of how we feel our design solves the issue at hand.

Security of digital voting is always the biggest concern when considering to implement a digital voting system. One way the security issues can be potentially solved is through the technology of blockchain.

Blockchain technology originates from the underlying architectural design of the cryptocurrency bitcoin. It is a form of distributed database where records take the form of transactions.

###  **INTRODUCTION**  ###
In the simplest terms, Blockchain can be described as a data structure that holds transactional records and while ensuring security, transparency, and decentralization. You can also think of it as a chain or records stored in the forms of blocks which are controlled by no single authority. A blockchain is a distributed ledger that is completely open to any and everyone on the network. Once an information is stored on a blockchain, it is extremely difficult to change or alter it.

Each transaction on a blockchain is secured with a digital signature that proves its authenticity. Due to the use of encryption and digital signatures, the data stored on the blockchain is tamper-proof and cannot be changed.

Each block in a blockchain network stores some information along with the hash of its previous block. A hash is a unique mathematical code which belongs to a specific block. If the information inside the block is modified, the hash of the block will be subject to modification too. The connection of blocks through unique hash keys is what makes blockchain secure.

### **THEORETICAL BACKGROUND** ###
In 2003, Estonia initiated the project of e-voting. The aim was to implement e-voting in the elections of the local government councils in 2005. In January 2004, a group of American security experts revealed the security report of Secure Electronic Registration and Voting Experiment (SERVE) [1]. The SERVE system was planned for deployment in the 2004 primary and general elections and allows eligible voters to vote electronically via Internet. After examining the security of SERVE, the group of security experts recommended that SERVE should be shut down. They also declared that they do not believe that differently constituted projects could be more secure than SERVE. Their conclusion was that the real barriers to success in e-voting are not skills, resources, etc; it is the fact that given the current Internet and PC security technology, e-voting is an essentially impossible task. The SERVE project was terminated indeed in January 2004. But estonia held there first elecctronic voting in2005! Our project’s theoretical background depends on estonia’s evoting timeline itself.

### **AIM OF THE PROPOSED WORK** ###
The aim of this project is to outline our proposal to solving the digital voting by using blockchain technology. The project starts by brief explanation of what blockchain technology is and how it is currently used. The following section looks at present day deployments of digital voting and the issues they face. The main section of the project is detailed breakdown of our proposed design followed by an analysis of potential flaws and threats . The final section is a conclusion of how we feel our design solves the issue at hand

### **OVERVIEW OF THE PROPESED SYSTEM** ###
Our design that we tried was to create a system that doesn’t entirely replace the current voting but rather integrates within a current system. We made the storage of votes more secure by implementing Block chain technology.

In India, there are about 10.6 Lakh polling places so securing the data of election results in hardcopy is not advisable. But using our system of block chain, all the data is decentralised and are kept securely within all nodes.

The system we are using is, while the polling process is going on. We collect the dataof voter’s ID (if wanted to vote) or miner’s ID(if wanted to mine a block with some count of votes) Then the data is entered into our block chain through miners and hashed and decentralised. Thus the data can’t be tampered.

### **ARCHITECTURE OF THE PROPOSED SYSTEM** ###
![image](https://user-images.githubusercontent.com/88433888/197354372-22f1cd22-2ba8-4735-81ef-23bcd4ff7d57.png)

### **SYSTEM MODEL** ###
![image](https://user-images.githubusercontent.com/88433888/197354402-f36f961a-b312-4783-bb0a-f92923289918.png)

### **IMPLEMENTATION** ###
* Clone the repository into your local machine
* Run the file, "main.py" using the command, "python main.py"

### **OUTPUT SCREENSHOTS** ###
![image](https://user-images.githubusercontent.com/88433888/197355042-df97ecc1-c353-4244-85d5-221f0810be0c.png)

![image](https://user-images.githubusercontent.com/88433888/197355057-2006e14a-ca47-485a-96ff-5a658d696c72.png)

![image](https://user-images.githubusercontent.com/88433888/197355070-8bec2280-d5e8-4146-b8b8-50d563967d0e.png)

![image](https://user-images.githubusercontent.com/88433888/197355107-1dd31109-bb30-4b93-819c-57220188c343.png)

### **BEFORE MINING** ###
![image](https://user-images.githubusercontent.com/88433888/197355141-073b71dc-ca69-40f4-833e-63b144353de4.png)

![image](https://user-images.githubusercontent.com/88433888/197355151-8e3cec2f-b95d-472b-92f4-a39ac2f7cef7.png)

### **VOTES GO INTO A BLOCK BY MINING** ###
![image](https://user-images.githubusercontent.com/88433888/197355167-9bae469d-2600-495a-a088-7a195de9f376.png)

### **AFTER THE MINING THE CHAIN LOOKS LIKE** ###
![image](https://user-images.githubusercontent.com/88433888/197355183-4da6e54b-d17e-4649-9a02-c5e6d2089855.png)

### **THE PROCESS THAT GOES ON BACKEND** ###
![image](https://user-images.githubusercontent.com/88433888/197355204-ebdb1ec8-addc-486f-ba97-1e6d080516aa.png)

### **CONCLUSION** ###
Our proposal of blockchain implementation in online voting system is better then what used in Estonia government since they made each of ten to fifteen votes as a block and hashed them (mine). Whereas on the other hand over proposal hashes the results of polling therefore very less resources spending in mining. Saving a lot of government resources.

India has about 10.6 lakh polling stations and there for the data is decentralized then more then we want it becomes more difficult to tamper. The possibility of ‘’51% Attack’’ is very less and difficult in case of having 10.6 lakh nodes.

Voter’s data is not compromised as the data which is being decentralised is only the number of votes by each candidate but not voter’s choice. On the other side the choice of the voter is also decentralised which against Indian government policies.

##### TEAM MEMBER/CONTRIBUTOR #####
Abhiram Borige





