# practice1

# 1 + 1+2 +  1+2+3 +......+ 1+2+3+.....+100 sum program

i = 1;
sum = 0;
max_count = 100;
clause = 0;

while(i <= max_count){
clause = clause + i;
sum = sum + clause;
i = i + 1;


}

System.out.print("sum is"+ sum)

