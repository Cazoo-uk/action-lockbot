# LockBot GitHub action

Essentially a reusable action on top of [lockbot](https://github.com/connorads/lockbot) that can be used to lock an environment.

### Defaults
| Parameters | Required | Description |
| :--- | :-: | :- |
| env | ✅ | Environment to which we're deploying to |
| lockbot_endpoint | ✅ | API endpoint (refer to [lockbot](https://github.com/connorads/lockbot) on how to get it) |
| lockbot_auth_token | ✅ | API auth token (refer to [lockbot](https://github.com/connorads/lockbot) on how to get it) |
| lockbot_api_owner | ✅ | Slack member ID |
