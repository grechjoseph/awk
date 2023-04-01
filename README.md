# awk

ls -lrt | tail -n +2 | awk '{print "File name: " $9 ", File size: " $5}'

1. list all files 
2. start from second line (to exclude column names)
3. Print "File name: " + <9th field> + ",  File size: " + <5th field>
