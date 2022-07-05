# LockBot GitHub action

Essentially a reusable action on top of [lockbot](https://github.com/connorads/lockbot) that can be used to lock an environment.

### Parameters
| Parameters | Required | Description |
| :--- | :-: | :- |
| action | ✅ | `acquire` or `release` |
| env | ✅ | Environment to which we're deploying to |
| endpoint | ✅ | API endpoint (refer to [lockbot](https://github.com/connorads/lockbot) on how to get it) |
| auth_token | ✅ | API auth token (refer to [lockbot](https://github.com/connorads/lockbot) on how to get it) |
| api_owner | ✅ | Slack member ID |
