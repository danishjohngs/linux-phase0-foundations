## Step 1 – User & Group Setup

```bash
sudo adduser dev1
sudo adduser dev2
sudo groupadd project
sudo usermod -aG project dev1
sudo usermod -aG project dev2
```
## Step 2 – Secure Directory Creation
```
sudo mkdir /project
sudo chown root:project /project
sudo chmod 770 /project
```
## Step 3 – Secure File Creation
```
sudo touch /project/secret.txt
sudo chown root:project /project/secret.txt
sudo chmod 660 /project/secret.txt

