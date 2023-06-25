#!/bin/bash


echo "Welcome to Simple Bash Calculator"

echo 

echo - "\t" "Press + for addition"
echo  "\t" "Press - for substraction"
echo  "\t" "Press * for multiplication"
echo  "\t" "Press / for division"

echo
echo -n "[+] Enter what you want to do"
read CAL


echo -n "Enter the first nuumber:"
read FIRST

echo

echo - n "Enter the second number:"
read SECOND

echo

RESULT=`expr $FIRST  $CAL $SECOND`

echo 

echo "Your Result is:- " $RESULT 

