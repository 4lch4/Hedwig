# Hedwig TODO List

This is gonna take some time to implement just due to the sheer size of the Twitter API. [Here is][2] a link to the API Reference Index that serves as a good starting point for all of the available endpoints.

## Models/Objects

* [ ] [Tweet][3]
* [ ] [User][4]
* [ ] [Entities][5]
* [ ] [Extended Entities][6]
* [ ] [Geo][7]

## Endpoints

### [Accounts and Users][0]

* [ ] Create & Manage Lists
  * [ ] **GET** ➥ `lists/list`
  * [ ] **GET** ➥ `lists/members`
  * [ ] **GET** ➥ `lists/members/show`
  * [ ] **GET** ➥ `lists/memberships`
  * [ ] **GET** ➥ `lists/ownerships`
  * [ ] **GET** ➥ `lists/show`
  * [ ] **GET** ➥ `lists/statuses`
  * [ ] **GET** ➥ `lists/subscribers`
  * [ ] **GET** ➥ `lists/subscribers/show`
  * [ ] **GET** ➥ `lists/subscriptions`
  * [ ] **POST** ➥ `lists/create`
  * [ ] **POST** ➥ `lists/destroy`
  * [ ] **POST** ➥ `lists/members/create`
  * [ ] **POST** ➥ `lists/members/create_all`
  * [ ] **POST** ➥ `lists/members/destroy`
  * [ ] **POST** ➥ `lists/destroy_all`
  * [ ] **POST** ➥ `lists/subscribers/create`
  * [ ] **POST** ➥ `lists/subscribers/destroy`
  * [ ] **POST** ➥ `lists/update`
* [ ] Follow, Search, & Get Users
  * [ ] **GET** ➥ `followers/ids`
  * [ ] **GET** ➥ `followers/list`
  * [ ] **GET** ➥ `friends/ids`
  * [ ] **GET** ➥ `friends/list`
  * [ ] **GET** ➥ `friendships/incoming`
  * [ ] **GET** ➥ `friendships/lookup`
  * [ ] **GET** ➥ `friendships/no_retweets/ids`
  * [ ] **GET** ➥ `friendships/outgoing`
  * [ ] **GET** ➥ `friendships/show`
  * [ ] **GET** ➥ `users/lookup`
  * [ ] **GET** ➥ `users/search`
  * [ ] **GET** ➥ `users/show`
  * [ ] **POST** ➥ `friendships/create`
  * [ ] **POST** ➥ `friendships/destroy`
  * [ ] **POST** ➥ `friendships/update`
* [ ] Manage Account Settings & Profile
  * [ ] **GET** ➥ `account/settings`
  * [ ] **GET** ➥ `account/verify_credentials`
  * [ ] **GET** ➥ `saved_searches/list`
  * [ ] **GET** ➥ `saved_searches/show/:id`
  * [ ] **GET** ➥ `users/profile_banner`
  * [ ] **POST** ➥ `account/remove_profile_banner`
  * [ ] **POST** ➥ `account/settings`
  * [ ] **POST** ➥ `account/update_profile`
  * [ ] **POST** ➥ `account/update_profile_banner`
  * [ ] **POST** ➥ `account/update_profile_image`
  * [ ] **POST** ➥ `saved_searches/create`
  * [ ] **POST** ➥ `saved_searches/destroy/:id`
* [ ] Mute, Block, & Report Users
  * [ ] **GET** ➥ `blocks/ids`
  * [ ] **GET** ➥ `blocks/list`
  * [ ] **GET** ➥ `mutes/users/ids`
  * [ ] **GET** ➥ `mutes/users/list`
  * [ ] **POST** ➥ `blocks/create`
  * [ ] **POST** ➥ `blocks/destroy`
  * [ ] **POST** ➥ `mutes/users/create`
  * [ ] **POST** ➥ `mutes/users/destroy`
  * [ ] **POST** ➥ `users/report_spam`

### [Tweets][1]

* [ ] Curate a Collection of Tweets
  * [ ] **GET** ➥ `collections/entries`
  * [ ] **GET** ➥ `collections/list`
  * [ ] **GET** ➥ `collections/show`
  * [ ] **POST** ➥ `collections/create`
  * [ ] **POST** ➥ `collections/destroy`
  * [ ] **POST** ➥ `collections/entries/add`
  * [ ] **POST** ➥ `collections/entries/curate`
  * [ ] **POST** ➥ `collections/entries/move`
  * [ ] **POST** ➥ `collections/entries/remove`
  * [ ] **POST** ➥ `collections/update`
* [ ] Filter Realtime Tweets
  * [ ] **POST** ➥ `statuses/filter`
* [ ] Get Tweet Timelines
  * [ ] **GET** ➥ `statuses/home_timeline`
  * [ ] **GET** ➥ `statuses/mentions_timeline`
  * [ ] **GET** ➥ `statuses/user_timeline`
* [ ] Post, Retrieve, & Engage w/ Tweets
  * [ ] **GET** ➥ `favorites/list`
  * [ ] **GET** ➥ `statuses/lookup`
  * [ ] **GET** ➥ `statuses/oembed`
  * [ ] **GET** ➥ `statuses/retweeters/ids`
  * [ ] **GET** ➥ `statuses/retweets/:id`
  * [ ] **GET** ➥ `statuses/retweets_of_me`
  * [ ] **GET** ➥ `statuses/show/:id`
  * [ ] **POST** ➥ `favorites/create`
  * [ ] **POST** ➥ `favorites/destroy`
  * [ ] **POST** ➥ `statuses/destroy/:id`
  * [ ] **POST** ➥ `statuses/retweet/:id`
  * [ ] **POST** ➥ `statuses/unretweet/:id`
  * [ ] **POST** ➥ `statuses/update`
* [ ] Sample Realtime Tweets
  * [ ] **GET** ➥ `statuses/sample`

[0]: file:///c%3A/Users/jisodl0/Development/Node.js/Hedwig/src/endpoints/AccountsAndUsers.js
[1]: file:///c%3A/Users/jisodl0/Development/Node.js/Hedwig/src/endpoints/Tweets.js
[2]: https://developer.twitter.com/en/docs/api-reference-index
[3]: https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/tweet-object
[4]: https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/user-object
[5]: https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/entities-object
[6]: https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/extended-entities-object
[7]: https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/geo-objects
