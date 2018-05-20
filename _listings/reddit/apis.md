---
name: Reddit
x-slug: reddit
description: Reddit /??r??d?t/, stylized as reddit, is an entertainment, social networking
  service and news website where registered community members can submit content,
  such as text posts or direct links. Only registered users can then vote submissions
  up or down to organize the posts and determine their position on the sites pages.
  Content entries are organized by areas of interest called subreddits.
image: http://www.redditstatic.com/about/assets/reddit-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: About
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/apis.md
specificationVersion: "0.14"
apis:
- name: Reddit Get Subreddit About Log
  x-api-slug: reddit
  description: Get a list of recent moderation actions.
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com///{/r/subreddit}/about/log
  tags: Subreddit, About, Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutlog-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutlog-getnbsp-openapi.md
- name: Reddit Get Subreddit About Location
  x-api-slug: reddit
  description: Return a listing of posts relevant to moderators.
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com///{/r/subreddit}/about/location
  tags: Subreddit, About, Location
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutlocation-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutlocation-getnbsp-openapi.md
- name: Reddit Get Subreddit About Where
  x-api-slug: reddit
  description: This endpoint is a listing.
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com///{/r/subreddit}/about/where
  tags: Subreddit, About, Where
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutwhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutwhere-getnbsp-openapi.md
- name: Reddit Get Subreddit About
  x-api-slug: reddit
  description: Return information about the subreddit.
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////r/subreddit/about
  tags: Subreddit, About
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditabout-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditabout-getnbsp-openapi.md
- name: Reddit Get Subreddit About Edit
  x-api-slug: reddit
  description: Get the current settings of a subreddit.
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////r/subreddit/about/edit
  tags: Subreddit, About, Edit
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutedit-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutedit-getnbsp-openapi.md
- name: Reddit Get Subreddit About Rules
  x-api-slug: reddit
  description: Get the rules for the current subreddit
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////r/subreddit/about/rules
  tags: Subreddit, About, Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditaboutrules-getnbsp-openapi.md
- name: Reddit Get Subreddit About Traffic
  x-api-slug: reddit
  description: Get the traffic for the current subreddit
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////r/subreddit/about/traffic
  tags: Subreddit, About, Traffic
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/rsubredditabouttraffic-getnbsp-openapi.md
- name: Reddit
  x-api-slug: reddit
  description: Reddit /??r??d?t/, stylized as reddit, is an entertainment, social
    networking service and news website where registered community members can submit
    content, such as text posts or direct links. Only registered users can then vote
    submissions up or down to organize the posts and determine their position on the
    sites pages. Content entries are organized by areas of interest called subreddits.
  image: http://www.redditstatic.com/about/assets/reddit-logo.png
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: About
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/about/master/_listings/reddit/openapi.md
x-common:
- type: x-authentication
  url: https://github.com/reddit/reddit/wiki/OAuth2
- type: x-base
  url: https://www.reddit.com/
- type: x-best-practices
  url: https://github.com/reddit/reddit/wiki/API
- type: x-blog
  url: http://www.redditblog.com/
- type: x-blog-rss
  url: https://www.reddit.com/r/datasets/.rss
- type: x-blog-rss
  url: http://www.redditblog.com/feeds/posts/default?alt=rss
- type: x-code-libraries
  url: https://github.com/reddit/reddit/wiki/API-Wrappers
- type: x-console
  url: https://apigee.com/console/reddit
- type: x-developer
  url: http://www.reddit.com/dev/api
- type: x-github
  url: https://github.com/reddit
- type: x-privacy
  url: https://www.reddit.com/help/privacypolicy
- type: x-security
  url: https://www.reddit.com/help/privacypolicy#section_security
- type: x-support
  url: https://www.reddit.com/contact/
- type: x-terms-of-service
  url: http://www.reddit.com/help/useragreement
- type: x-transparency-report
  url: https://www.reddit.com/wiki/transparency
- type: x-twitter
  url: https://twitter.com/reddit
- type: x-website
  url: http://www.reddit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---