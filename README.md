# Command-Injection-Attack-Detection

I have found the date and time that the command injection attack was intiated.
<img width="580" alt="Screenshot 2024-10-07 at 2 33 37 PM" src="https://github.com/user-attachments/assets/b9201070-29e6-451b-8a41-3d6218ed8ba6">

I have also found the IP address of the attacker.

<img width="581" alt="Screenshot 2024-10-07 at 2 35 17 PM" src="https://github.com/user-attachments/assets/c6b1a6a5-0fca-4ad2-80c6-b4e2af64cfa8">

I can tell that this is an attack for a few reasons. The use of the semicolon (;) indicates an attempt to chain commands in a shell environment. The attacker includes ;ls after the IP address. The semicolon lets them terminate the original command and insert a new one, which is a common tactic in command injection. The query parameter q=1.1.1.1;ls implies the attacker aims to execute shell commands. The command ls is used to list files, which could reveal sensitive information about the server’s directory.<img width="579" alt="Screenshot 2024-10-07 at 2 39 10 PM" src="https://github.com/user-attachments/assets/1b55d6f3-0798-4f6e-b114-fcb631778ba2">
