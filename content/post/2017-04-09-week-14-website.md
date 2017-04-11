+++
date = "2017-04-09T17:27:30-05:00"
categories = []
keywords = []
description = ""
title = "Week 14: Website Development"

+++
After two long weeks, the production-ready **[modulogeek.com](https://modulogeek.com)** website is complete!

{{< figure src="https://lh3.googleusercontent.com/hfDxE8MkdQQq8cZRp_q9lgdqNmi0Bfvb6RsbrN1HXW1IprDyldXztyMFxeSROtPDIC6KQEYuYTsDkoKOkkH7Zi81KgwvcGeRluH7C_xEBg8lBAGny4gc0xIgI7KgZXrQBmyRxzQf--md6txcKHvTg2fmpjpl0Ac4T1yqNHs_cghz6HmPuUBfjG4mWffd6L8jbh8baIMORvcvdqQBo5t9d3mnxd6wgNPk4IR-6JI7s-iXI09iVHrMA_waPwB7EZeoyJQJMn7MFqasOkR73qQt20pTDLtI7kZ9pkzBosFC4h4YY7swihp8G1wsNheacOlnzyv7pYerhxOsM_LppPgF47gXwxyYhnLtp2Kk4rocx3QVBRU5uUKSsiGppm2VMHjRcd_GN1MqVWvv57L_F7LClTqf39z5hcIQt05EvksIx2818X73WuHv1xW6t0gJlUHEMRtWGXy6k3rXhq6uCvNMMsRaHhjYXLzNSEQJtaQL2s4rXGQRUZweOiWkR6Q6v5gfZ32nPjPT-EUkkierkaonTMtm1y9Vc3_ox42NQW_kWKfSO0gK8ufk3uMMgnUnxs4YDq1uPx1pgjfObsou1JhqhRkKlIiks31XqnY8e7W_ja_SYB3HGpznAw1Ef2lWqQ8jyn9j2h73M7wJlHqCRO3AvgNpru9J7nGsOC6C98_ZhQ=w1216-h974-no" link="https://modulogeek.com" >}}

This was created with [Hugo](https://gohugo.io) and with the [Creative theme](https://themes.gohugo.io/creative/). And a very big thanks to Google Chrome's developer tools: it is quite a godsend. My work would have been magnitudes harder if not for this nifty invention!

The site is also hosted using what I call "future tech" (cos I am old and this new way of hosting is novel to me). It is now fully hosted under [Amazon Web Services](https://aws.amazon.com) (AWS), using [S3](https://aws.amazon.com/s3) as the storage for the files, [Cloudfront](https://aws.amazon.com/cloudfront) as the content delivery network (CDN), and [Route 53](https://aws.amazon.com/route53) for DNS hosting. I've just started using the AWS CLI to sync the files to S3, and I can see the huge scripting/automation potential of having all aspects of my AWS services controllable via this tool.

And, as is customary, I have put up the Hugo source on github: [hugo-modulogeek-com](https://github.com/pirxthepilot/hugo-modulogeek-com)
