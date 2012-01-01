title: Exception Handling in .NET
author: Ragunathan Pattabiraman
date: 5-January-2012

# Exception Handling
## in .NET

# What can go wrong?

# Not enough memory
# No DB connection
# Bad input
# File IO exception
# No permission

# Error in error handling code
## :--)

# In short, EVERYTHING!

# "What can't go wrong?"
## Better question

# One approach
## Error Code

# 
<%code lang:'csharp' do%>

result = DoProcessing();

if(result != 0) {
  log("Processing failed!");
  return 1;
}
<%end%>

# Downsides of Error Code approach

# etc...
