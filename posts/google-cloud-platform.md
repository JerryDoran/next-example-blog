---
title: "Getting Geolocation Data from GoogleApi"
date: "January 19, 2023"
excerpt: "Accessing the Google Cloud Console to manage cloud applications"
# cover_image: "/images/posts/img2.jpg"
---

Getting geolocation data from the googleapi to enable google maps in my Next.js project

1. Navigate to [Google Cloud Console](https://console.cloud.google.com)
2. Select your project from the drop down modal.

<figure>
<img src="/images/posts/google-cloud-1.PNG" alt="google-cloud"/>
</figure>
<figure-caption>Figure 1. Dropdown Project Modal</figure-caption>

3. Search for "geocoding" and select the Geocoding API.

<figure>
<img src="/images/posts/google-cloud-2.PNG" alt="google-cloud"/>
</figure>
<figure-caption>Figure 2. Geocoding API Search</figure-caption>

4. If the Geocoding API is not enabled, click Enable. Otherwise it has been enabled.

<figure>
<img src="/images/posts/google-cloud-3.PNG" alt="google-cloud"/>
</figure>
<figure-caption>Figure 3. Geocoding API Overview Screen</figure-caption>

5. After clicking "Manage" or "Enable" you will be directed to Google Maps Platform screen.

<figure>
<img src="/images/posts/google-cloud-4.PNG" alt="google-cloud"/>
</figure>
<figure-caption>Figure 4. Google Maps Platform</figure-caption>

6. Select Credentials on the left sidebar and the following screen will display.

<figure>
<img src="/images/posts/google-cloud-5.PNG" alt="google-cloud"/>
</figure>
<figure-caption>Figure 5. Google Maps Credentials</figure-caption>

7. Select Maps API Key and the API screen will appear. Click to copy your key for your project.

<figure>
<img src="/images/posts/google-cloud-6.PNG" alt="google-cloud"/>
</figure>
<figure-caption>Figure 5. Google Maps API Key</figure-caption>

Back in your project you would usually copy this key to an environmental variable in a .env or .env.local file.
