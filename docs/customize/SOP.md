# SOP

SOP stands for Standard Operating Procedures, which are the set of documents and processes used by a business where the management records the business operations regarding the delivery and follow-up of the products and services over time

## Malware Anlysis

Malware analysis is the process of determining the purpose and functionality of a piece of malware. This process will reveal what type of harmful program has infected your network, the damage it’s capable of causing, and—most importantly—how to remove it. Malware analysis used to be performed manually by experts in a time-consuming and cumbersome process. Today, there are a number of open-source malware analysis tools that can perform this process automatically

Examining the capabilities of malicious software allows you to better assess the nature of a security incident, and may help prevent further infections. Here’s how to set up a controlled malware analysis lab—for free.

## Step 1: Allocate systems for the analysis lab

A common approach to examining malicious software involves infecting a system with the malware specimen and then using the appropriate monitoring tools to observe how it behaves. This requires a laboratory system you can infect without affecting your production environment. The most popular and flexible way to set up such a lab system involves virtualization software, which allows you to use a single physical computer for hosting multiple virtual systems,each running a potentially different operating system.Running multiple virtual systems simultaneously on a single physical computer is useful for analyzing malware that seeks to interact with other systems, perhaps for leaking data, obtaining instructions from the attacker, or upgrading itself. Virtualization makes it easy to set up and use such systems without procuring numerous physical boxes.

  .. Caution:: 

    This test steps for Malware analysis.


Analysis File
------------------
Behavior Analysis
---------------------

 ![](Behavior.jpg)


Dropped File 
------------------------

 ![](DropFile.jpg)