# Final Border Check Logic

The Final Border Check resolves whether each Active player can legally leave.

## Step 1: Determine border strictness

Use the current Heat level.

| Heat | Border requirement |
|---:|---|
| 0 | Passport + Visa Stamp + Exit Ticket |
| 1 | Add Entry Proof |
| 2 | Add 1 Supporting Document |
| 3 | Suspicious documents become risky |
| 4 | Add 2 Supporting Documents |
| 5 | One random document per player is audited |
| 6 | Lockdown, Scammers usually win |

## Step 2: Check each Active player

Deported players do not count as legal exits.

## Step 3: Resolve Suspicious documents

At low Heat, Suspicious documents may pass.

At high Heat, Suspicious documents fail unless Cleared.

## Step 4: Count valid exits

Compare the number of valid exits to the script threshold.
