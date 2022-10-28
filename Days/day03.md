---
title: '#30DaysforGoogleCloud - Cloud Storage 3'
published: true
description: 30DaysforGoogleCloud - Introduction
tags: 'GCP, Cloud, IaaS, PaaS, SaaS, GoogleCloud, Storageon Cloud'
cover_image: null
canonical_url: null
id: 
date: '28-Oct-2022'
---

## Cloud Storage - Day 3

Cloud Storage allows world-wide storage and retrieval of any amount of data at any time. You can use Cloud Storage for a range of scenarios including serving website content, storing data for archival and disaster recovery, or distributing large data objects to users via direct download.

Create a bucket
In the Cloud Console, go to Navigation menu > Cloud Storage > Buckets. Click CREATE BUCKET.

Name your bucket: Enter a unique name for your bucket.

Bucket naming rules:

Do not include sensitive information in the bucket name, because the bucket namespace is global and publicly visible.

Bucket names must contain only lowercase letters, numbers, dashes (-), underscores (_), and dots (.). Names containing dots require verification.

Bucket names must start and end with a number or letter.

Bucket names must contain 3 to 63 characters. Names containing dots can contain up to 222 characters, but each dot-separated component can be no longer than 63 characters.

Bucket names cannot be represented as an IP address in dotted-decimal notation (for example, 192.168.5.4).

Bucket names cannot begin with the "goog" prefix.

Bucket names cannot contain "google" or close misspellings of "google".

Also, for DNS compliance and future compatibility, you should not use underscores (_) or have a period adjacent to another period or dash. For example, ".." or "-." or ".-" are not valid in DNS names.

Click CONTINUE.

Set Location type to Multi-region.

Set Location to us (multiple regions in United States)

Click CONTINUE.

Set Default Storage class to Standard.

Click CONTINUE.

If needed, uncheck Enforce public access prevention on this bucket under Prevent public access.

Select Fine-grained under Access Control.

Click CONTINUE.

Scroll to the bottom and click CREATE.

That's it — you've just created a Cloud Storage bucket!







## Resources

I am always open to adding additional resources to these readme files as it is here as a learning tool.

My advice is to watch all of the below and hopefully you have also picked something up from the text and explanations above.

- [Cloud in 5 Minute](https://www.youtube.com/watch?v=M988_fsOSWo)
- [What is the Google Cloud](https://www.youtube.com/watch?v=kzKFuHk8ovk)
- [Google Cloud Path](https://www.youtube.com/watch?v=JbQc_8-rVt4)

If you made it this far, then you will know if this is where you want to be or not. See you on [Day 2](day02.md).