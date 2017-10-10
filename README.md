Github Trending Api 文档
-----------

### 域名： https://python.0x2048.com



### 1. 获取 Trending 列表

#### 接口功能

> 指定时间和语言获取 Github Trending 的所有数据

#### URL

> [v1/trending?since=daily&language=java](https://python.0x2048.com/v1/trending?since=daily&language=java)

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数

|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|since |ture |string|trending 的类型，如 daily、week |
|language |false |int |请求的语言|

#### 返回字段

|返回字段|字段类型|说明 |
|:----- |:------|:----------------------------- |
|id | int |返回结果状态。0：正常；1：错误。 |
| name | string | 仓库名 |
| full_name | string | 用户名/仓库名 |

其余字段参考示例

#### 接口示例

> 地址：[https://python.0x2048.com/v1/trending?since=daily&language=java](https://python.0x2048.com/v1/trending?since=daily&language=java)


```json
[
    {
        "id": 105440603, 
        "name": "ScalingLayout", 
        "full_name": "iammert/ScalingLayout", 
        "owner": {
            "login": "iammert", 
            "id": 11799296, 
            "avatar_url": "https://avatars3.githubusercontent.com/u/11799296?v=4", 
            "gravatar_id": "", 
            "url": "https://api.github.com/users/iammert", 
            "html_url": "https://github.com/iammert", 
            "followers_url": "https://api.github.com/users/iammert/followers", 
            "following_url": "https://api.github.com/users/iammert/following{/other_user}", 
            "gists_url": "https://api.github.com/users/iammert/gists{/gist_id}", 
            "starred_url": "https://api.github.com/users/iammert/starred{/owner}{/repo}", 
            "subscriptions_url": "https://api.github.com/users/iammert/subscriptions", 
            "organizations_url": "https://api.github.com/users/iammert/orgs", 
            "repos_url": "https://api.github.com/users/iammert/repos", 
            "events_url": "https://api.github.com/users/iammert/events{/privacy}", 
            "received_events_url": "https://api.github.com/users/iammert/received_events", 
            "type": "User", 
            "site_admin": false
        }, 
        "private": false, 
        "html_url": "https://github.com/iammert/ScalingLayout", 
        "description": "With Scaling Layout scale your layout on user interaction.", 
        "fork": false, 
        "url": "https://api.github.com/repos/iammert/ScalingLayout", 
        "forks_url": "https://api.github.com/repos/iammert/ScalingLayout/forks", 
        "keys_url": "https://api.github.com/repos/iammert/ScalingLayout/keys{/key_id}", 
        "collaborators_url": "https://api.github.com/repos/iammert/ScalingLayout/collaborators{/collaborator}", 
        "teams_url": "https://api.github.com/repos/iammert/ScalingLayout/teams", 
        "hooks_url": "https://api.github.com/repos/iammert/ScalingLayout/hooks", 
        "issue_events_url": "https://api.github.com/repos/iammert/ScalingLayout/issues/events{/number}", 
        "events_url": "https://api.github.com/repos/iammert/ScalingLayout/events", 
        "assignees_url": "https://api.github.com/repos/iammert/ScalingLayout/assignees{/user}", 
        "branches_url": "https://api.github.com/repos/iammert/ScalingLayout/branches{/branch}", 
        "tags_url": "https://api.github.com/repos/iammert/ScalingLayout/tags", 
        "blobs_url": "https://api.github.com/repos/iammert/ScalingLayout/git/blobs{/sha}", 
        "git_tags_url": "https://api.github.com/repos/iammert/ScalingLayout/git/tags{/sha}", 
        "git_refs_url": "https://api.github.com/repos/iammert/ScalingLayout/git/refs{/sha}", 
        "trees_url": "https://api.github.com/repos/iammert/ScalingLayout/git/trees{/sha}", 
        "statuses_url": "https://api.github.com/repos/iammert/ScalingLayout/statuses/{sha}", 
        "languages_url": "https://api.github.com/repos/iammert/ScalingLayout/languages", 
        "stargazers_url": "https://api.github.com/repos/iammert/ScalingLayout/stargazers", 
        "contributors_url": "https://api.github.com/repos/iammert/ScalingLayout/contributors", 
        "subscribers_url": "https://api.github.com/repos/iammert/ScalingLayout/subscribers", 
        "subscription_url": "https://api.github.com/repos/iammert/ScalingLayout/subscription", 
        "commits_url": "https://api.github.com/repos/iammert/ScalingLayout/commits{/sha}", 
        "git_commits_url": "https://api.github.com/repos/iammert/ScalingLayout/git/commits{/sha}", 
        "comments_url": "https://api.github.com/repos/iammert/ScalingLayout/comments{/number}", 
        "issue_comment_url": "https://api.github.com/repos/iammert/ScalingLayout/issues/comments{/number}", 
        "contents_url": "https://api.github.com/repos/iammert/ScalingLayout/contents/{+path}", 
        "compare_url": "https://api.github.com/repos/iammert/ScalingLayout/compare/{base}...{head}", 
        "merges_url": "https://api.github.com/repos/iammert/ScalingLayout/merges", 
        "archive_url": "https://api.github.com/repos/iammert/ScalingLayout/{archive_format}{/ref}", 
        "downloads_url": "https://api.github.com/repos/iammert/ScalingLayout/downloads", 
        "issues_url": "https://api.github.com/repos/iammert/ScalingLayout/issues{/number}", 
        "pulls_url": "https://api.github.com/repos/iammert/ScalingLayout/pulls{/number}", 
        "milestones_url": "https://api.github.com/repos/iammert/ScalingLayout/milestones{/number}", 
        "notifications_url": "https://api.github.com/repos/iammert/ScalingLayout/notifications{?since,all,participating}", 
        "labels_url": "https://api.github.com/repos/iammert/ScalingLayout/labels{/name}", 
        "releases_url": "https://api.github.com/repos/iammert/ScalingLayout/releases{/id}", 
        "deployments_url": "https://api.github.com/repos/iammert/ScalingLayout/deployments", 
        "created_at": "2017-10-01T12:28:34Z", 
        "updated_at": "2017-10-09T05:02:08Z", 
        "pushed_at": "2017-10-02T15:12:03Z", 
        "git_url": "git://github.com/iammert/ScalingLayout.git", 
        "ssh_url": "git@github.com:iammert/ScalingLayout.git", 
        "clone_url": "https://github.com/iammert/ScalingLayout.git", 
        "svn_url": "https://github.com/iammert/ScalingLayout", 
        "homepage": null, 
        "size": 8348, 
        "stargazers_count": 899, 
        "watchers_count": 899, 
        "language": "Java", 
        "has_issues": true, 
        "has_projects": true, 
        "has_downloads": true, 
        "has_wiki": true, 
        "has_pages": false, 
        "forks_count": 68, 
        "mirror_url": null, 
        "open_issues_count": 1, 
        "forks": 68, 
        "open_issues": 1, 
        "watchers": 899, 
        "default_branch": "master", 
        "network_count": 68, 
        "subscribers_count": 23
    }, 
    {}
    ]
```

### 2. 登录 Github

#### 接口功能

> 指定用户名和密码进行 Github 登录

#### URL

> /v1/login

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数

|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|username |t |string|用户名 |
|password |t |string |密码|

#### 返回字段

|返回字段|字段类型|说明 |
|:----- |:------|:----------------------------- |
| fuck_username | string | 登录成功用户的 Token |
| user | string | 用户名 |
| avatar | string | 头像链接 |


#### 接口示例

> 地址：[https://python.0x2048.com/v1/login?username=xiyouMc&password=test](https://python.0x2048.com/v1/login?username=xiyouMc&password=test)

```json
{
    "fuck_username": "aaaaaa", 
    "user": "xiyouMc", 
    "avatar": "https://avatars0.githubusercontent.com/u/8032883?v=4&s=400"
}
```


