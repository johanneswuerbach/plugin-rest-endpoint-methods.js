# Get a single comment (Legacy)

**This method is deprecated.**

**Deprecation Notice:** This endpoint route is deprecated and will be removed from the Teams API. We recommend migrating your existing code to use the new [`Get a single comment`](https://developer.github.com/v3/teams/discussion_comments/#get-a-single-comment) endpoint.

Get a specific comment on a team discussion. OAuth access tokens require the `read:discussion` [scope](https://developer.github.com/apps/building-oauth-apps/understanding-scopes-for-oauth-apps/).

```js
octokit.teams.getDiscussionCommentLegacy(
  team_id,
  discussion_number,
  comment_number
);
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>team_id</td><td>yes</td><td>

team_id parameter

</td></tr>
<tr><td>discussion_number</td><td>yes</td><td>

discussion_number parameter

</td></tr>
<tr><td>comment_number</td><td>yes</td><td>

comment_number parameter

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](endpoint.documentationUrl).