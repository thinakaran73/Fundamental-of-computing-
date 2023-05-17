# Take input as binary number
echo "Enter Binary Number -"
read n

# function to convert binary to decimal number
function binaryCon(){

    local i=0
    local num=0
    
    # while loop
    while [ $n != 0 ]
    do
    digit=`expr $n % 10`
    num=$(( num + digit * 2**i ))
    n=`expr $n / 10`
    (( ++i ))
    done
    
    # print the resultant decimal number
    echo "Resultant Decimal Number"
    echo "$num"
}

# Function Call
binaryCon
