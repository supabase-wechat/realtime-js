# `realtime-js` - [Wechat Miniprogram](https://developers.weixin.qq.com/miniprogram/dev/framework/) compatible

Forked from supabase/realtime-js, the origional documentation can be found [here](https://github.com/supabase/realtime-js).

## Usage

As it serves only as a submodule and workspace dependency in [supabase-wechat/supabase-js](https://github.com/supabase-wechat/supabase-js), there will be no independent builds out of this repository.

## Major changes

### Background

<https://github.com/orgs/supabase/discussions/30361>

### Changes

Before this change is officially confirmed valid, apply this change in this fork

- add missing `setupConnection()` when using custom `transport` in `RealtimeClient`
