echo "enter number:"
read x
y=$((  $x % 2 ))
if [ $y -eq 0 ]
then
echo "Number is even"
else
echo "number is odd"
fi
