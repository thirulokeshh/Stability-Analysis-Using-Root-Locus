# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![IMG-20251115-WA0064](https://github.com/user-attachments/assets/3ea887b5-0cd5-428a-a20e-2c12b9118a04)
![IMG-20251115-WA0065](https://github.com/user-attachments/assets/4a8cd3e2-5d29-4e03-ba65-75b9bfebb9ff)
![IMG-20251115-WA0066](https://github.com/user-attachments/assets/2423134a-f921-4a52-acb4-6f2c1bd0376a)
![IMG-20251115-WA0067](https://github.com/user-attachments/assets/820fb044-7e9c-4f94-99cb-7b9b1bec573e)


## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
~~~
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
~~~

## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-15 211113" src="https://github.com/user-attachments/assets/f41fab13-86e7-4745-a9eb-8d90c3cde55b" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 749.55 
