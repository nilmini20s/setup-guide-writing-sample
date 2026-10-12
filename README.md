### About this setup guide extension

I wrote this as a writing exercise for Antithesis, a software testing company. The task was to extend their existing [Setup Guide](https://antithesis.com/docs/setup/docker_compose/) so it teaches readers how to access and interpret the results of their first test.

The existing guide ends once the user has kicked off a test run. My extension adds three new sections — Access your results, Understand your results, and Next steps — that orient the reader to the triage report, Logs Explorer, and multiverse map. I also wrote editorial observations noting inconsistencies between the Docker Compose and Kubernetes versions of the guide.

I wrote this sample in Markdown in VS Code and pushed it to GitHub.

**Intended audience:** A performance validation engineer already using the simulator, who has results in hand, and needs to consolidate results for analysis.