<a name="1.0.0"></a>

# 1.0.0 (2020-03-19)

To infinity and beyond 🚀

### Features

- update dependencies

<a name="1.0.0-beta.5"></a>

# 1.0.0-beta.5 (2019-12-04)

### Features

- Firebase can't redirect subdomain to path, therefore use `deckdeckgo.com/poll` instead of `poll.deckdeckgo.com`

<a name="1.0.0-beta.4"></a>

# 1.0.0-beta.4 (2019-12-01)

### Breaking Changes

- update the poll displayed in the remote with the values of the deck (after the answers have been cast)
- `answeredOnce` as state

<a name="1.0.0-beta.3"></a>

# 1.0.0-beta.3 (2019-12-01)

### Features

- expose `answeredOnce` as an attribute to sync the information between deck and remote

### Breaking Changes

- event `pollConnected` replaced by event `pollUpdated` triggered on each component updated

<a name="1.0.0-beta.2"></a>

# 1.0.0-beta.2 (2019-12-01)

### Features

- remove RxJS and use callbacks instead

<a name="1.0.0-beta.1-1"></a>

# 1.0.0-beta.1-1 (2019-11-30)

### Features

- add a CSS variable for the `font-size` of the slot `how-to`

<a name="1.0.0-beta.1"></a>

# 1.0.0-beta.1 (2019-11-30)

### Features

- interact with your audience with this new `poll` template ([#471](https://github.com/deckgo/deckdeckgo/issues/471))
