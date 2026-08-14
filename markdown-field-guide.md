# Coastal Survey Field Guide

A short handbook for volunteers recording shoreline conditions. Read it before
your first survey, and keep a copy in your field bag.

## Before you go

Check the tide table for your site and plan to arrive **thirty minutes** before
low tide. Surveys run *rain or shine*, but lightning cancels everything.

Bring the following:

- A charged phone with the survey app installed
  - A battery pack, for a full day in the field
- Waterproof boots and gloves
- The site map, printed at full size
- A one-metre quadrat frame

![Quadrat frame placed on cobble](images/quadrat.png)

### Recording a transect

Walk the transect from the high-water mark toward the sea, stopping every five
metres. At each stop:

1. Photograph the quadrat from directly above.
2. Count every organism inside the frame.
3. Note the substrate as sand, cobble, or bedrock.
4. Record the time to the nearest minute.

Do not guess. An unrecorded stop is worth more than an invented one.

> Survey data is only as good as its worst observation. When you cannot identify
> a species, photograph it and mark the entry as unconfirmed.

## Uploading your data

Connect to wifi before opening the app, then press the `Sync` button. The app
writes one JSON record per stop:

```
{"transect": 4, "stop": 3, "substrate": "cobble", "count": 17}
```

If the upload fails, the records stay on your phone until the next sync. Never
delete the app while unsynced records are on it.

Questions go to the [volunteer coordinator](https://example.org/coastal/contact),
who answers within two working days.

## Common mistakes

Volunteers most often mis**count** barnacles, which cluster densely enough that a
tally counter is worth carrying. The second most common error is recording the
_wrong transect number_ after a break.

Reporting problems
------------------

If the app crashes, note what you were doing and send the crash log from the
settings screen. Do not reinstall the app first: reinstalling discards the
records that have not yet been uploaded.

---

Revised for the 2026 season.
