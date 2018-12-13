
##Spark with AWS EC2
Dostęp do Elastic Compute Cloud (EC2) poprzez konsolę webową:
1.     Konsola EC2: https://console.aws.amazon.com/ec2/v2/home?region=eu-west-1

2.     Najlepiej wybrać region EU (Ireland)

3.     Uruchomienie testowej instancji:

Obraz maszyny wirtualnej (Amazon Machine Image AMI) Ubuntu Server 16.04 LTS (HVM), SSD Volume Type - ami-092ad110dc1cdc2ed
Rozmiar instancji: ﻿t2.micro
Konfiguracja bezpieczeństwa: port 80 (HTTP) musi być otwarty
(Opcjonalne) Utworzenie nowej pary kluczy i zapisanie pliku klucz.pem.
4.     Połączenie do uruchomionej instancji:

Połączenie przez przeglądarkę, przykładowy adres: http://c2-176-34-70-221.eu-west-1.compute.amazonaws.com
Zapisanie obrazu instancji: Actions -> Create Image

Uwaga: na zajęciach korzystamy z obrazu: ami-092ad110dc1cdc2ed
