### NAME: SRI SRINVASAN K
### REG NO: 24900578
### EXP NO 4: FULL ADDER AND FULL SUBTRACTOR

### **AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

### **EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

### **FULL ADDER AND FULL SUBTRACTOR**

### **FULL ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)



### **FULL SUBTRACTOR**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

### **TRUTHTABLE:**
### **FULL ADDER:**
![full-adder](https://github.com/user-attachments/assets/df08eb1d-aa61-4fe6-bc79-207dbbe4a9ce)

### **FULL SUBTRACTOR**
![full-subtractor](https://github.com/user-attachments/assets/3dc16edf-b029-486c-a86f-791d781ea2e6)


### **PROGRAM:**
![Screenshot 2024-12-12 111230](https://github.com/user-attachments/assets/b414e2d8-4652-4ee3-b577-0fbf0757cdfd)



### **RTL REALIZATION OUTPUT:**
![Screenshot 2024-12-12 110003](https://github.com/user-attachments/assets/eb3d34e4-c783-4e9e-859b-e41897f462db)


### **OUTPUT TIMING WAVEFORM:**
![Screenshot 2024-12-12 110927](https://github.com/user-attachments/assets/24bedbbf-aeca-40fd-b242-543ca90cbc20)

### **RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



