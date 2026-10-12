### About this setup guide extension

I wrote this as a writing exercise for Antithesis, a software testing company. The task was to extend their existing [Setup Guide](https://antithesis.com/docs/setup/docker_compose/) so it teaches readers how to access and interpret the results of their first test.

The existing guide ends once the user has kicked off a test run. My extension adds three new sections — Access your results, Understand your results, and Next steps — that orient the reader to the triage report, Logs Explorer, and multiverse map.

**Note:** Antithesis has since updated their setup guides. This sample was written against the earlier version of the guides, which configured test launches via curl rather than through the web app.

**My approach:** The original final section did two things at once: it briefly mentioned the triage report and listed next steps. My extension separates these into distinct sections — Access your results, Understand your results, and Next steps — giving each topic room to orient the reader one step at a time.

While working on this, I also noticed inconsistencies between the Docker Compose and Kubernetes versions of the guide (different section headings, different coverage of the Logs Explorer and email notifications). I wrote the new sections so they could be appended to both guides.

I wrote this sample in Markdown in VS Code and pushed it to GitHub.

**Intended audience:** A developer who has just set up Antithesis and triggered their first test, and needs to find and interpret the results.