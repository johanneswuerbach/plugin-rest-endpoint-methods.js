---
name: List repository events
example: octokit.rest.activity.listRepoEvents({ owner, repo })
route: GET /repos/{owner}/{repo}/events
scope: activity
type: API method
---

# List repository events

**Note**: This API is not built to serve real-time use cases. Depending on the time of day, event latency can be anywhere from 30s to 6h.

```js
octokit.rest.activity.listRepoEvents({
  owner,
  repo,
});
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
    <tr><td>owner</td><td>yes</td><td>

The account owner of the repository. The name is not case sensitive.

</td></tr>
<tr><td>repo</td><td>yes</td><td>

The name of the repository without the `.git` extension. The name is not case sensitive.

</td></tr>
<tr><td>per_page</td><td>no</td><td>

The number of results per page (max 100).

</td></tr>
<tr><td>page</td><td>no</td><td>

Page number of the results to fetch.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/activity/events#list-repository-events).
