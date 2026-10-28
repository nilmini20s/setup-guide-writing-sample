### About this setup guide extension

Antithesis is a developer tools company whose software testing platform helps developers find bugs by running their software in deterministic simulations. I wrote this as a writing exercise extending their [Setup Guide](https://antithesis.com/docs/setup/docker_compose/) guide with the final steps a new user takes after running their first test. 

Ther existing guide ends once the user has kicked off a test run. I extended the guide to show users how to access and interpret the results of their first test. My extension adds three new sections — _Access your results_, _Understand your results_, and _Next steps_ — that orient the reader to the triage report, Logs Explorer, and multiverse map.

**Note:** Antithesis has since updated their setup guides. This sample was written against the earlier version of the guides, which configured test launches via curl rather than through the web app.

**My approach:** The original final section did two things at once: it briefly mentioned the triage report and listed next steps. My extension separates these into distinct sections — _Access your results_, _Understand your results_, and _Next steps_ — giving each topic room to orient the reader one step at a time.

While working on this, I also noticed inconsistencies between the Docker Compose and Kubernetes versions of the guide (different section headings, different coverage of the Logs Explorer and email notifications). I wrote the new sections so they could be appended to both guides.

I wrote this sample in Markdown in VS Code and pushed it to GitHub.

**Intended audience:** A developer who has just set up Antithesis and triggered their first test, and needs to find and interpret the results.
