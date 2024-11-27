# Debugging Checklist: My mindful approach to technical troubleshooting
*v1.0.0*

## Before I start
- Get my notebook ready to document observations.
- Take a moment to feel the sensations in my body - am I feeling anxious or rushed? If yes, step away from the computer, make a cup of tea and give myself at least a minute of mindful breathing to relax. 
- Remind myself that it's okay not to know the answer straight away
- When I'm feeling grounded, set a timer for 45 minutes of focused investigation.

## My redflags
These are the thoughts or patterns I see myself doing sometimes that show I am moving towards a more reactive and fight/flight probelm solving mode. I am documenting them so that I know what to look out for. At any time these come up for me, my plan is to take pause and practice a mindful/awareness based exercise to help me slow down.

- **Thinking**: "I'll just try this quick fix..."
- **Acting**: Making multiple changes at once
- **Feeling**: too anxious to ask questions
- **Acting**: Skipping documentation of my debugging steps
- **Feeling**: like I need to race to implement a solution and know all the answers

## Step 1: Gather basic info (may require working with client or user to gather information) (5-10mins)
- Who reported the issue?
- What exactly am I seeing?
- When did this start happening?
- Can I reliably reproduce the issue? (don't reproduce at this stage, just to know if it will be possible)
- Document the exact error message (if any).

## Step 3: Understand Context (5-10 mins)

- Which environment am I in? (local, staging, production)
- What user actions lead to this issue?
- Does the issue affect all users or just some?
- Are there related errors in the logs?
- Have there been any recent deployments or changes in the code base?
- Write a problem statement to address e.g. when a user logs in, they cannot see their profile page

## PAUSE 
- Take a moment to notice if I'm feeling rushed or anxious
- If not, carry on
- If yes, try: a mindful/grounding exercise like a quick bodyscan, box breath with longer exhale for a few minutes
- Remind myself: "I have time and no one is going to die if I don't get the answer"

## Step 5: Write down up to 3 possible causes

- Write down 3 possible causes before investigating any
For each hypothesis, note:
  - Why do I think this might be the cause?
  - How can I test this specifically?
  - What evidence would prove/disprove this?

* if it has been more than 30minutes here, would it be helpful to run what i have so far past someone for help?

## Step 6: Testing

Test one possible cause at a time and:
- Document each testing step - console.log, dd(), debugger tools
- Make sure to check browser developer tools along the way at each step (Network, Console, Elements) and note down any logs/errors
- Review results and assess if this fix has addressed the problem statement.

## Step 7: Ask for Help (If stuck for >30 mins)

Summarize what I've tried by sharing investigation notes
Ask specific questions like:
"Could you review my debugging approach?"
"Based on my notes, do you think I am on the right track with the possible causes and should keep testing?"
If I am being blocked by a technical concept or issue that I don't fully understand, I could ask for help understanding that before proceeding e.g.
"Could you help me understand [the specific concept]?"



## Learning Reflection
Some steps to follow after an issue is resolved to help with learning and debugging for next time:
Optional reflection questions:
- What was the actual cause?
- What did I learn about the system?
- What new technical concepts do I need to study?
- How could I prevent similar issues?