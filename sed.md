# Replace from match
sed 's:match.*:match'

# Add string before
sed 's:original:new&'

# Use like grep
sed -n '/START/,/END/p' $file

