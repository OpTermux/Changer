# !/bin/bash
 
 
printf "\033[1;36m #######################################################\n" 
printf "\033[1;36m ##                     OpTermux                      ##\n" 
printf "\033[1;36m ##  If you get any error comment me I help you 24*7  ##\n"
printf "\033[1;36m #######################################################\n" 
 
# Input type of operation
echo "Enter Choice :"
echo "1. MAC Address"
echo "2. IP Address"

read ch

 
# Switch Case to perform selection
case $ch in
 
  1)echo "Enter MAC Address:"
 
  res=`
read mac

ifconfig eth0 down
ifconfig eth0 hw ether $mac
ifconfig eth0 up

echo "Your MAC Address Changed successfully"
`
  ;;
  
  
  2)echo "Enter IP Address:"
  
  res=`

read ip
ifconfig eth0 $ip
echo "Your IP Address Changed successfully"
`
  ;;
  
esac
echo " $res"
