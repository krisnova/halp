# halp

Pushing iridium communications to the next level.

Halp is a small program that will send push notifications to my unlucky friends in the event of an emergency.

It will run in Kubernetes.

---

Given an iridium communicator like a [Garmin Inreach](https://discover.garmin.com/en-US/inreach/personal/) a `halp` operator can program various responses and integrations in time of emergency. 

The `halp` program will support various alerting modes.

 - E_INCONVENIENCED
 - E_UPSHITCREEK
 - E_COMPLETELYFUCKED

Each mode can be configured with a map of `contacts` to `integration` points running in memory.

# Integrations

Using the [twilio](https://www.twilio.com/docs) API we can have users subscribe to various push notifications of their own liking.


