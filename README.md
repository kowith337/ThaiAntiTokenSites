# ThaiAntiTokenSites

**Formerly: AntiPumpSites on [PasteBin](http://pastebin.com/etRKNtD4)**

A filter that only compatible for [uBlock](https://github.com/gorhill/uBlock) because it have ability to **prevent users to view sites that listed in filter**, unless you temporary disable rules. (and you will see those sites will not fully load because of `$important` rules)

This filter has listed to block sites that know to trick and gain [**Facebook access token**](https://www.facebook.com/help/524275404355719) from users that they offer you to boost likes, followers, comments, post shares, etc.

Most Facebook users don't know much about access token and can be easily to get tricked, admin of those sites will store tokens and then use to earn benefits for themselves by using your access to like posts or pages, follow many users or lists, comments on posts, share posts and more.

**Repeat**: This only work with uBlock and it doesn't (fully) protect you if you had gave token for those sites before.

If you're currently in trouble about that, Go to [Facebook Apps Settings](https://www.facebook.com/settings?tab=applications) and then try to delete suspicious apps logins, or completely reset platform by turn it off and then turn it on again.

- - - - -

[Subscribe](https://subscribe.adblockplus.org/?location=https://github.com/kowith337/ThaiAntiTokenSites/raw/master/AntiPumpSites.txt&title=Thai%20AntiToken%20Sites) or copy [Direct Link](https://github.com/kowith337/ThaiAntiTokenSites/raw/master/AntiPumpSites.txt) *if subscription link doesn't work* and parse in uBlock Origin.

**Note**: ABP subscription link can added this list on uBlock only because this filter have no `[AdBlock Plus]` compatibility header.

- - - - -

**Bonus for uMatrix users.**
You can parse [hosts file](https://github.com/kowith337/ThaiAntiTokenSites/blob/master/AntiPumpSites_hosts.txt) to apply in uMatrix, It's good for double protection.
> **Note**
> - Items in this filter are added manually, thats mean no checksum generate and can't predict about how frequently to be update.
> - This filter is mainly to block known access token theft sites in Thailand.
> - You can use [*Issues*](https://github.com/kowith337/ThaiAntiTokenSites/issues) to report those sites, I will be check and update lists if needed.
