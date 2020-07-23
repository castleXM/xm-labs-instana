# Instana

This integration allows you to alert users in xMatters from an alert in Instana.


---------

<kbd>
<a href="https://support.xmatters.com/hc/en-us/community/topics">
   <img src="https://github.com/xmatters/xMatters-Labs/raw/master/media/disclaimer.png">
</a>
</kbd>

---------

# Files

* [Instana.zip](Instana.zip) - Workflow zip file with the step and example flow
* [instana.png](/instana.png) - Instana logo


# Installation

## xMatters Setup
1. Download the [Instana.zip](Instana.zip) file onto your local computer
2. Navigate to the Workflows tab of your xMatters instance
3. Click Import, and select the zip file you just downloaded
4. Copy the URL from the **Inbound from Instana** Step inside the **Alert** flow.
5. Adjust the recipients in the **Create Event - Alert** step.


## Instana Setup
1. Go to **Settings > Alert Channels**
2. Add a new alert channel of type webhook.
3. Name it xMatters or something that helps you identify it.
4. Take the link copied from **Step 4** of the xMatters setup instructions and put it in the Webhook URL field.
5. (Optional) Click the **Test Channel** button and see if anything comes through in the Activity Log of the flow in xMatters. This can be useful for troubleshooting in case of any issues later.
6. This alert channel can now be used to trigger xMatters when creating alerts in Instana.


## Example
This is the provided flow in the integration.

<kbd>
	<img src="/media/ExampleFlow.png">
</kbd>

