**tl;dr**

...

7.  [**Run your first test!**](#run-your-first-test)

*   Trigger a test with the provided webhook endpoint.

8.  [**Access your results**](#access-your-results)

*   Check on the progress of your test on the **Recent runs** page.
*   Get the link to your triage report by email.

9.  [**Understand your results**](#understand-your-results)

*   Read about the [triage report](/docs/product/understanding_test_results/reports/).
*   Orient yourself to the [Logs Explorer and multiverse map](/docs/product/understanding_test_results/logs_explorer/).

...



[Access your results](#access-your-results)
-----------------------------------------------------

To check on your test's progress at any time, go to the **Recent runs** page in the web app.

Within an hour of launching your test, you’ll receive an email with a link to a triage report. The email goes to the address you specified in `antithesis.report.recipients`. You can also get results through [Discord and Slack alerts](/docs/product/tooling_integrations/discord_slack/).

You can view the triage report in any of the following ways:
* Click the link in the email.
* Click the **Triage results** button next to the test on the **Recent runs** page.
* Click the **report url** link in the Discord or Slack alert.



[Understand your results](#understand-your-results)
-----------------------------------------------------

We suggest you read how to [understand your results](/docs/product/understanding_test_results/) while you wait for your test to finish! 

The [triage report](/docs/product/understanding_test_results/reports/) provides a high-level overview of your run's results. You can view an [interactive example triage report](/reports/example-triage-report). It contains four sections:
1. The **Environment** section lists container images and configuration used in the test.
2. The **Utilization** section gives you an overview of test length and behavior discovery.
3. The **Findings** section summarizes new, rare, and resolved findings. 
4. The **Properties** section shows pass/fail results for each of your test properties.

### [Explore further with Logs Explorer](#explore-further-with-logs-explorer)

The [Logs Explorer and multiverse map](/docs/product/understanding_test_results/logs_explorer/) give you two more ways to explore your test results. 

The **Logs Explorer** lets you search for events across all the execution paths. Events stream in while the test is still running, so you can start searching before your test finishes.

You can view the Logs Explorer in any one of the following ways:
* Click the **Explore Logs** button on the triage report.
* Click the **Explore Logs** button on the **Recent runs** page.
* Go to the **Logs Explorer** page and select a run.

The **multiverse map** gives you a visual tree overview of all execution paths. You can view it by clicking the **Map** tab above the search results.



[Next steps](#next-steps)
-----------------------------------------------------

Congratulations — you’re now set up with Antithesis!

From here, we suggest:

*   Reading about [how Antithesis works](/docs/introduction/how_antithesis_works) if you haven’t done so yet, to understand some of the core concepts behind Antithesis testing.
*   Trying the [Test Composer tutorial](/docs/getting_started/tutorials/docker_compose/cluster-test/) for a ground-up guide to iterating on your testing.
*   Reading the [SDK docs](/docs/reference/sdk/) to integrate the relevant SDK with your code.

Later on, you’ll probably also want to [configure your CI system](/docs/product/tooling_integrations/ci/) to automate the process of building your software and kicking off webhooks.