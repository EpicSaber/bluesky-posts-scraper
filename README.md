[Bluesky Posts Scraper](https://apify.com/scrapestorm/bluesky-posts-scraper?fpr=data)

## Bluesky Posts Scraper - Extract Post Data from Bluesky 🔍

The Bluesky Posts Scraper is a powerful tool designed to extract detailed data from posts on Bluesky. By providing a keyword and specifying the maximum number of posts, you can retrieve the following information for each post:

```
Post URI 🔗: Unique identifier for the post
Post CID 📂: Content identifier for the post
Author DID 🧑‍💻: Decentralized Identifier of the post author
Author Handle 🏷️: Username or handle of the post author
Author Display Name 📛: Full display name of the post author
Author Avatar 🖼️: URL to the author's avatar image
Post Created Time ⏰: The time when the post was created
Post Text ✍️: The content of the post
Post Language 🌍: Languages used in the post
Post Images 🖼️: Thumbnails and full-size images attached to the post
Reply Count 💬: Number of replies to the post
Repost Count 🔄: Number of reposts of the post
Like Count 👍: Number of likes on the post
Quote Count 🗣️: Number of quotes or citations of the post
Post Indexing Time 🗓️: The time when the post was indexed in the system
Post Labels 🏷️: Any labels associated with the post
```

## 🛠️ How to Use the Bluesky Posts Scraper

Input Parameters

To use the Bluesky Posts Scraper, provide the following parameters:

```
{
"keyword": "john",
"maxitems": 60
}
```

- Steps

Enter Data: Provide the keyword and specify the maximum number of posts you want to retrieve.
Start Scraping: Click the "Start" button to begin the scraping process. The tool will search for posts that match the keyword and retrieve the relevant data.
Download Your Data: After extraction, you can download the results in various formats such as JSON, CSV, XML, RSS, or HTML Table.

## Why Scrape Bluesky Posts? ✨🚀

Scraping Bluesky posts is useful for:

```
Content Research 📚: Identifying popular topics, discussions, or influencers related to a specific keyword or hashtag.
Audience Insights 👥: Understanding the engagement patterns and interests of Bluesky users.
Competitive Analysis 🏁: Monitoring the engagement strategies of competitors or industry influencers.
Brand Monitoring 📢: Tracking mentions of your brand or relevant topics across Bluesky.
Trend Discovery 🔍: Discovering emerging trends or viral posts within the Bluesky network.
```

## 💸 Pricing

This scraper operates on a subscription basis at a cost of $17.99/month.

## Related Actors

If you're interested in other YouTube or Facebook scraping solutions, check out these related tools:

- [Facebook Followers & Following Scraper 📊👥](https://apify.com/scrapestorm/facebook-followers-following-scraper)
- [💬 YouTube Comments Scraper](https://apify.com/scrapestorm/youtube-comments-scraper---rental-fast-and-cheap)
- [🏎 YouTube Scraper (By Keyword)](https://apify.com/scrapestorm/youtube)
- [🔴 Youtube Channel Scraper (Rental)](https://apify.com/scrapestorm/youtube-channel-scraper)
- [🌐 Youtube Shorts Scraper 📺 (Rental)](https://apify.com/scrapestorm/youtube-shorts-scraper-rental---fast-cheap)
- [Facebook Ads Library Scraper 🎯📈](https://apify.com/scrapestorm/facebook-ads-library-scraper)
- [Facebook Likes Scraper (Fast & Cheap) 👍 🌟](https://apify.com/scrapestorm/facebook-likes-scraper-fast-cheap)
- [Facebook Shares Scraper (Exclusive & Affordable) 🚀💡](https://apify.com/scrapestorm/facebook-shares-scraper-exclusive-affordable)
- [Facebook Comments Scraper (All-in-One) 💬](https://apify.com/scrapestorm/facebook-comments-scraper-all-in-one)
- [YouTube Transcript Video Scraper 📝 (⚡ Fast & 💸 Cheap)](https://apify.com/scrapestorm/youtube-transcript-videos)
- [Youtube Playlist Scraper 🎵 - Rental (Fast & cheap)](https://apify.com/scrapestorm/youtube-playlist-scraper---rental-fast-cheap)

---

## 🔑 Bluesky Posts Scraper Input Format

To use the Bluesky Posts Scraper, provide the following parameters:

```
{
    "keyword": "john",
    "maxitems": 60
}
```

## 📊 Bluesky Posts Scraper Data Output

The Bluesky Posts Scraper will extract the following information for each post and store it in the dataset:

Example output:

```
[
    {
        "uri": "at://did:plc:cnpe7qvcyjrhm6w7w7e4atur/app.bsky.feed.post/3lklpliaiwc25",
        "cid": "bafyreidqna6oqol642ws5bt4dbo7kkjy3utdc52qmkjwiey4fjiibsztc4",
        "author": {
            "did": "did:plc:cnpe7qvcyjrhm6w7w7e4atur",
            "handle": "kevinmkruse.bsky.social",
            "displayName": "Kevin M. Kruse",
            "avatar": "https://cdn.bsky.app/img/avatar/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreid7tqojotcpkaoljdayyrm3ngygep5mkkolxakjaagwx3lolvycv4@jpeg",
            "createdAt": "2023-04-29T20:34:46.513Z"
        },
        "record": {
            "createdAt": "2025-03-17T17:47:47.832Z",
            "text": "CIA Director John Ratcliffe is the Archer",
            "langs": [
                "en"
            ]
        },
        "embed": {
            "$type": "app.bsky.embed.images#view",
            "images": [
                {
                    "thumb": "https://cdn.bsky.app/img/feed_thumbnail/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreigkcqrveohg4ma7vxjmnnanswwhdu36qpixgxta75gphcjei7vf7q@jpeg",
                    "fullsize": "https://cdn.bsky.app/img/feed_fullsize/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreigkcqrveohg4ma7vxjmnnanswwhdu36qpixgxta75gphcjei7vf7q@jpeg",
                    "alt": "",
                    "aspectRatio": {
                        "height": 450,
                        "width": 438
                    }
                },
                {
                    "thumb": "https://cdn.bsky.app/img/feed_thumbnail/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreiavnv66bb4egdyq44wsoxjc75lttyf262myjruicmyehd7hp72ada@jpeg",
                    "fullsize": "https://cdn.bsky.app/img/feed_fullsize/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreiavnv66bb4egdyq44wsoxjc75lttyf262myjruicmyehd7hp72ada@jpeg",
                    "alt": "",
                    "aspectRatio": {
                        "height": 570,
                        "width": 656
                    }
                }
            ]
        },
        "replyCount": 5,
        "repostCount": 5,
        "likeCount": 112,
        "quoteCount": 0,
        "indexedAt": "2025-03-17T17:47:49.454Z",
        "labels": []
    },
    {
        "uri": "at://did:plc:cnpe7qvcyjrhm6w7w7e4atur/app.bsky.feed.post/3lklpliaiwc26",
        "cid": "bafyreidqna6oqol642ws5bt4dbo7kkjy3utdc52qmkjwiey4fjiibsztc5",
        "author": {
            "did": "did:plc:cnpe7qvcyjrhm6w7w7e4atur",
            "handle": "johndoe.bsky.social",
            "displayName": "John Doe",
            "avatar": "https://cdn.bsky.app/img/avatar/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreid7tqojotcpkaoljdayyrm3ngygep5mkkolxakjaagwx3lolvycv5@jpeg",
            "createdAt": "2023-05-10T20:34:46.513Z"
        },
        "record": {
            "createdAt": "2025-03-17T18:00:10.832Z",
            "text": "John Doe discusses new trends in AI.",
            "langs": [
                "en"
            ]
        },
        "embed": {
            "$type": "app.bsky.embed.images#view",
            "images": [
                {
                    "thumb": "https://cdn.bsky.app/img/feed_thumbnail/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreigkcqrveohg4ma7vxjmnnanswwhdu36qpixgxta75gphcjei7vf8q@jpeg",
                    "fullsize": "https://cdn.bsky.app/img/feed_fullsize/plain/did:plc:cnpe7qvcyjrhm6w7w7e4atur/bafkreigkcqrveohg4ma7vxjmnnanswwhdu36qpixgxta75gphcjei7vf8q@jpeg",
                    "alt": "",
                    "aspectRatio": {
                        "height": 450,
                        "width": 438
                    }
                }
            ]
        },
        "replyCount": 3,
        "repostCount": 2,
        "likeCount": 75,
        "quoteCount": 1,
        "indexedAt": "2025-03-17T18:00:12.454Z",
        "labels": []
    }
]
```

## 📫 Support

🌟 Leave us a 5 star if you are satisfied with the product!
🌍 For any questions, specific needs, or issues, please reach out through Apify's platform or via email
[Storm_Scraper 🌪️🌩️](https://apify.com/scrapestorm)