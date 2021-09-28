This branch brute-forcees a method to output wallet values in non-exponential format so it can be used via the commandline directly for things like calculations, etc.

Devs whithin ChiaCo rejected it in leiu of a re-write of the python standard libraries to fix the issue upstream in order to resolve this problem, which would be great but I don't have time to babysit, so I'm just running with this patch applied.  Maybe someday they'll fix, but for now this is an immediate fully-working solution (however hacky it might appear on the surface).
 
-=dave
