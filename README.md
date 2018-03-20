# Hackathon-4.0
Our Project aims for Smart City prototype by leveraging Internet of Things (IoT) and Smart Contracts to come up with a peer-to-peer monitored energy distribution system to solve most of the power grid problems in the state of Rajasthan . The main problems with the existing infrastructure are :-

i)Billing process requires manual intervention.
ii)Electricity bill may not be paid on time by the buyer
iii)Illegal tapping of power lines
iv)Unethical selling of units by electricity board

We have proposed an IOT and blockchain based solution :

An IOT enabled meter is installed in every house, that sends the meter reading at regular intervals to a decentralized blockchain. This way, every house’s usage is transparent.Local transformers and power plants too are connected to the blockchain and upload their electricity transactions on a regular basis. Hence, in case of illegal tapping of electricity, the sum of electricity usage by individual houses and transformers/power plants will not be equal, and the blockchain will detect this theft.
The household now pays through a Smart Contract that fetches the unit usage of the meter from the blockchain. Once the required amount is paid, the Smart - Contract uploads this transaction to a payment blockchain, and sends a permit signal to the IOT-enabled meter for next month The meter too is a smart device. If it does not receive a permit from the Smart Contract e.g. when the bill is not paid on time , then it trips the connection of the house. Hence, manual intervention is not needed and the process is automated.
With the current prototype, we have developed a framework which is very easily extensible to other basic distribution services provided and administered by government like:

Water Supply in Agriculture 
Water Supply to houses 
Travel and transport

Approach Technique for Resolving the Problem 

Our solution is based on IoT smart devices that automate the process and blockchain which is tamper proof that ensures transparency and prevents and detects fraud. 

IoT enabled meters installed in house automate the process of submitting periodic readings
A decentralized blockchain ensures that every transaction in terms of electricity e.g. how much a house has utilized , how much a power plant of organization has transmitted, etc is transparent and consistent. Any fraud would lead to inconsistent blocks, hence triggering detection of a possible illegal tap.
Smart Contracts form the core of the system. They manage payments of each meter based on their blockchain readings, and manage permits for electricity for the next month. If a household fails to pay bill in the required time, the smart contract does not send permit to the IoT meter, which results in the meter automatically tripping the connection
