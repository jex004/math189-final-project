# MATH 189 Final Project

## Description
Social media now serves as the medium through which most individuals access the news and obtain new information, making it a common and effective channel for political advertising. As these platforms become increasingly saturated with content, it is vital that both activists and politicians are strategic about their marketing methods. It’s of the utmost importance to identify a target demographic in order to know which language and buzzwords will be the most engaging and thus, have the highest returns. By analyzing how political advertisements and target audiences change over time, we can better learn how to create an impactful and eye-catching ad. 

When a campaign chooses a particular buzzword, they’re not just picking any term. Instead, they’re trying to signal an identity or a set of values that resonates with a specific group of people. This project will help us see how word choices have evolved over time as well as provide insights into the political climate and its development over time too. In this way, we can better comprehend how digital spaces are being used to influence anything from smaller social movements to major elections. Such insights also promote greater awareness of marketing strategies enabling us to make better informed decisions that are less influenced by campaign strategy.

Thus, we want to investigate the following questions:

Do the buzzwords utilized by political ads on Facebook remain stable from 2019 to the present? Additionally, does that trend remain the same for all demographics or do ads targeting different demographics exhibit different patterns in how much the buzzwords they use change over time?

## Column Metadata
| Column | Type | Description |
|---|---|---|
| `id` | int | Unique identifier for the ad |
| `ad_creation_time` | datetime | When the ad was created |
| `ad_delivery_start_time` | datetime | When the ad began delivery |
| `bylines` | string | Attribution/byline for the ad |
| `currency` | string | Currency used for spend values |
| `page_id` | int | Unique identifier for the Facebook page |
| `page_name` | string | Name of the Facebook page |
| `ad_creative_bodies` | string | Main body text of the ad creative |
| `ad_creative_link_captions` | string | Caption text for linked content |
| `ad_creative_link_descriptions` | string | Description text for linked content |
| `ad_creative_link_titles` | string | Title text for linked content |
| `audience_size_lower` | int | Lower bound of estimated audience size |
| `impressions_lower` | int | Lower bound of ad impressions |
| `impressions_upper` | float | Upper bound of ad impressions |
| `spend_lower` | int | Lower bound of amount spent |
| `spend_upper` | float | Upper bound of amount spent |
| `ad_snapshot_url` | string | URL to the ad snapshot |
| `language_<lang>` | bool | Whether the ad contained <lang> as a language |
| `platform_<pf>` | bool | Whether the ad was on <pf> |
| `<age range>/<gender>` | float | Percentage (%) of <age range> and <gender> demographic in the audience |