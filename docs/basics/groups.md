# Groups

It's often a good idea to create a group for whatever you are doing. It makes *security policies* so much easier to manage.

- If you are creating **users**, put them into corresponding ***User Groups*** 
- **IP-addresses**, create an ***Address Group***
- Filtering based on **applications** - create an ***Application Group***
- **Services** - create a ***Service Group***

And so on.

### Example

Let's say you already have a *Security Policy* that blocks for a certain type of applications through ***Application Groups***. You discover a new application of the same type and it needs to be blocked, then it's much easier to just add the application to the group and continue filtering through the same policy than.
