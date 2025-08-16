# Tango
Tango is a task planning and context management tool for Claude Code

This come from my practical experience with Claude to build production grade software

# Problem statements
Planning and Context Mangement is extremely important to achieve desirable engineering outcome with automated system

# The Tango workflow 

Step setup. /setup-tango this will create .tango along with necessary directory structure within
Step 1. Start with inquiry in **Plan mode**. Plan out the features with Claude.
Step 2. /plan-init - This will begin another series of conversation with Claude. The outcome will be a plan directory inside .tango with verbose directory name. The plan name will be reported back to the user
Step 3. /plan-revise - Make changes in initial plan.
Step 4. /plan-retrieve [Name of plan] - Get the most upto date working session of the plan to continue working
Begin implementation using the retrieve plan
Step 5. /session-log - Update the plan directory with the most recentwork to keep context up to date.

# Important Note 
1. Always clear context with /clear before working one new thing
2. Always 
