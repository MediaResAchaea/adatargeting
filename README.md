# Ada's targeting script, packaged and cleaned up a bit, and given a namespace that isn't Ada. No functional changes.

## How it works:
STEP 1: Set leaders with setl <name1> <name2> <name3> ...

STEP 2: ALLY PARTY and then do ALLIES to let it capture current allies. 
Make sure you repeat this step to keep the allies list in sync
          
STEP 3: TEST! TEST! TEST!! You should be following the leader's calls
but don't trust it battle yet till you've thoroughly tested

## How to test:
STEP 1: Do the above steps, STEP 1 and STEP 2

STEP 2: You can use the "testparty" alias to test locally!

STEP 3: Have a person configured as leader in your party call a target
in the format, "Target has been changed to <name>." You should see yourself switching to that target!

STEP 4: Have a person NOT configured as leader in your party call a
          target in the same format, you should see it getting ignored
