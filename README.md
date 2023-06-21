### Hi there 👋

<!--
**rarumdj/rarumdj** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Stats :chart_with_downwards_trend:

##### General Statistics

[![David Johnson's Github Stats](https://github-readme-stats.vercel.app/api?username=rarumdj&count_private=true&show_icons=true&theme=nightowl&include_all_commits=true&include_all_prs=true&show=reviews)](https://github.com/rarumdj)


##### Languages/Tools/Stack

[![David Johnson's Github Stats](https://github-readme-stats.vercel.app/api/top-langs?username=rarumdj&count_private=true&show_icons=true&theme=nightowl&langs_count=15)](https://github.com/rarumdj)


<!-- Add the following code to your profile's README.md file -->

<!-- Count Private Pull Requests -->
<script>
  fetch('https://api.github.com/users/rarumdj/events')
    .then(response => response.json())
    .then(data => {
      const privatePullRequests = data.filter(event => {
        return event.type === 'PullRequestEvent' && event.payload.pull_request.private;
      });

      const privatePRCount = privatePullRequests.length;

      // Display the count in your README
      document.getElementById('private-pr-count').innerText = privatePRCount.toString();
    })
    .catch(error => {
      console.error('Error:', error);
    });
</script>

<!-- Display the Count -->
**Private Pull Requests:**
<span id="private-pr-count">Loading...</span>

