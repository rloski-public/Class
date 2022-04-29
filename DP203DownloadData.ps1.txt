$breakline = "**************************************************************************************`n"
get-date
write-output "$breakline   Starting DP-203 Download"
mkdir c:\dp-203

cd c:\dp-203

git clone https://github.com/microsoftlearning/dp-203-data-engineer.git data-engineering-ilt-deployment


write-output "$breakline   Ending DP-203 Download"

get-date
write-output "$breakline   Starting PySpark Cookbook Download"
git clone https://github.com/PacktPublishing/PySpark-Cookbook.git PySpark-Cookbook
write-output "$breakline   Ending PySpark Cookbook Download"
get-date
