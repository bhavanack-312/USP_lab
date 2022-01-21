#!/bin/bash
echo "Enter a string"
read string
count=0
l=`expr "$string" : '.*'`
for ((i=0;i<$l;i++))
do
c=`expr "$string" : '\(.\)'`
if [ "$c" = 'a' -o "$c" = 'e' -o "$c" = 'i' -o "$c" = 'o' -o "$c" = 'u' ]
then
count=$(($count+1))
fi
string=`expr "$string" : '.\(.*\)'`
done
echo "The number of vowels: $count"
