# BD-n8n-GenericShares
Sharing some generic n8n agent and AI enhancement Workflows for BD Users

This is to support a webinar about some automation possiblities for Brilliant Directories using n8n. It's highly specific to that chat and likely not overly useful for others. But feel free to use as templates for whatever.

# What do these workflows do?

* Worlkflow A takes URL listings from a Google Sheet file and researches what they are, generating descriptions, search slugs, and categorization.
* Workflow B takes the results of Workflow A and uses the Brilliant Directories API to load the new listings.

# Warning

I've put these up on here as templates to support a webinar training session. I'm going to leave them as reference as they may be useful as starter templates to modify for other projects. However, note at least these three things... 1) Things change fast in today's environments; nodes and code may become deprecated quickly. And 2) These workflows are highly specific to use of a Supabase database and a Brilliant Directories application. There's a manual "human in the loop" step between the workflows and that's intentional, both for a gut check and to also insert logo / graphic links for listings. 3) Brilliant Directories now has embedded AI tools that likely makes this kind of effort wholly unnecessary. Though I think it may still be useful as an external batch process, especially for maintaining an external canonical reference database such as may be done with Supabase or another database.
