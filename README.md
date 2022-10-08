# Newrl Testnet -  Mükafatlı Node  ( Son 1 gün, elə indicə qur getsin) 

* Son tarix : 9  oktyabr gecəyə qədər vaxtımız var. 

* Bitmə Tarixi : 15 oktyabr 2022 Yəni təxmini 1 həftə civarı gedəcəyi gözlənilir.
* Aktiv server varsa ora yoxdursa Digital OCeandan pulsuz verilən 28 usdlik serverə qura bilərsiniz. Göstəriciləri belədir

3 CPU

4 GB RAM

80 GB SSD

1. Scripti yazın
```bash
wget -O newrl.sh https://raw.githubusercontent.com/NodesWizard/Oto-Kurulumlar/main/newrl.sh && chmod +x newrl.sh && ./newrl.sh
```

2. Aşağıdakı 3 kodu 1-1 sıra ilə yaz, 2-3 dəqiqə gözlə, yükləmə edəcək. Ondan sonra ctrl+a+d ilə əsas ekrana qayıt. 
```bash
cd newrl
screen -r newrl
scripts/start.sh testnet
```
3. Aşağıdakı kodu yazandan sonra seçim etməyini istəyir. testnet yaz enter klik et. Sonra Y yazıb enter klik et.
```bash
cd newrl
python3 scripts/show_wallet.py
```
4. Yuxarıdakını yazdıqdan sonra keylər çıxacaq. Onları mütləq yadda saxla. 
![image](https://user-images.githubusercontent.com/65338121/194706724-9e219903-cd5d-42ef-ace5-9850955199f9.png)
5. Aşağıdakı linklər cüzdan saytına daxil ol.

https://wallet.newrl.net/

6. Şifrə yaz və cüzdanı import et. 4-cüdə çıxan keyləri ora yaz və okay bas. 

7. Okay vurduqdan sonra KYC bölümü var, hələki vacib deyil, istənilən ölkəni seç, istənilən şəkili seç və "active wallet" seç. 

8. Faucetə gir və cüzdan adresini yaz 500000 üstündə istənilən rəqəmi yaz, məsələn 696969 yaz və token al.

https://wallet.newrl.net/faucet/

9. Daha sonra sol üst menudan "run a node" seç və stake et 

10. Aşağıdakı cüzdanadr yerinə cüzda adresini yazıb, adi brauzerə yaz və "success" yazısı gəlibsə alındı. Yenə də 5-6 min qatladın noddan. 
```bash
http://archive1-testnet1.newrl.net:8421/sc-state?table_name=stake_ledger&contract_address=ct1111111111111111111111111111111111111115&unique_column=wallet_address&unique_value=CUZDANadr
```

Proyektin sosialları: 
dc girmeyi unutmayın..

Discord : https://discord.gg/zVpQrfmQ4Z

Twitter : https://twitter.com/newrl_layer1

website : https://newrl.net/

---------------------------------------------------------------------------

Bizi izləyin
Telegram: https://t.me/drtestnet

Youtube: https://www.youtube.com/c/KhayalAll/videos

Twitter: https://twitter.com/xeyalall


